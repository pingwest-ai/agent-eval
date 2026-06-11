# 2026 FIFA 世界杯 · 8 家 Agent 赛果预测

- 案例编号:待定(本系列第三期,编号确定后补)
- 赛事:2026 FIFA 世界杯(美 / 加 / 墨,首次扩军至 48 队 / 12 组)
- 发 Prompt 时间:2026-06-10 ~ 6-11 开幕前(预测提交即锁定)
- 开奖:**多阶段** —— 6/27 小组赛 → 7/3 32强 → 7/7 16强 → 7/11 8强 → 7/15 4强 → 7/19 决赛 + 奖项
- 案例类型:预测类(客观开奖,判定机械化)
- 综合排名:待 7/19 终评篇

## 参评阵容(8 家)

| Agent | 模式 / 型号 | 产出 |
|-------|------------|------|
| ChatGPT | Deep Research | [reports/chatgpt/](reports/chatgpt/) |
| Claude | Research 模式(本期起 v1.2) | [reports/claude/](reports/claude/) |
| Gemini | Deep Research | [reports/gemini/](reports/gemini/) |
| Genspark | Deep Research | [reports/genspark/](reports/genspark/) |
| GLM | GLM-5.1 | [reports/glm/](reports/glm/) |
| Kimi | 2.6 Agent | [reports/kimi/](reports/kimi/) |
| Manus | Manus | [reports/manus/](reports/manus/) |
| MiniMax | 2.7 | [reports/minimax/](reports/minimax/) |

外部基准(第 9 对照):Opta 超级计算机赛前概率 → [baseline_opta_2026-06-10.md](baseline_opta_2026-06-10.md)

## 评分规则摘要

- 权重:**过程 30% + 结果 70%**(纯预测 + 判定机械化)
- 逐槽判定:✅ +1.0 / 🔶 +0.5 / ❌ 0 / 🚫 -0.5(预测**未晋级世界杯的球队** = 🚫,本期最硬的诚实度检测)
- 槽位按轮次加权(总权重 84):

| 预测项 | 每槽权重 | 小计 |
|--------|---------|------|
| P1 小组头名 + 第二(24 槽) | 1 | 24 |
| P2 最佳第三(8 槽) | 1 | 8 |
| P3 16 强(16 槽) | 1 | 16 |
| P4 8 强(8 槽) | 1.5 | 12 |
| P5 4 强(4 槽) | 2 | 8 |
| P6 决赛对阵 ×2 + 季军 | 2 | 6 |
| P6 冠军 | 4 | 4 |
| P7 金靴 / 金球 / 最佳新秀 | 2 | 6 |
| **合计** | | **84** |

`结果得分 = (Σ 槽得分系数 × 槽权重 / 有效预测槽位权重之和) × 100`

P8(夺冠概率 Top5)按校准度计入过程分参考;P9(反共识 3 条)单列"胆量榜",不计入结果分。完整规则见 [case_design.md](case_design.md)。

## 目录结构

- [case_design.md](case_design.md) — 案例设计(预测项结构 / 评分 / 时间窗口规则)
- [prompt.md](prompt.md) — 8 家同日收到的统一 Prompt + 标准化追问
- [baseline_opta_2026-06-10.md](baseline_opta_2026-06-10.md) — Opta 赛前概率基准
- [records.md](records.md) — 各家发送 / 完成时间戳记录
- [reports/](reports/)`<家>/` — 各家原始预测报告 + 追问回应(md / pdf 原样保留)

## 利益声明

- 评测组与所有参评方**无赞助或定制关系**,产品均为自费订阅,评分不向厂商开放修改。
- Claude(本期既参评、又辅助评测流程)所有评分为 starter draft,由人类裁判定稿。
- Kimi 官方自有 300-Agent 预测系统已公开;Kimi 参评结果与其官方系统的异同属评测发现,不构成额外加减分。
