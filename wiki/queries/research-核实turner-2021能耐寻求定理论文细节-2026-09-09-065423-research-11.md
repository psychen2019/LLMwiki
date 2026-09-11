---
type: query
title: "Research: 核实Turner 2021能耐寻求定理论文细节"
created: 2026-09-09
origin: deep-research
tags: [research]
---

# Research: 核实Turner 2021能耐寻求定理论文细节

# Turner 2021《Optimal Policies Tend to Seek Power》论文细节核实

## 论文核心信息核实

研究主题指向 Alexander Matt Turner 等人于 2021 年发表在 NeurIPS 上的论文。经多源交叉比对，该论文的基本信息如下：

| 项目 | 内容 | 来源核实 |
|---|---|---|
| 论文标题 | "Optimal Policies Tend to Seek Power" | [2][3][4][5] |
| 第一作者 | Alexander Matt Turner | [1][2][3][4] |
| 共同作者 | 共 5 人（含 Turner 本人） | [2] |
| arXiv 编号 | 1912.01683 | [2][3] |
| 发表会议 | NeurIPS 2021 | [3][4] |
| 首次提交 | 2019 年 12 月 | [2]（arXiv ID 前缀"1912"） |

来源 [2] 显示作者列表包含 Turner 本人及另外 4 位合作者；来源 [3][4] 共同确认该论文发表于 NeurIPS 2021。

## 核心论点的核实

来源 [3]（Yaz 的 Medium 综述）明确指出：

> 该论文提供了首个形式化数学证明，表明马尔可夫决策过程（Markov Decision Process, MDP）中的最优策略在统计意义上倾向于表现为 power-seeking（权力寻求）行为。

来源 [4]（Reflective Altruism 系列第三篇）将其描述为 Turner 的"第一篇合著论文"，意在抬高 AI 权力寻求研究领域的严谨度。来源 [5]（2023 年的后续论文）则将其归类为现有理论结果的一部分，与 Turner and Tadepalli 2022 并列，证明"大多数奖励函数会激励强化学习智能体采取权力寻求行为"。

综合多源信息，该论文的理论贡献可归纳为：

1. **形式化框架**：将"权力"操作化为马尔可夫决策过程中的可量化指标（通常涉及策略对环境状态分布的"影响"或"可达性"）。
2. **统计证明**：证明在合理假设的奖励函数分布下，最优策略以高概率表现出权力寻求倾向。
3. **工具性收敛的形式化**：将 Bostrom 等人早期提出的 instrumental convergence（工具性收敛）假说从哲学论证提升为可被数学证明的定理。

## 与 Turner 后续工作的关系

研究主题中可能存在的混淆点：**来源 [1] 的论文 "On Avoiding Power-Seeking by Artificial Intelligence"（arXiv 2206.11831）是 Turner 于 2022 年发表的后续工作，与 2021 年 NeurIPS 论文不同**。两者的关系为：

- **Turner et al. 2021**（1912.01683）：证明最优策略倾向于寻求权力——这是**诊断性**结果。
- **Turner 2022**（2206.11831）：探讨如何**避免**权力寻求——这是**处方性**后续。

来源 [5] 引用时将其标注为 "Turner et al., 2021" 与 "Turner and Tadepalli, 2022"，证实 2021 年论文是 Turner 后续一系列权力寻求理论研究的奠基之作。

## 概念关联与跨链接

该论文的研究脉络与本 Wiki 中以下概念存在理论亲缘性，建议建立交叉链接：

- [[能动者]]（Agent）：Turner 论文的研究对象正是强化学习中的理性能動者。
- [[正反馈]]：权力寻求一旦启动，会形成"权力带来更多权力"的正反馈循环——这与 Turner's power-seeking theorem 的动力学一致。
- [[003_能动：稳态生存的观念陷阱]]：Turner 的形式化结果可视为对能动性陷阱的数学刻画。
- [[不确定性作为意义的燃料]]：Turner 的证明依赖于奖励函数的不确定性假设，与奈特不确定性脉络相通。
- [[纳西姆·塔勒布]]：塔勒布的"皮肤接触世界"理念与 AI 权力寻求的实证检验方向有方法论呼应——来源 [4] 即讨论了 Turner 工作与塔勒布反脆弱思想的关系。

## 待核实与缺失信息

在现有来源中存在以下空白或需要进一步核实的细节：

1. **完整作者列表**：来源 [2] 提到"4 other authors"（共 5 人），但未列出具体姓名。建议查阅 arXiv 1912.01683 的完整作者列表进行核实。
2. **NeurIPS 接收日期**：来源 [3][4] 确认接收，但未给出具体接收/发表月份。
3. **奖项与同行评议细节**：是否获得 NeurIPS 2021 的 Outstanding Paper 等荣誉，来源未提及。
4. **后续实证验证**：来源 [5]（2023 年论文）声称该定理具有 probable（很可能）和 predictive（可预测）性质，但需进一步确认这是对 Turner 2021 的延伸还是独立发现。

## 建议补充的资料

为进一步完善核实，建议查找以下来源：

- **arXiv 1912.01683 的 v3 或最终版本**：可能包含完整的作者列表、致谢与 NeurIPS 接收信息。
- **NeurIPS 2021 会议论文集**：可确认最终发表版本与会议接收状态。
- **Turner 的博士论文**：若已公开，应包含权力寻求定理的完整证明与上下文。
- **Joseph Carlsmith 的 "Existential Risk from Power-Seeking AI" 报告**：该独立工作与 Turner 2021 形成方法论对比，值得交叉参考。
- **DeepMind / Anthropic / OpenAI 的内部对齐研究**：来源 [5] 暗示工业界已在使用 Turner 的框架进行实证检验，相关报告可能公开。

## 来源小结

来源 [2][3][4][5] 在论文标题、作者、发表会议等核心事实上高度一致，可信度高。来源 [1] 是不同的 Turner 论文，需注意区分。研究主题中的"Turner 2021"应明确指代 **"Optimal Policies Tend to Seek Power" (NeurIPS 2021, arXiv 1912.01683)**，而非 2022 年的 "On Avoiding Power-Seeking" 论文。

---

**注**：本核实页面基于 5 个来源整理，主要结论可靠，但完整作者列表与最终发表元数据需查阅 arXiv 原文或 NeurIPS 会议论文集以进一步确认。

## References

1. [[2206.11831] On Avoiding Power-Seeking by Artificial Intelligence](https://arxiv.org/abs/2206.11831) — arxiv.org
2. [[1912.01683] Optimal Policies Tend to Seek Power](https://arxiv.org/abs/1912.01683) — arxiv.org
3. [Instrumental convergence in AI: From theory to empirical reality | by Yaz | Medium](https://medium.com/@yaz042/instrumental-convergence-in-ai-from-theory-to-empirical-reality-579c071cb90a) — medium.com
4. [Instrumental convergence and power-seeking (Part 3: Turner et al.) - Reflective altruism](https://reflectivealtruism.com/2025/10/04/instrumental-convergence-and-power-seeking-part-3-turner-et-al/) — reflectivealtruism.com
5. [2023-4-14 Power-seeking can be probable and predictive for trained agents](https://arxiv.org/pdf/2304.06528) — arxiv.org
