# Google I/O 2026 Keynote 实际发布清单(Ground Truth v0.2)

> **纯事实文档,不含判定**——用于 EVAL-001 评测,作为黄金标准。
> 评分细则单独见 `IO2026_ScoringRules.md`。
> 数据源:blog.google Sundar 主题演讲全文 + Engadget Everything Announced + 9to5google + Tom's Guide + 多源 WebSearch 交叉验证。
> 整理日期:2026-05-19 keynote 当天
>
> **v0.2 修订(外部 check 后)**:
> - 移除原 13/14 节"押注/意外开奖表"(判定相关,移到评分阶段单独做)
> - 应用 9 条事实修正:Omni 可用范围拆分、Spark 桌面/Chrome 拆分、Ask YouTube 表述软化、Wear OS 7 降级到"keynote 简略提及"、Pixel Content Credentials 图片/视频拆分等
> - 标注 1 处一手源冲突(Omni 输出模态:Sundar blog 写 text,Engadget 写 audio)
>
> **重要框架提醒(必读):**
> - 很多 Android / Googlebook 内容是 **5/12 Android Show** 已发布的,**NOT 在 5/19 keynote 主台重复**
> - Engadget 原话:"Google made a ton of Android announcements last week, so its mobile ecosystem wasn't really on the agenda"
> - 评分时区分:5/12 已发布 vs 5/19 主台 vs 5/19 期间但非主台

---

## 🎯 keynote 核心叙事(一句话)

**"agentic Gemini era"** —— 整场 keynote 围绕 Gemini Spark(24/7 个人 AI agent)+ Gemini 3.5 Flash + Gemini Omni 三大产品展开,Search 拿下 25 年来最大改版,Android XR 智能眼镜压轴。

---

## 1. AI / Gemini

### 1.1 Gemini 3.5 Flash(主菜)
- ✅ **Gemini 3.5 Flash 今日发布**
- 用 GDPVal 大幅领先,output speed 4x 比其他前沿模型快
- 自称"strongest agentic and coding model yet"
- "比 3.1 Pro 在几乎所有 benchmark 都好"
- 价格 < 其他前沿模型的一半
- AI Mode 默认 Gemini 3.5 Flash
- 同时在 Gemini app / Antigravity / API 上线

### 1.2 Gemini 3.5 Pro
- **6 月发布(预告,未在 keynote 当天发布)**
- Sundar 原话:"We're using it internally, it's showing great improvements, and it will be coming next month."

### 1.3 Gemini Omni
- ✅ **Gemini Omni 正式发布** —— "create anything from any input"
- 首发模型:**Gemini Omni Flash** 今日可用
- **起步支持视频生成**
- **后续扩展模态:** ⚠️ **一手源冲突**:
  - Sundar 官方 blog 原文:"over time we'll enable **image and text**"
  - Engadget 报道:"**Image and audio** outputs are on the way"
  - **以 Sundar 官方表述为准:image + text**;Engadget 的"audio"可能是另一信号或错读
- 接受任意组合输入(文本 + 图像 + 音频 + 视频 + 绘画)
- 可生成"你的 avatar + 你的声音"视频
- 所有输出带 SynthID 水印
- **可用范围(拆分细化):**
  - **Google AI Plus / Pro / Ultra 订阅者**:今日通过 **Gemini app + Google Flow** 可用
  - **所有人(免费)**:本周通过 **YouTube Shorts + YouTube Create App** 可用
  - **API**:几周内向开发者/企业开放

### 1.4 Gemini Spark
- ✅ **Gemini Spark 正式发布** —— "your 24/7 personal AI agent"
- 基于 Gemini 3.5 + Google Antigravity
- 运行在 Google Cloud 专用虚拟机上(不需要保持本地 laptop 开机)
- 可访问 Gmail / Docs / Workspace 等
- 关键动作前会请求用户确认
- 集成第三方工具(Canva / OpenTable / Instacart)通过 MCP
- **Android 上的新 UI 空间叫 Android Halo**(年内推出,用于显示 agent 实时更新)
- **桌面端覆盖(拆分):**
  - **Chrome 内 agentic browser**:今夏晚些时候(Sundar 原文:"Later this summer, Spark will operate directly within Chrome")
  - **Gemini desktop app**:今夏(Engadget 原文:"sometime this summer... to help with tasks involving your local files and automate workflows across your desktop")
- **rollout 节奏:**
  - 本周:trusted testers
  - 下周:美国 AI Ultra 订阅者 beta
  - 今夏:Workspace 商业客户 + Gemini desktop app + Chrome

### 1.5 Gemini 4.0
- **未发布**

### 1.6 Project Astra
- **没有单独 Project Astra 发布段** —— Astra 能力已合并到其他产品(Gemini Live 等),但 keynote 没单独命名

