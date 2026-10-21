[English](README.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [日本語](README.ja.md)

# Hi，我是 Hu Deyi 👋

## ⚓ 关于我

大连海事大学本科在读，**英语（涉外法治）专业**。

我正在尝试把 **社会研究、人工智能、治理与信息系统** 放到同一个观察框架中，并进行相关研究与开发。

目前的兴趣可以缩略为五个方向：

- ⚖️ **法社会学研究**
- 🤖 **人工智能**
- 🏛️ **治理**
- 🔍 **批判社会学**
- 🌏 **跨文化研究**

我尤其关注制度、规则、证据、技术与社会结构之间如何相互作用，以及其中哪些关系能够进一步转化为**可检索、可结构化、可验证、可复用的信息系统**。

## 研究兴趣

`法社会学研究` · `人工智能` · `治理` · `批判社会学` · `跨文化研究`

## 🌊 我正在开发什么

### [SeaFlow](https://github.com/HuDeyi-66/SeaFlow)

**SeaFlow** 是一个长期的法律 AI 与证据基础设施项目。

它探索如何把不同形式的资料转化为可靠、可追溯、机器可调用的证据，同时尽可能保留原始材料的来源、引用与证据边界。

目前的核心原则是：

> **Evidence First · Traceable Sources · Small Core · Extensible Skills**

四个公开 Skill 仓库已在批准的发布清单范围内同步；基座运行时和正式 ChenHai 实现保持私有，WenHai 仍仅在本地维护。

**工程状态：** 六个 Skill 已在经过测试的 Windows/CPython 环境下完成 **V3.5 合成证据六 Skill 集成内部验收**；**V3.6 外部基准评测尚未开始**。这不是第三方同行评议、法律正确性认证、真实语料准确率验证或生产就绪认证。

[查看 SeaFlow 架构与六 Skill 算子展示](https://hudeyi-66.github.io/seaflow-library-project-control/)。

## 🧩 SeaFlow 六个 Skill

六个 Skill 都是 SeaFlow 独立的一级模块，均有范围明确的本地实现；它们是项目自有模块，不代表兼容 Anthropic Agent Skills。源码公开状态与内部工程验收资格应分别理解。

### 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) — 法律文本证据

**核心能力：** Structure、ResolveRefs、忠实来源的文本切片及引用重建。

**证据边界：** 引用位置对应已登记的文本表示；来源标签唯一匹配并不证明法律引用目标身份或法律正确性。

**源码状态：** 公开源码仓库.

### 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) — 表格证据

**核心能力：** ReconstructVerify、AccountLoss、单元格来源定位与显式损失记录。

**证据边界：** 校验限于受支持的工作簿输入和选定证据，不声称整本工作簿完整无遗漏。

**源码状态：** 公开源码仓库.

### 🗂️ WenHai（海玟） — 文献证据

**核心能力：** RegisterAsset · PreserveTranscript · SegmentEvidence · ExtractAdvice。

**证据边界：** 保留文本片段的声明坐标与编辑衍生关系；不认证未提供的原始录音、发言人身份或建议真实性。

**源码状态：** 本地私有仓库，没有公开源码链接.

### 🔎 ChenHai（海琛） — 证据充分性与过程评估

**核心能力：** Φ 证据充分性评估、Ψ 检索及研究过程评估。

**证据边界：** 证据缺口和未知来源必须显式保留；过程评估不等于法律正确性判断。

**源码状态：** 正式实现私有；公开 ChenHai 探索仓库是独立历史原型 ([公开探索原型](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill)).

### 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — 证据关系与溯源图

**核心能力：** Γ 证据溯源图、带类型事件、断言及登记校验。

**证据边界：** 计算上的衍生关系不自动证明法律引用关系、因果关系或独立印证。

**源码状态：** 公开源码仓库.

### 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — 时间证据

**核心能力：** 时间证据状态判断、复核规划及时间证据准入。

**证据边界：** 法律生效时间未知时保持未确定；发布日期与计划日期不自动证明法律效力。

**源码状态：** 公开源码仓库.

## 🧭 我如何理解这些项目

我的很多研究和开发都可以放到这样一条链条中：

**社会现实 → 制度与规则 → 证据 → 信息系统 → 人工智能**

我同时对这条链条的两个方向感兴趣：

- 社会与制度结构如何被形式化并进入计算系统；
- 计算系统又如何反过来改变证据的生产、组织和使用。

这也是 **法社会学研究、人工智能、治理、批判社会学与跨文化研究** 五个方向发生交叉的地方。

## 🛠 代表项目

- 🌊 [SeaFlow](https://github.com/HuDeyi-66/SeaFlow) —— 项目与架构公开入口。
- 🧭 [SeaFlow 技术展示站](https://hudeyi-66.github.io/seaflow-library-project-control/) —— 六 Skill、验收范围和能力边界。
- 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) —— 法律文本、结构观察与引用候选。
- 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) —— 可核验的表格证据与显式损失记录。
- 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) —— 有范围限制的时间证据判断。
- 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) —— 证据关系与计算溯源。
- 🔎 **ChenHai（海琛）** —— 正式实现私有；[公开探索原型](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill) 为独立历史项目。
- 🗂️ **WenHai（海玟）** —— 本地私有文献证据 Skill，没有公开仓库。

## 📖 研究 × 工程

对我而言，研究与开发是一条连续的路径：

> **观察 → 理解 → 形式化 → 构建 → 重新审视**

研究帮助我识别值得关注的结构。

工程迫使这些结构变得明确。

而一个系统真正被构建出来之后，它暴露出的局限往往又会成为新的研究问题。

这里的一些 repository 是稳定工具，
一些是研究原型，
还有一些仍然只是实验。

它们共同记录着一些想法如何逐渐成为系统。

## 🌱 最近在探索

- 证据导向的 AI 系统
- 检索与溯源
- 模块化 AI Skill
- 本地与轻量模型
- 多模态研究工作流
- AI 辅助研究基础设施
- 智能系统的社会影响

## 🤖 常用 AI 模型

`GPT` · `DeepSeek` · `Kimi`

## 🧩 五个标签

**⚖️ 法社会学研究**
制度、规则、法律实践及其与社会结构之间的关系。

**🤖 人工智能**
检索、Agent、语言模型、证据系统与人机交互。

**🏛️ 治理**
制度设计、协调机制、监管以及新兴技术治理。

**🔍 批判社会学**
权力、制度、技术、社会结构，以及隐藏在看似中立系统背后的前提。

**🌏 跨文化研究**
意义、规范与制度如何在语言、法律文化与社会语境之间流动。

## 我正在探索的问题

如何让法律与社会研究真正使用 AI，同时又不让答案遮蔽其背后的证据链。
