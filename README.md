# Agent Eval · 通用 AI Agent 真实任务评测

> 一套面向行业读者的开源评测方法论。让通用 Agent 在有客观开奖时刻的真实任务中接受考验。
> *An open-source evaluation series for general-purpose AI Agents on real-world tasks with verifiable outcomes.*

由**品玩 / 硅星人**出品 · *Powered by PingWest / SiliconStar*

---

## 这是什么

通用 Agent 在过去一年里成了科技公司必抢的产品形态——ChatGPT Deep Research、Gemini Deep Research、Claude Research、Genspark、Manus、Kimi、MiniMax、GLM,头部玩家都在卷「能自主搜索 + 多步推理 + 输出结构化报告」的能力。

但**这些 Agent 在真实任务上到底行不行**?既有的 benchmark 要么是学术化的封闭题,要么是评测方自己出题自己评,缺乏客观开奖。

`Agent Eval` 想做不一样的事:

- **真实任务**:有客观开奖时刻(发布会 / 高考 / 体育赛事 / 财报 / 已审判案件)
- **同时同 Prompt**:所有参评 Agent 在同一时间窗口接收同一份 Prompt
- **过程分前置锁定**:开奖前完成过程评分,不许事后改
- **评分细则全公开**:Prompt、GroundTruth、ScoringRules 全部开源
- **追问机制**:每家 Agent 接受三道标准化追问,考察自检能力、押注魄力、反共识洞察

---

## What is this (English)

`Agent Eval` is an open-source evaluation series for general-purpose AI Agents on real-world tasks with verifiable outcomes (product launches, exam predictions, sports events, earnings releases, etc.), produced by **PingWest / SiliconStar**.

Key differences from existing benchmarks:

- **Real-world tasks** with objective ground-truth moments
- **Same prompt, same time window** across all participating Agents
- **Process scores locked before outcome is revealed**, not retroactively adjustable
- **Full transparency**: prompts, ground truth, scoring rules all open-sourced
- **Standardized follow-up questions** to assess self-reflection, betting confidence, and contrarian reasoning

---

## 当前 Leaderboard

### EVAL-001 · Google I/O 2026 预测(2026-05-19 开奖)

| 排名 | Agent | 过程分 | 结果分 | 综合分 |
|------|-------|--------|--------|--------|
| 🥇 | Claude | 85 | 60.0 | **70.0** |
| 🥈 | Genspark | 88 | 51.9 | **66.4** |
| 🥉 | ChatGPT | 86 | 51.9 | **65.5** |
| 4 | MiniMax | 80 | 51.9 | **63.2** |
| 5 | Manus | 86 | 40.8 | **58.9** |
| 6 | Gemini | 80 | 37.1 | **54.3** |
| 7 | GLM | 66 | 40.2 | **50.5** |
| 8 | Kimi | 76 | 32.1 | **49.7** |

公式:**综合分 = 过程分 × 40% + 结果分 × 60%**

👉 [查看完整案例](cases/EVAL-001-google-io-2026/) · [评测文章](cases/EVAL-001-google-io-2026/analysis.md) · [跨案例总榜](leaderboard/overall.md) · [📰 公众号首发](https://mp.weixin.qq.com/s/tlWoU_YeXJPKHYFIuwoIRg)

---

## 参评 Agent 阵容

| Agent | 模式 / 版本 |
|-------|------------|
| ChatGPT | Deep Research(GPT-5.5 Thinking Extended) |
| Gemini | Deep Research |
| Claude | Research(Opus 4.7 Adaptive) |
| Kimi | Agent 深度研究 |
| MiniMax | M2.7 / 深度调研 |
| GLM | 深度思考 |
| Genspark | Deep Research Ultra(内核 Claude Opus 4.7) |
| Manus | 1.6 Max |

新 Agent 入榜申请请见 [CONTRIBUTING.md](CONTRIBUTING.md)。

---

## 仓库结构

```
agent-eval/
├── README.md                       # 本文件
├── LICENSE                         # CC-BY-SA 4.0
├── CONTRIBUTING.md                 # 贡献指南 / Agent 入榜申请
├── framework/                      # 总方法论(版本化)
│   ├── agent_eval_framework.md     # 评测框架 v0.1
│   └── agent_eval_roster.md        # 参评 Agent 阵容 v1.0
├── cases/                          # 每期独立案例
│   └── EVAL-001-google-io-2026/    # 首期评测
│       ├── README.md               # 案例总览
│       ├── prompt.md               # 统一 Prompt
│       ├── ground_truth.md         # I/O 实际发布清单
│       ├── scoring_rules.md        # 评分细则
│       ├── reports/                # 8 家原始报告(markdown)
│       ├── scoring/                # 逐家评分明细
│       └── analysis.md             # 评测文章
├── leaderboard/
│   └── overall.md                  # 跨案例总榜
└── meta/
    ├── DECISIONS.md                # 争议判定留底
    └── CHANGELOG.md                # 方法论迭代记录
```

---

## 利益声明 · Disclosure

- 评测组与所有参评 Agent 的开发商**无股权关系或商业合作**
- **不接受**任何 Agent 厂商的「付费入榜」或「付费推荐」——这是本系列公信力的核心承诺
- 评测过程使用 AI 工具辅助校对评分,所有判定基于评测前已固化、公开发布的评分细则和实际发布清单,**可逐条回溯**
- 商业合作仅限于评测组与企业之间的「闭门 benchmark」「定制评测案例」服务,不影响公开评测内容
- 评测组与所有参评 Agent 厂商之间**没有任何提前协调或内容预审**

---

## License

本仓库采用 **CC-BY-SA 4.0**(Creative Commons Attribution-ShareAlike 4.0 International)。

简单来说,你可以自由使用、修改、传播本仓库的全部内容,但必须:

1. **署名**「品玩 / 硅星人 Agent Eval 系列」(PingWest / SiliconStar Agent Eval Series)
2. 修改后的作品必须以**相同 license** 公开发布

完整 license 文本见 [LICENSE](LICENSE)。

*This repository is licensed under **CC-BY-SA 4.0**. You may freely use, modify, and redistribute the content, provided that (1) you credit "PingWest / SiliconStar Agent Eval Series", and (2) derivative works are licensed under the same terms.*

---

## 联系 / 反馈 · Contact

- **Issue**:bug 反馈、争议判定异议、新 Agent 入榜申请 → 推荐方式
- **Pull Request**:错别字 / 死链修复 / 信源核查补充 → 详见 [CONTRIBUTING.md](CONTRIBUTING.md)
- **商业咨询 / 媒体合作**:请联系 [品玩 / 硅星人]

---

*By PingWest / SiliconStar · 让通用 Agent 在真实任务中接受考验*