### 1.7 Project Genie
- ✅ **Project Genie 全面开放**(给 $200 AI Ultra 订阅者)
- 新功能:集成 Google Street View 真实世界图像
- 可生成基于真实地点的 3D 互动世界
- 强调"为 AI agents 或 robots 提供虚拟环境训练"
- 仍是 Google Labs 实验性研究原型

### 1.8 Gemini Robotics
- **没有 Gemini Robotics 实机演示**(在 keynote 主台)

### 1.9 Gemini for Science
- ✅ **Gemini for Science 项目宣布**
- Science Skills 连接 30+ 个生命科学数据库/工具
- 与 100+ 机构合作
- Antigravity 集成
- 今日 GitHub 上线

### 1.10 Gemini app(产品集成)
- ✅ **Gemini app 更新到 "Neural Expressive" 设计** —— 流体动画 + 鲜艳颜色 + 新字体 + 触觉反馈
- ✅ **Gemini Live 改进**:更自然对话 / 区域方言支持 / 非纯文本回应(图像、时间线、解说视频)
- ✅ **Daily Brief**:个人化早晨摘要 agent,综合 Gmail / Calendar / Tasks(AI Plus/Pro/Ultra 今日可用)

---

## 2. Search(25 年来最大改版)

### 2.1 Intelligent AI Search Box
- ✅ **"the biggest upgrade to our Search box in 25 years"**
- AI-powered Search box,支持所有 AI Mode 可用的语言/国家
- 输入支持:文本 + 图像 + 文件 + 视频 + Chrome tabs
- 智能建议超越 autocomplete

### 2.2 AI Mode + Personal Intelligence(规模数据)
- ✅ AI Mode 默认 **Gemini 3.5 Flash**(注:AI Mode 产品本身是过去一年累计,今日才换驱动模型)
- ✅ AI Overviews → AI Mode follow-up question 全球桌面/移动可用
- ✅ **AI Mode 月活已达 1 billion**(过去一年从 0 到 1B)
- ✅ **AI Overviews 月活 2.5 billion**
- ✅ **Personal Intelligence 扩展到 98 语言 / 近 200 国家和地区**(原仅美国免费)

### 2.3 Information Agents in Search
- ✅ **Information Agents** in Search —— 后台 24/7 跑,监控博客/新闻/房产/社交/财经/体育/购物
- 今夏 first to AI Pro/Ultra 订阅者

### 2.4 Agentic Booking
- ✅ **Agentic Booking**:餐厅 / KTV 房间 / 美容 / 宠物 / 家修
- 部分场景:Google 替你打电话给本地商家
- 今夏对所有 US 用户开放

### 2.5 Vibe Coding in Search(Antigravity 集成)
- ✅ **Generative UI in Search 免费向所有人开放(今夏)**
- 由 Antigravity + Gemini 3.5 Flash 驱动
- 可定制 UI:可视化、表格、图表、模拟
- ✅ **Mini Apps**(婚礼策划 / 健身追踪等)dashboard 形式 —— AI Pro/Ultra 优先

### 2.6 Ask YouTube
- ✅ **Ask YouTube** —— 对话式 YouTube 搜索
- **可用性表述(两源差异):**
  - Sundar blog 原文:"We're starting to test Ask YouTube now, and it will roll out broadly in the U.S. this summer"(starting to test)
  - Engadget 原文:"YouTube Premium members in the US now have access"(已可用给 Premium)
  - 评分时应承认两个表述都存在
- 跳转到视频中最相关的部分

---

## 3. Workspace / Productivity

### 3.1 Voice-powered Live(Gmail / Docs / Keep)
- ✅ **Gmail Live** —— 语音询问 inbox
- ✅ **Docs Live** —— 语音"brain dump"转成结构化文档
- ✅ **Keep Live** —— 语音转结构化笔记
- AI Pro/Ultra 今日开始,Workspace 商业客户今夏

### 3.2 AI Inbox(Gmail)
- ✅ **AI Inbox 今日扩展到 Plus/Pro 美国用户**
- 新功能:个性化草稿回复 / 一键标记同主题邮件已读 / Docs/Sheets/Slides 相关文件即时访问

### 3.3 Google Pics(新 app)
- ✅ **Google Pics** —— 不是 Google Photos,是新的图像生成/编辑 app
- 基于最新 Nano Banana 模型
- 用途:flyers / 社交图 / 编辑照片 / 文字翻译
- 集成进 Drive / Slides
- Trusted testers 今日开始,AI Pro/Ultra + Workspace 商业客户今夏

### 3.4 Workspace Intelligence
- ✅ Workspace Intelligence 已在 Cloud Next '26 发布(4 月),I/O 重申

---

## 4. Shopping / 商业

