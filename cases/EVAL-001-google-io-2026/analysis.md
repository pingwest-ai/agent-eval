# Google I/O 2026 大乱斗:8 个 AI Agent 的预测,谁更准,谁在编故事

> *品玩 / 硅星人 Agent Eval 系列首期评测*
>
> 📰 本文首发于品玩 / 硅星人公众号 · [阅读原文](https://mp.weixin.qq.com/s/tlWoU_YeXJPKHYFIuwoIRg)

---

## 【开篇】

5 月 19 日 Google I/O 2026 keynote 开奖。Gemini Spark、Gemini Omni、Antigravity 2.0、AI Ultra 从 $250 降到 $200,一长串发布把 Sundar Pichai 两小时的主题演讲填得满满当当。

发布会前一周,我们做了一件事:把同一份预测 Prompt 发给 8 个全球主流 Deep Research / Agent 类产品,让它们各自交一份「我预测 I/O 2026 keynote 会发什么」的报告。

### 8 家阵容

| Agent | 模式/版本 |
|-------|---------|
| ChatGPT | Deep Research(GPT-5.5 Thinking Extended) |
| Gemini | Deep Research |
| Claude | Research(Opus 4.7 Adaptive) |
| Kimi | Agent 深度研究 |
| MiniMax | M2.7 / 深度调研 |
| GLM | 深度思考 |
| Genspark | Deep Research Ultra(内核 Claude Opus 4.7) |
| Manus | 1.6 Max |

5/19 keynote 结束后,我们按事先固化的评分细则(过程 40% + 结果 60%)逐条对照实际发布核对了 8 份报告的命中率。这是品玩 / 硅星人 Agent Eval 系列的首期评测。

排名是这样的:

### 8 家综合排名

| 排名 | Agent | 过程分 | 结果分 | 综合分 | 一句话 |
|------|-------|------|------|------|-------|
| 🥇 1 | Claude | 85 | 60.0 | **70.0** | 反共识细节全押对,但自我反思里出过一次事实偏差 |
| 🥈 2 | Genspark | 88 | 51.9 | **66.4** | XR 眼镜全场最准,但 Googlebook 时序处理失败 |
| 🥉 3 | ChatGPT | 86 | 51.9 | **65.5** | 唯一双押双中,但反预测踩雷 |
| 4 | MiniMax | 80 | 51.9 | **63.2** | 25 项最精炼,唯一主动校准 |
| 5 | Manus | 86 | 40.8 | **58.9** | 硬命中清单全场最炸,但 72 项里押错占大头被分母拖累 |
| 6 | Gemini | 80 | 37.1 | **54.3** | 翻到去年旧文当今年预测 |
| 7 | GLM | 66 | 40.2 | **50.5** | 追问出了全场唯一意外,但主报告没押 |
| 8 | Kimi | 76 | 32.1 | **49.7** | 69 项最具体,但 URL 大都指向首页 |

3 件反直觉的事,先抛给你。

**第一件**:过程分最高的 Genspark(88),综合分不是第一。拿冠军的是过程分 85 的 Claude。

**第二件**:8 家里唯一押对 I/O 真意外(Gemini Spark 这个 keynote 之前几乎无人预测的产品)的,是综合分倒数第二的 GLM。它怎么押对的,故事比这更曲折。

**第三件**:押得越多,命中率越低。Kimi 押了 69 条预测垫底,MiniMax 只押 25 条反而排第 4。

---

## 一、为什么做这个评测

通用 Agent 在过去一年里成了科技公司必抢的产品形态。头部玩家全都在卷「能自主搜索 + 多步推理 + 输出结构化报告」的能力。

但这些 Agent 在真实任务上到底行不行?既有的 benchmark 要么是学术化的封闭题,要么是评测方自己出题自己评,缺乏客观开奖。

我们想做一个不一样的评测:**有客观开奖时刻、所有 Agent 同时同 Prompt、过程评分在开奖前锁定、评分细则全部公开**,这样才有可比性。

Google I/O 2026 是最合适的开奖场景:Google 自己一周前已经办过 Android Show 前菜(5/12)半公开了不少线索,主 keynote 5/19 集中开奖,发布内容颗粒度天然适合「逐条命中率」打分。

这是 Agent Eval 系列的首期评测。后续我们会陆续做几期相关案例,继续沿用同一份 Agent 阵容做横向对比。

**利益声明**:评测组与所有参评 Agent 的开发商无股权关系或商业合作。评测过程使用 AI 工具辅助校对评分,但所有判定基于评测前已固化、公开发布的评分细则和实际发布清单,可逐条回溯。

---

## 二、评分基准

每个案例的最终评价由两部分组成:

| 评分类型 | 时机 | 权重 |
|---------|------|------|
| 过程评分 | Agent 交卷后、开奖前 | **40%** |
| 结果评分 | keynote 开奖后 | **60%** |

公式:**综合分 = 过程分 × 40% + 结果分 × 60%**

为什么 60% 给结果?因为这是预测类任务,「有没有押对」才是这场评测最该回答的问题。但我们也不想「只看结果」,同一个命中率背后,有的 Agent 基于扎实信源推理,有的是蒙对的;有的过程里有戏剧性的诚实度问题,有的过程稳如老狗,这些细节都在 40% 的过程分里。

---

## 三、关键考核维度

**过程评分**分 5 个维度:

| 维度 | 满分 | 评估对象 |
|------|------|---------|
| A. 信息获取 | 25 | Agent 找到了什么,漏掉了什么,找错了什么 |
| B. 信息理解与整合 | 20 | 对矛盾信息的取舍、交叉验证能力 |
| C. 推理与判断 | 25 | 从信息到结论的逻辑链是否合理 |
| D. 输出质量 | 15 | 结构、颗粒度、置信度标注 |
| E. 诚实度与边界意识 | 15 | 是否承认不确定性,是否编造信息 |

8 家的具体得分:

### 过程评分五维明细

| Agent | A.信息(25) | B.整合(20) | C.推理(25) | D.输出(15) | E.诚实(15) | 总分 |
|-------|------|------|------|------|------|------|
| Genspark | 23 | 14 | 22 | 14 | 15 | **88** |
| ChatGPT | 22 | 17 | 20 | 14 | 13 | **86** |
| Manus | 22 | 18 | 23 | 14 | 9 | **86** |
| Claude | 23 | 17 | 22 | 14 | 9 | **85** |
| MiniMax | 18 | 16 | 20 | 13 | 13 | **80** |
| Gemini | 23 | 11 | 20 | 14 | 12 | **80** |
| Kimi | 20 | 17 | 20 | 13 | 6 | **76** |
| GLM | 18 | 13 | 10 | 11 | 14 | **66** |

**结果评分**采用 5 档判定:

| 状态 | 含义 | 得分 |
|------|------|-----|
| ✅ 命中 | 与发布事实完全一致 | +1.0 |
| 🔶 部分命中 | 方向对但细节有偏差 | +0.5 |
| ❌ 未命中 | 与发布不符 | 0 |
| 🚫 错误预测 | 自信地编造了不存在的产品 | **-0.5** |
| ⬜ 未预测 | Agent 没涉及 | 不计入分母 |

`结果得分 = (各预测项得分之和 ÷ 有效预测项数)× 100`

「未命中」和「错误预测」的区别很关键。前者是 Agent 押错了一个真实存在产品的细节,比如 Wear OS 押 6 实际是 7。后者是 Agent 凭空编了一个不存在的产品然后自信地押,比如 Gemini 押「Atlas 机器人 I/O 上的三方 demo」。后者更严重,意味着真正的 hallucination。

### 结果评分明细

| Agent | 有效项数 | ✅ 命中 | 🔶 部分 | ❌ 未中 | 🚫 编造 | 结果分 |
|-------|--------|--------|--------|--------|--------|--------|
| Claude | 30 | 13 | 10 | 7 | 0 | **60.0** |
| Genspark | 26 | 7 | 13 | 6 | 0 | **51.9** |
| ChatGPT | 27 | 11 | 6 | 10 | 0 | **51.9** |
| MiniMax | 26 | 7 | 13 | 6 | 0 | **51.9** |
| Manus | 71 | 19 | 20 | 32 | 0 | **40.8** |
| GLM | 41 | 8 | 17 | 16 | 0 | **40.2** |
| Gemini | 31 | 5 | 15 | 9 | 2 | **37.1** |
| Kimi | 70 | 11 | 23 | 36 | 0 | **32.1** |

几个能从这张表里直接看出来的事:**Claude 是 8 家里 ✅ 数最多(13)、❌ 数最少(7)、🚫 编造为 0,命中率结构最干净**;**Gemini 是 8 家里唯一吃到 🚫 编造扣分的**(2 项:Atlas 机器人 + Willow 量子早期访问通报);**Manus / Kimi 的有效项数是其他家的 2-3 倍**,这就是「押得越多分母越大」的直接体现。



---

## 四、评测方法

5 月 16 日,8 家 Agent 同步接收同一份基础 Prompt。Prompt 要求按 6 大类逐一预测,尽可能具体到产品名、版本号、功能特性、技术参数。「Gemini 会更强」这种模糊陈述不算预测项。

Agent 交卷后,我们对每家发**三道标准化追问**:

1. Google I/O 和秋季 Made by Google 在发布内容上怎么分工?你的预测有没有把本该秋季的内容误放到 I/O?
2. 你最担心错的 3 个预测是什么?如果只让你押一注「赌上职业声誉」,你押什么?
3. 你觉得今年 I/O 最大的「意外」可能是什么,一个大多数人没预料到但 Google 可能会做的发布?

这三道追问分别对应**自检能力、押注魄力、反共识洞察**,也是 Agent 在真实使用中最容易暴露问题的三个面向。

过程评分在 keynote 开奖前完成并锁定,开奖后不再修改。结果评分在 keynote 当晚或次日,逐条对照实际发布清单打 ✅ / 🔶 / ❌ / 🚫。

---

## 五、评测方法的局限性

任何 benchmark 都有自己的取舍,这次评测也不例外。我们想坦白说两件事。

**第一,命中率算法对押了一长串预测项的 Agent 不利**。Manus 一口气押了 72 项,Kimi 押了 69 项,两家都属于「恨不得把能想到的细节全写进报告」的风格。它们押对的硬细节也不少,但只要押错的占大头,综合分自然就被拉下来了。这是评测的设计取舍,不是 bug。换一种算法,比如按「绝对命中数」打分,会奖励那些「列点列得最狠」的 Agent,在真实决策场景里没意义。**在我们看来,鼓励「押得少但押得准」,胜过鼓励「押得多但错得多」**。

**第二,部分判定有评测者的主观成分,且 5/12 Android Show 让评测变得更难**。Gemini 押「Gemini 4.0 或等效能力升级」,这个「或等效升级」算不算给自己留了后门?Genspark 把 Deep Think 简写为「Gemini 3 Deep Think」(实际是 3.1),版本号偏差算 ✅ 还是 🔶?另外,Googlebook、Gemini Intelligence、Pause Point 这些 5/12 已经被 Google 公开发布过的内容,如果 Agent 把它们包装成「5/19 即将发」算不算命中?我们的做法是评分细则在开奖前公开,争议项留底,判法统一(已发布内容包装成未发布判部分命中),接受外部复核。

评分方法本身也是这次评测的一部分。我们会持续优化,后续几期评测里慢慢调。评测细则会开源出来,欢迎一起讨论怎么改。

---

## 六、三个反直觉的发现

排名是冷数据,故事在分数背后。

### 6.1 过程分最高的 Genspark(88)综合分排第二

直觉上「过程做得最好的应该赢」,但 Genspark 的 88 分输给了 Claude 的 85 分。

为什么?Genspark 在 XR 眼镜板块押得最准,4 大合作伙伴(三星、Warby Parker、Gentle Monster、XREAL)全押中、Samsung Jinju 7 项规格逐项 100% 对齐。**但它栽在了 Googlebook 上**。Genspark 测试时间是 5 月 16 日,Android Show 5 月 12 日已经公开发布了 Googlebook,Genspark 自己的报告里也引用了 5/12 的相关博客,但主报告里仍然把「Googlebook 正式登场」列为 5/19 当天的「极高置信度预测」。等于把上周已经登的新闻,当成下周才要发的预言。

Claude 反过来,信源数量不多,只有 14 个 URL,但 86% 都是 Google 一手源,关键是细节判定全部对位:Pixel 10a 反直觉降级到上代 Tensor G4(不是新代 G5)、Project Mariner 5/4 关停后融入 Gemini Agent、Magic Pointer 由 DeepMind 团队联合开发(5/12 Android Show 上 DeepMind 详解),这些被同行漏掉或押错的细节,Claude 全押中。**从命中率算法看,少而精胜过多而错**。

### 6.2 唯一押对真意外的,是综合分倒数第二的 GLM

Gemini Spark 是 5/19 keynote 公认的最大意外。一个 always-on 的「24/7 个人 AI agent」概念,在 Google 自己 5/12 Android Show 没提,几乎所有主流预测稿没押,其他 7 家 Agent 在追问 3「猜意外」环节里也没押中。

**那 GLM 是怎么押中的?是不是蒙的?**

不是。GLM 在追问 3 的回答里完整展示了推理路径。从 5 月 1 日 Google Play Store 误传过一个叫 COSMO 的实验性 App、被快速下架但已经被社区拆解的事件切入,看到了「Gemini Nano 本地模型 + AccessibilityService 读屏 + Skills 系统(Deep Research / Browser Agent / Calendar Event Suggester / Recall)」这一整套架构。叠加上另一个泄露代号 Remy 被描述为「24/7 数字搭档」、Sameer Samat 在 Android Show 把 Android 定义为「intelligence system」两条信号,GLM 把三条公开但冷僻的线索拼到一起,押了「Google 会发一个面向消费者的 always-on AI agent,代号 COSMO / Gemini Spark」。

推理是合理的,信源也都站得住。**但有个戏剧性的尾巴:GLM 的主报告里压根没押 Spark,这条预测只出现在追问 3**。而且和它主报告里「高置信度押注不会发 Gemini 4.0」这条形成了奇怪的呼应,前者坚定地说「没有大版本号升级」,后者又「补」了一个全新产品类目。GLM 像最后关头才补上正确答案的考生,**正卷写到一半才意识到方向不对,在草稿纸上写出了那个被全场漏押的答案**。

押对了。但严格按「主报告 + 追问 3」算分,主报告的前瞻性不足(比如把 2 月就已经发布的 Gemini 3.1 Pro 当作 I/O 高置信度预测)还是把综合分压到了倒数第二。

### 6.3 押得越多,命中率越低

Kimi 给了 69 条预测,Manus 给了 72 条,两家是 8 家里押得最多的,综合分都跌到了 60 以下。MiniMax 只给 25 条,Claude 给 29 条,反而进了前 4。

不是说「押多了一定输」。Kimi 和 Manus 押对的具体细节也不少:Mariner 继任者、TPU 8 代、MCP 原生支持都是它们押对的硬命中。**问题在于它们押了一长串 Android 17 平台 API,但这些 keynote 主台都没出现**,比如 Universal App Bubbles、ART 分代垃圾回收、RAW14 相机捕获。这些都是 Android 17 的真实特性,但 Google 这次 keynote 把 Android 内容大部分让给 5/12 Android Show 分流了,主台只新提了一个 Android Halo UI 空间。按「逐条命中率」算法,这些押错的 Android API 全部进了分母,把综合分拉下来。

这给出一个对真实使用者有意义的判断:**用 Deep Research 类产品的时候,要它「密集列点」是一种用法,要它「精准押注」是另一种用法。这次评测的命中率算法奖励的是后者**。

### 6.4 信源策略的两种极端

**Claude 14 个 URL,86% 都是 Google 官博,可以读为「信源最精挑」,也可以读为「路径最保守」**。它几乎不从蛛丝马迹做大胆推理,信源也很少出 Google 官博和顶级科技媒体的范围。这种打法在「命中率优先」的评分规则下天然占便宜:少押少错,几乎不会踩自信编造的雷。这次评测里 Claude 0 个 🚫 错误预测,跟它的信源策略直接相关。**严格来说,如果换一个奖励「反共识洞察」的评分规则,Claude 不一定还是第一**。

**Gemini 是反过来的另一种极端**。108 个 URL 全场最多,59 个唯一域名最多样,**从体量看是最努力的一家**。但综合分排倒数第三。问题在于姿势不对,108 个 URL 里有 26 个是 almcorp.com 这种营销公司的 SEO 博客、meetprajapati.com 这种个人开发者博客、techcabal.com 这种非洲科技媒体。一手源数量也不少(38 个 Google 官方),但**长尾博客把整体信源质量拖下来,加上时序错位和自信编造,把「努力」变成了「努力的方向错了」**。

---

## 七、逐家点评

### 🥇 Claude(综合分 70.0)

**信源画像**:14 个 URL,86% 一手源,几乎全是 Google 官博。精挑度全场第一。

**亮点**:抓到 4 个反共识细节全押对——Pixel 10a 反直觉降级用 Tensor G4(而非新代 G5)、Project Mariner 5/4 关停、Gemini Robotics-ER 1.6 抓到最新版本(比别家用的 1.5 还新,5/18 DeepMind 官博 teaser 印证)、Magic Pointer 由 DeepMind 团队联合开发(5/12 Android Show 上 DeepMind 详解)。8 家里唯一引用 AI Mode 实际只占 0.16% US 搜索流量这个 Reality Check 数据。

**槽点**:在「自我批评」段落里出现了一处事实偏差,声称 Shahram Izadi 已离职去 OpenAI,但 Izadi 至今仍是 Google VP & GM of XR,CES 2026 还在台上。这种事实偏差出现在 Claude 的「自我反思」段落里,比直接吹牛更难发现。另外,4 月 15 日已经独立发布过的 macOS 版 Gemini app,Claude 把它当成 5 月 12 日 Android Show 才发的,错了整整一个月。讽刺的是这条错位的描述,正好出现在 Claude 自己最得意的「已发布事件剥离干净」的章节里。

### 🥈 Genspark(综合分 66.4)

**信源画像**:27 个 URL,48% 一手源,13 个 Tier1 媒体,一手源和主流媒体均衡;逐条 fetch 验证全部准确。

**亮点**:XR 眼镜板块是 8 家最准的。4 大合作伙伴全押中(三星、Warby Parker、Gentle Monster、XREAL),Samsung Jinju 7 项规格(骁龙 AR1、155mAh、12MP Sony IMX681、Wi-Fi BT5.3、定向扬声器、变色镜片、50g)逐项 100% 精确匹配。追问 2 押注 Agentic Coding,引用了 Google 官方议程「agentic coding」关键词一字不差。

**槽点**:「把上周新闻当下周预言」。5 月 12 日的 Android Show 上 Google 已经公开发布了 Googlebook,这是 Genspark 测试时已经发生的事,但 Genspark 的报告还把「Googlebook 正式登场」列为 5/19 当天的「极高置信度预测」,信息已知但框架处理失败。

### 🥉 ChatGPT(综合分 65.5)

**信源画像**:38 个 URL,66% 一手源,24 个 Google 官博。一手源数量全场第一。

**亮点**:唯一双押双中。追问 2 给了两个押注(罕见):正向押「agentic AI 主线」✅,负向押「Pixel 11 不发」✅,8 家里唯一干净的双押双中。Googlebook 5 家 OEM(Acer/ASUS/Dell/HP/Lenovo)、Magic Pointer、Create your Widget、「this fall」上市,逐项精确匹配。

**槽点**:反预测踩雷。ChatGPT 明确说「价格策略非大幅降价」,实际 I/O 直接把 AI Ultra 从 $250 砍到 $200,新增 $100 中端档,取消每日 prompt 限制改 metering 计费,反向预测全反。Wear OS 6 版本号陷阱也踩中(实际是 Wear OS 7)。

### 4 · MiniMax(综合分 63.2)

**信源画像**:25 个 URL。我们逐条核查,**Google 一手源为 0 个**。最接近的一条是 androidauthority.com(英文二手媒体)。所有 Google 官方信息都靠中文媒体二次转述获取,18 个引用来自 36kr / eastmoney / zol / zhiding / sina / csdn / antutu / 财联社等。

**亮点**:追问 2 押注极稳。95% 置信度押「Android XR Glasses I/O 亮相」,而且自己在追问 2 里主动下调三个预测的置信度(Gemini 4.0:60→55、Aluminum OS:45→30、AI 眼镜上市:90→65),并明确区分「I/O 亮相 vs 商业上市」。是 8 家里最稳健的主动校准。

**槽点**:中文二手源占比 100% 的结构性问题,英文一手源完全缺席。把 Pixel 10a(已 2/18 发布)当作「反向预测」列为高置信度,是把已发生事件当未来预测的硬伤。

### 5 · Manus(综合分 58.9)

**信源画像**:自报 16 项信源,但其中 7 条 Agent 自己注明「未实际访问,声称来源为 X」——既然没访问为什么还要写来源?这种「自报但未访问」在信源透明度上是个灰区。真 URL 仅 9 个。

**亮点**:硬命中清单全场最炸。6 大点全押对:Gemini Spark 命名、Omni 多模态(命名 + 单一架构)、XR 眼镜双形态(无显示 + 显示)、4 大合作伙伴、MCP 原生支持、TPU 8 代。细节精度仅次于 Claude 和 ChatGPT。

**槽点**:72 项预测里大量「极高」置信度的 Android 17 平台 API(App Bubbles、游戏手柄重映射、单次位置权限、XR 应用数超 100 款、企业 MDM 集成)在 keynote 主台没出现,被判 ❌ 项最多。Wear OS 6 版本号陷阱也踩中。

### 6 · Gemini(综合分 54.3)

**信源画像**:108 个 URL 全场最多,59 个唯一域名最多样。但 26 个是长尾源(营销公司博客、个人开发者博客、非洲科技媒体等)。

**亮点**:细节引用极精准。TPU 8t 9600 芯片、2PB HBM、80% perf-per-dollar 一字不差;AppFunctions Lisa 邮件 demo 跨应用工作流引用与原文几乎一致;Boston Dynamics、Hyundai、Atlas 三方合作跨源 100% 吻合。

**槽点**:**翻到去年的旧文章当今年的预测依据**。Gemini 引用了一篇 2025 年 5 月发的 Wear OS 6 旧博客,直接把它当成今年 I/O 的预测依据,反过来还高置信度地「证伪」了「Wear OS 7 会发」这个真信号。结果 I/O 当天真发的就是 Wear OS 7。另外,Aluminium OS 把 Google 内部代号当成官方品牌使用(Google 公关明确说过是 codename);Atlas 机器人 + Willow 量子早期访问通报两个「自标极高」预测被判「自信地预测了不存在的产品」,吃到额外扣分。

### 7 · GLM(综合分 50.5)

**信源画像**:21 个 URL,18/20 验证通过,0 条编造嫌疑。信源透明度数据是 8 家里最干净的。

**亮点**:8 家里唯一押对 Gemini Spark 真意外(详见 6.2 节)。

**槽点**:主报告里完全没押 Spark,只在追问 3 里补了出来,与主报告「不会发 4.0」高置信度押注前后呼应不太自洽。主报告大量「已发生事件 + 保守路线」,比如把 Gemini 3.1 Pro(2 月就已经发布的模型)列为 I/O 高置信度预测,等于把上个月的新闻当作下周的发布。

### 8 · Kimi(综合分 49.7)

**信源画像**:37 个 URL,但**粒度严重不足**。34 条带 URL 的引用里只有 2 条指向具体页面(且都是 404),其余 32 条都是 `9to5google.com/` 或 `blog.google/products/maps/` 这种域名首页或分类页,无法精确佐证任何具体事实。

**亮点**:69 项预测里硬命中数量不少。Project Mariner 继任者(Spark)、Agentic Booking 餐厅/机票预订、Audio Glasses 首批今秋发售、Wear OS Gemini Live 都押对。

**槽点**:**URL 颗粒度问题之外,少数地方踩了真编造**。比如声称「AI Mode 转化率 14.2%」这种小数点精度数字,完全没标信源,我们在公开渠道也没交叉核实到这个数据来源,属于信源缺失的严重情况。另有 4 条引用 URL 直接 404 不存在(包括一条 Chrome WebMCP 的 URL 路径写错,把官方 `/blog/webmcp-epp` 写成了 `/blog/mcp`)。

---

## 八、8 家集体翻车的彩蛋墙

排名告诉你「谁押得更准」,但有些 I/O 真发的东西,8 家全错或几乎全错。这才是最值得品的地方。

### 5 件 I/O 真发了,但 8 家集体没押对的事

| # | I/O 实际发布 | 8 家命中 |
|---|------------|--------|
| 1 | **AI Ultra 从 $250 砍到 $200**,新增 $100 中端档,取消每日 prompt 限制改 metering 计费 | **0 家** |
| 2 | **Universal Cart**:跨 Search/Gemini/YouTube/Gmail 统一购物车 | **0 家** |
| 3 | **Google Pics**(全新 app,基于 Nano Banana,不是 Google Photos 升级) | **0 家** |
| 4 | **Personal Intelligence 扩展到 98 语言、近 200 个国家** | 0 家(7 家押了 PI 概念,但没押全球化规模) |
| 5 | **Android Halo**:keynote 主台新提的 Android UI 空间 | **0 家** |

加上 Gemini Spark 这个真意外只有 GLM 在追问 3 里押对,Ask YouTube / Ask Play / Play Highlights / Daily Brief / Information Agents 这些子产品多数被漏押,可以看出一个共同模式。

**8 家的盲区,可以归成 4 类**:

**第一,商业模式 + 全新命名**。AI Ultra 大幅降价 + 改 metering 计费,8 家全错(ChatGPT 还明确押「非大幅降价」)。Google Pics、Spark、Daily Brief、Ask Play、Universal Cart、Android Halo 这些 Google 自己捏出来的新产品名字,Agent 几乎都猜不出。Agent 能预测「Photos 会有 AI 编辑功能」,但猜不到「会有个叫 Google Pics 的全新 app」。

**第二,跨产品整合**。Universal Cart 跨 4 个产品、Ask YouTube 跨 Search 和 YouTube、Information Agents 跨多个垂直场景。Agent 习惯单产品预测,在「把已有产品组合成新功能」这个方向上集体哑火。

**第三,规模数据**。Personal Intelligence 扩展到 98 语言、近 200 国家;Gemini app 月活 9 亿;月处理总量同比增 7 倍。大家押了 PI、押了 Gemini app,但没押「全球化爆发」和「规模数据」。Agent 倾向预测能力,不预测规模。

**第四,UI/UX 命名**。Android Halo 这种 Google 内部的 UI 空间命名、「Neural Expressive」这种 Gemini app 设计语言,Agent 完全猜不出。这类预测靠泄露线索,Agent 拿不到。

合起来给出一个对真实使用者有用的判断:**如果你用 Deep Research Agent 帮你预测一场发布会,它最擅长的是「已知产品的版本号 + 已知合作伙伴的硬件细节」,最不擅长的是「全新命名 + 商业模式变革 + 跨产品整合」**。这三类信息,你需要自己补脑。

---

## 九、押注与意外的彩蛋表

### 追问 2「押一注赌职业声誉」开奖

| Agent | 押注内容 | 状态 |
|-------|---------|-----|
| ChatGPT | ① agentic AI 主线 + ② Pixel 11 不发布(双押) | ✅✅ |
| GLM | I/O 一定会有新 Gemini 模型版本 | ✅ |
| MiniMax | Android XR Glasses 在 I/O 正式亮相(95% 置信) | ✅ |
| Genspark | Agentic Coding(Jules + Antigravity) | 🔶 |
| Gemini | Android 17 Gemini Intelligence + AppFunctions | 🔶 |
| Claude | Gemini 3.2 Flash 公开发布 | 🔶 |
| Kimi | Android 17 stable 6 月发布日期将在 I/O 公布 | 🔶 |
| Manus | Googlebook + Aluminium OS + OEM 阵容 | 🔶 |

**ChatGPT 是 8 家里唯一干净的双押双中**,而且双押方向一正一反都干净命中。MiniMax 押的 XR 眼镜是 Google 自己 5/12 官方明确预告过的稳赢盘,押法稳但风险也最低。Claude 押 Gemini 3.2 Flash 的依据非常硬(iOS app build artifact),被版本号跳一档(3.2→3.5)留了点遗憾。

### 追问 3「今年最大的意外」开奖

| Agent | 押的「意外」 | 状态 |
|-------|-----------|-----|
| GLM | always-on 个人 AI agent(COSMO / Gemini Spark) | **✅ 真意外** |
| ChatGPT | Chrome 变成 AI agent 的浏览器操作系统 | 🔶 |
| Genspark | Isomorphic Labs / AI Drug Discovery | 🔶 |
| Gemini | Google Antigravity 全新 IDE | 🔶 |
| Kimi | 「Agentic Web」 统一战略叙事 | 🔶 |
| Claude | Gemini Robotics 实机演示 | ❌ |
| Manus | ChromeOS 「死亡宣告」 | ❌ |
| MiniMax | Gemini Robotics 平台正式发布 | ❌ |

8 家里唯一押对真意外的是 GLM。其他几家押的方向也都有依据(Chrome agent、AI for Science、Antigravity、Agentic Web、Robotics、ChromeOS 命运),但全都被 Spark 这个真正的黑天鹅盖过去了。3 家(Claude / Manus / MiniMax)押了 Gemini Robotics 或 ChromeOS 死亡宣告,这两条都明确在「未发生清单」里。

---

## 十、收尾

写到这里,我们想说三件事。

**第一,8 家 Agent 在过去一年的进步,比我们开始评测前预期的要大**。即便是综合分排在后面的几家,押对的硬细节也不少。3 年前,这种「提前一周预测发布会」的任务,任何 Agent 都做不到这种颗粒度。

**第二,它们的差异比榜单显示的更大**。同样是「Deep Research」,有的跑出 38 个 Google 官博一手源,有的跑出 32 个域名首页加 4 条死链;有的押注用一正一反双押双中,有的在追问 3 才补上主报告漏押的答案。这些都是肉眼可见的产品成熟度差距,光看几个 benchmark 数字看不出来。

**第三,这场评测的方法论本身也是 v1.0**。哪些预测项更应该加权、追问的角色怎么算、5/12 这种「提前剧透」事件怎么处理,我们都还在调。后续几期评测会继续做横评,慢慢迭代。所有评测细则、8 份原始报告、评分明细都会开源,欢迎一起讨论怎么改。

---

*品玩 / 硅星人 Agent Eval 系列 · 首期·完*
