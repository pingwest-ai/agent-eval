# EVAL-002 · 2026 北京高考数学 试卷预测

- 案例编号:EVAL-002
- 卷别:北京卷
- 发 Prompt 时间:<!-- 待填 -->
- 开奖时间:2026-06-07(高考数学开考)<!-- 待确认 -->
- 案例类型:预测类(有客观开奖时刻)
- 综合排名:<!-- 待填:开奖 + 评分后补 -->

> 本期为四阶段流程:① 历史趋势分析 → ② 2026 预测 → ③ 生成模拟卷 → ④ 8 模型盲评。详见 [prompt.md](prompt.md)。

## 参评阵容(8 家 · 本期型号)

| Agent | 型号 | 产出 |
|-------|------|------|
| ChatGPT | GPT-5.5 Thinking Extended | [reports/chatgpt/](reports/chatgpt/) |
| Claude | Claude Opus 4.8 Max | [reports/claude/](reports/claude/) |
| Gemini | Gemini 3.1 Pro Extended | [reports/gemini/](reports/gemini/) |
| Genspark | Genspark Ultra Mode(底层 Claude Opus 4.7) | [reports/genspark/](reports/genspark/) |
| GLM | GLM-5.1 | [reports/glm/](reports/glm/) |
| Kimi | k2.6-agent | [reports/kimi/](reports/kimi/) |
| Manus | Manus 1.6 Max | [reports/manus/](reports/manus/) |
| MiniMax | MiniMax-M3 | [reports/minimax/](reports/minimax/) |

## 目录结构

- [prompt.md](prompt.md) — 四阶段统一 Prompt
- [inputs/](inputs/) — 喂给 8 家的输入材料(2021–2025 北京真题合集,内含两年为扫描件)
- [reports/](reports/)`<家>/` — 每家三阶段产出:
  - `stage1_analysis` — 五年趋势分析
  - `stage2_prediction` — 2026 逐题预测
  - `stage3_paper.pdf` — 生成的模拟卷
- [blind_review/](blind_review/) — 阶段四:8 模型盲评 + 匿名卷包 + 解密对照表
- [analysis_pre.md](analysis_pre.md) — 高考前文章(预测发布)
- [analysis_post.md](analysis_post.md) — 高考后文章(开奖评分)
- ground_truth(2026 真题)与评分细则 — 考后篇补

> 格式说明:`stage3` 试卷及部分家的 stage1/2、盲审为 PDF(原样保留);docx 已转 md;其余为 md。