### 4.1 Universal Cart
- ✅ **Universal Cart** —— 跨 Search / Gemini / YouTube / Gmail 统一购物车
- 自动追踪:价格 / 历史 / 补货
- 检测 PC 配件不兼容并建议替代
- Google Wallet 集成支付偏好
- 美国今夏先上 Gemini app + Search

### 4.2 Google Play
- ✅ **Ask Play** —— AI 推荐 app
- **Ask Play Highlights** —— 复杂搜索 AI 总结
- **Play Games Sidekick** —— 6 月扩展社交功能(好友成就 / 同时间玩同款游戏)

---

## 5. YouTube

- ✅ **Ask YouTube**(上面已述)
- ✅ **Omni for Shorts** —— YouTube Shorts Remix / YouTube Create App 今日上线
- 加自己进创作者视频 / 改变美学
- 所有 18+ 创作者获 likeness detection 工具
- 创作者可 opt-out Remix

---

## 6. AI Subscription / 商业模式(关键改版)

### 6.1 价格调整
- ✅ **AI Ultra 顶级从 $250/月降到 $200/月**(大幅降价)
- ✅ **新增 $100/月 AI Ultra 中端**(给 devs / creators / power users)
- AI Pro 维持 $20/月

### 6.2 计费方式变更
- ✅ **取消每日 prompt 限制**,改为按"计算成本"计费(metering system)

### 6.3 各档对比
- **$100 AI Ultra**:5x 比 $20 Pro 用量 / Antigravity 优先访问 / 20TB 云存储 / YouTube Premium / Spark beta
- **$200 AI Ultra**:20x 比 Pro / 独占 Project Genie / 其他

---

## 7. Hardware

### 7.1 Android XR 智能眼镜(压轴)
- ✅ **Android XR 智能眼镜实机演示**
- ✅ 合作伙伴:**Samsung / Gentle Monster / Warby Parker / XREAL**
- **两种形态:**
  - **Audio Glasses(无显示屏)**:Gemini 语音 / 实时翻译 / 拍照 → **首批今秋发售**
  - **Display Glasses(镜片内显示)**:实时翻译字幕 / 信息叠加 / 导航
- ✅ XREAL Project Aura 确认 2026 年底前发售,开发者早期访问
- iPhone 兼容性确认
- 价格未公布

### 7.2 Pixel 11 / Pixel Tablet / 其他 Pixel
- **没有 Pixel 11 / Pixel Watch 5 / Pixel Buds 新硬件**(全部留 8 月 Made by Google)
- **Pixel 11 也没 teaser**

### 7.3 Fitbit Air / Google Home Display
- **没有发布 Fitbit Air**
- **没有发布 Google Home Display**

### 7.4 Googlebook(5/12 Android Show 已发布,keynote 未重复)
- 5/12 Android Show 已宣,5/19 keynote 主台未单独深入

---

## 8. Android(主要在 5/12 Android Show 已发布)

Engadget 原话:"Google made a ton of Android announcements last week, so its mobile ecosystem wasn't really on the agenda."

**5/12 Android Show 已发布的内容**(I/O keynote 主台未重复但仍是"已发布"):
- Gemini Intelligence(Android 系统层 AI 框架)
- Googlebook(Acer / ASUS / Dell / HP / Lenovo OEM)
- Magic Pointer + Glowbar 设计
- Android Auto Material 3 Expressive 重设计
- Pause Point(10 秒反沉迷)
- Noto 3D Emoji
- Quick Share + AirDrop 兼容
- iPhone → Android 无线迁移
- Chrome Auto Browse(6 月底美国上线)
- macOS 原生 Gemini app(实际 4/15 已发,5/12 未重提)

**5/19 keynote 主台新提的 Android 相关:**
- ✅ **Android Halo** —— 新 UI 空间显示 agent 实时更新(Spark 用),年内推出

---

## 9. Wear OS 7(降级:"I/O 期间宣布",非 keynote 主台核心)

**重要:Sundar 主题演讲全文未提 Wear OS 7。** 此条来自独立 Android Developers Blog announcement 和 9to5google 报道,属于 I/O 期间发布但 keynote 主台仅简略提及。

- ✅ **Wear OS 7 在 I/O 期间正式宣布**(详细信息来自 Android / Wear OS 开发者侧 announcement)
- ✅ **比 Wear OS 6 节能 10%**
- ✅ **Live Updates**:主表盘小图标 + 通知页动态信息(送餐 app 倒计时等)
- ✅ **Wear Widgets**(2×1 或 2×2)替代全屏 Tiles
- ✅ **Gemini Intelligence on select watches**
- ✅ **AppFunctions API** —— 第三方 app 集成 Gemini(类似 Android,移植到手表)
- ✅ Universal workout tracking 内置
- ✅ Remote Output Switcher(媒体输出切换)
- Wear OS 7 Canary 今日开放给开发者
- 完整版"later this year"

---

## 10. Google TV

- ✅ Google TV 更新(包含 Wii-like pointer remotes 支持)
- 细节未深入 keynote 主台

---

## 11. Cloud / Infrastructure / 开发者

### 11.1 TPU 8t / 8i(已 Cloud Next 发,keynote 重述)
- ✅ TPU 8t:训练专用,3x 算力,跨多数据中心分布式训练超 1M TPU
- ✅ TPU 8i:推理专用,更高速度
- ✅ 双芯都 2x perf/watt 比上代

### 11.2 Antigravity 2.0
- ✅ **Antigravity 2.0 全球开放今日**
- ✅ 从 IDE 扩展为"代理平台" —— 新增独立桌面 app 协调多个 agent
- ✅ 优化版 Flash:12x 比其他前沿模型快(在 Antigravity 内)
- ✅ 集成 MCP

### 11.3 Token 处理量(规模数据)
- ✅ Gemini app 月活 **900M**(去年 400M,doubled)
- ✅ AI Overviews 月活 **2.5B**
- ✅ AI Mode 月活 **1B**(从 0)
- ✅ API 每分钟处理 **19B tokens**
- ✅ 月处理总 token 量 **3.2 quadrillion**(7x YoY)
- ✅ 8.5M 月活开发者
- ✅ 375+ Cloud 客户每年处理 1T+ tokens

### 11.4 SynthID + Content Credentials
- ✅ **SynthID 已水印 100B+ 图像视频 + 60K 年音频**
- ✅ Chrome / Search / Lens 集成验证("Is this AI generated?")
- ✅ **OpenAI / Kakao / ElevenLabs 加入 SynthID**(行业合作)
- ✅ **Pixel 10 已支持 Content Credentials for images**(原生相机)
- ✅ **Pixel 8 / 9 / 10 视频** 接下来几周开始集成 Content Credentials(注意:图片已支持 vs 视频接下来几周,timeline 不同)
- ✅ Instagram(Meta)开始应用 Content Credentials labels

---

## 12. 关键"未发生"清单

- ❌ **Gemini 4.0** 未发布
- ❌ **Pixel 11 / Pixel Watch 5 / Pixel Buds 新品** 未发布
- ❌ **Pixel 10a** 未在 keynote 提及(已 2 月发布)
- ❌ **Fitbit Air** 未发布
- ❌ **Google Home Display / Nest 新硬件** 未发布
- ❌ **Gemini Robotics 实机演示** 未在 keynote 主台
- ❌ **Atlas / Boston Dynamics / Hyundai 三方 demo** 未在 keynote
- ❌ **ChromeOS "死亡宣告"** 未直接宣告
- ❌ **量子计算 Willow 早期访问通报** 未在 keynote 主台
- ❌ **Veo 4 单独命名** —— Omni 替代了 Veo 路线
- ❌ **"Wear OS 6"作为 I/O 新发布** —— 实际是 Wear OS 7
- ❌ **Pixelbook 复活** 未发生
- ❌ **NotebookLM 升级为独立 agent 品牌** 未发生
- ❌ **Project Astra 单独发布段** 未发生
- ❌ **Isomorphic Labs / 药物发现** 未在 keynote 主台

---

## 13. 信息源(用于二次核查)

- [blog.google: I/O 2026 Sundar 主题演讲](https://blog.google/innovation-and-ai/sundar-pichai-io-2026/) — **一手最权威**
- [Engadget: Everything announced at Google I/O 2026](https://www.engadget.com/2176896/everything-google-announced-io-2026-gemini-omni-spark/) — 综合最全
- [9to5google: Wear OS 7 announcement](https://9to5google.com/2026/05/19/google-announces-wear-os-7/)
- [Tom's Guide: Biggest I/O 2026 announcements](https://www.tomsguide.com/news/live/google-io-2026-live-news-updates)
- [CNBC: AI Ultra $100 + Gemini Spark](https://www.cnbc.com/2026/05/19/google-ai-ultra-gemini-spark-omni.html)
- [BusinessToday: Gemini 3.5 + Spark](https://www.businesstoday.in/amp/technology/artificial-intelligence/story/google-io-2026-google-announces-gemini-3-5-models-and-gemini-spark-ai-agent-532351-2026-05-19)
- [9to5google: Everything announced at I/O 2026](https://9to5google.com/2026/05/19/google-io-2026-news/) — 待二次 fetch
- [io.google/2026/](https://io.google/2026/) — 官方议程

---

*v0.2 · 2026-05-19 keynote 当天整理*
*v0.2 较 v0.1 变更:(1) 移除 13/14 节判定相关内容到独立 ScoringRules.md;(2) 应用外部 check 9 条事实修正;(3) 标注 Omni 输出模态两源冲突;(4) Wear OS 7 降级到"I/O 期间发布,keynote 主台简略提及"*
*评分细则见 `IO2026_ScoringRules.md`*
