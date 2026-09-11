---
type: query
title: "Research: \"一人公司 + AI 智能体年入千万\"的可验证证据链"
created: 2026-09-09
origin: deep-research
tags: [research]
---

# Research: "一人公司 + AI 智能体年入千万"的可验证证据链

# "一人公司 + AI 智能体年入千万"的可验证证据链：以 Pieter Levels 为典型案例

## 1. 命题边界

"一人公司 + AI 智能体年入千万"是中文互联网近年流行的财富叙事模板，其核心主张为：一个自然人在不雇人的前提下，仅依靠软件与 AI 工具，即可达成年营收千万人民币（或等值美元）量级的业务。该命题的强度高度依赖个别"标杆案例"——其中被引用最频繁的就是 Pieter Levels（网名 @levelsio）。本文以可获取的公开来源构建证据链，并标注其中的不一致与缺口。

## 2. 标杆案例：Pieter Levels 的产品矩阵

根据多个二手来源整理，Pieter Levels 在不雇人的前提下长期运营以下三款核心产品 [2][4]：

- **Nomad List**：面向数字游民的全球城市排名与社区平台，是其最早的产品，已迭代至 5.0 [1]。
- **Remote OK**：远程职位招聘板，从一张 Google Spreadsheet 起步 [5]。
- **Photo AI**：AI 图像生成服务（本次研究语料未直接覆盖具体收入数字，但 [4] 将其列为 Pieter 三大主业之一）。

这三款产品的共同特征是：单人或极小团队、自托管、低运营成本、高毛利订阅 / 雇主付费收入。

## 3. 营收数据：多来源对照与内部矛盾

下表汇总各来源给出的关键数字：

| 来源 | 标的 | 报告数字 | 时点 / 语境 |
|------|------|----------|-------------|
| [1] levels.io | Nomad List | $20k–$40k/月，约 $300k/年 | Nomad List 5.0 推出时点（早期） |
| [2] softwaregrowth.io | Nomad List | $3M ARR | 长期累计增长后 |
| [3] getlatka.com | Nomad List | 标题写 $5.3M ARR、$2.1M 估值；正文又写 $650K 营收 | 2024 |
| [4] fast-saas.com | 整体组合（Nomad List + Photo AI + Remote OK） | $3M/年 | 长期披露 |
| [5] reddit r/SaaS | Remote OK | $3.6M/年 | 单独披露 |

需要明确标注的**内部矛盾与缺口**：

1. **同一指标、同年口径不一致**：来源 [3] 在同一页面中，标题声称"$5.3M ARR"，正文却写"$650K revenue"。ARR 与年度营收差一个数量级，且与 [2]、[4] 提供的 $3M 量级对不上，存在数字搬运或单位混淆嫌疑。
2. **产品口径不一致**：来源 [4] 的 $3M/年是"组合"口径，来源 [5] 的 $3.6M/年仅是 Remote OK 单产品口径。若简单加总，理论年化数字可能远高于任何一个单独披露的数字，但**没有任何来源给出经审计的总收入证明**。
3. **AI 智能体收入未被单独披露**：在五份来源中，没有任何一份将"由 AI 智能体驱动的收入"作为独立指标呈现。Photo AI 虽属 AI 产品，但 [1]–[5] 均未说明其营收占比或 AI 自动化对总收入的贡献度。
4. **"年入千万（美元 vs 人民币）"未对齐**：中文叙事中的"千万"通常指人民币（约 $140 万）。若按 [4] 的 $3M/年（≈ ¥2200 万）口径，确实越过千万门槛；若按 [1] 的 $300k/年（≈ ¥220 万），则未达"千万人民币"。叙事模板在转化货币单位时常被有意或无意地省略。

## 4. 方法论特征：Speed、Simplicity、Independence

来源 [2] 把 Pieter Levels 的成功归因于三条核心原则：**Speed（速度）、Simplicity（简洁）、Independence（独立）**。其内涵与本知识库中的若干既有概念可以对应：

- **不稀释股权、不雇人**：对应 [[自我约束|自我约束]] 的极端形态——主动放弃规模扩张的诱惑，以换取利润与决策自由度。
- **单产品小闭环**：与 [[闭环控制|闭环控制]] 一致——从产品、客服到营销全部由单人形成反馈回路，省去组织内的[[快回路挤压慢回路|快回路挤压慢回路]]问题。
- **平台化业务结构**：Nomad List 与 Remote OK 均为典型的[[平台商业模式|平台商业模式]]，并自带[[数据飞轮|数据飞轮]]——用户越多，排名 / 匹配质量越好，进而吸引更多用户。
- **使命窄、输入宽**：[[使命要窄输入要宽|使命要窄、输入要宽]] 在 Pieter 身上表现为"专注做几个工具型产品"，但产品方向的输入来自全球数字游民社区的开放反馈。

值得指出的是，这套方法论**不依赖 AI 智能体**——其本质仍是 SaaS 时代的单人开发者红利。AI 在 Pieter 的产品组合中更多是"新增产品线"（Photo AI）而非"替代人力"的杠杆。这一点对于评估原命题至关重要。

## 5. 证据链强度评估

将上述证据按可信度分层：

- **强证据（自述）**：来源 [1] 是 Pieter 自己官网博客，属于一手自述；来源 [5] 是社区报道，被 Pieter 本人在多处引用过。
- **中证据（行业媒体）**：来源 [2]、[4] 是专门追踪独立开发者与 SaaS 增长的博客，倾向于引用自述数字，**未经独立审计**。
- **弱证据 / 高风险**：来源 [3] 内部数据自相矛盾，且 getlatka.com 主要靠创始人自报数据，**公信力弱于 SEC 文件或银行流水**。

**总体判断**：Pieter Levels 的"一人公司年收入数百万美元"叙事在中文互联网被广泛接受，但**没有任何来源能构成经独立第三方审计的证据链**。所有数字均来自本人披露或转述，且数字之间存在量级差异。

## 6. 关键缺口与建议补充的资料

要真正验证"一人公司 + AI 智能体年入千万"这一命题，以下资料仍需补充：

1. **税务 / 公司注册文件**：Pieter Levels 在荷兰注册的个体公司（eenmanszaak）是否公开年报？荷兰税务局（Belastingdienst）公示的公司财报可作为硬证据。
2. **支付平台收入分账数据**：Stripe、PayPal 等支付商不会公开个体商户的 GMV，但 Pieter 多次在直播中展示过自己的 Stripe Dashboard 截图——这些截图的原始画面或第三方抓取可作为佐证。
3. **AI 智能体的收入占比**：需要找到将 Photo AI 单独披露收入数字的来源（例如 Pieter 的公开财务报表或独立报道）。
4. **其他同类标杆**：除 Pieter 外，是否存在多个**经过第三方验证**的"AI 智能体 + 一人公司"年入千万案例？中文圈常被引用的"AI 播客"、"AI 写代码"等案例，几乎都没有可审计的数字。建议寻找 Stripe Atlas、Mercury Bank 等提供的公开案例研究。
5. **失败率与生存偏差**：成功案例被放大，失败案例被忽略。建议参考 [[均值与重尾|均值与重尾]] 框架——一人公司模式可能呈重尾分布，少数头部案例拉动整体叙事，但中位数年收入可能远低于"千万"门槛。

## 7. 小结

"一人公司 + AI 智能体年入千万"在 2024–2026 年的中文语境中是一个**强叙事、弱证据**的命题。以 Pieter Levels 为最常被引用的标杆，其年收入在 $300k 至 $3.6M 之间的多个数字均可见，但**口径不一致、未经审计、AI 智能体的贡献度未独立披露**三点构成主要证据缺口。该命题作为"可能性叙事"可以成立，但作为"可复制度"则缺乏支撑。

---

**附：来源链接**

- [1] https://levels.io
- [2] https://softwaregrowth.io
- [3] https://getlatka.com
- [4] https://fast-saas.com
- [5] https://reddit.com/r/SaaS

## References

1. [Nomad List Founder — @levelsio (Pieter Levels)](https://levels.io/nomad-list-founder) — levels.io
2. [How Pieter Levels grew Nomad List to $3 million ARR - Software Growth](https://www.softwaregrowth.io/blog/how-pieter-levels-grew-nomad-list) — softwaregrowth.io
3. [Nomad List Revenue 2024: $5.3M ARR, $2.1M Valuation](https://getlatka.com/companies/nomad-list) — getlatka.com
4. [How Pieter Levels Built a $3M/Year Business with Zero Employees - FastSaaS Blog](https://www.fast-saas.com/blog/pieter-levels-success-story/) — fast-saas.com
5. [r/SaaS on Reddit: How did this guy turn a Google Spreadsheet into $3.6M/year (and is still the only employee)](https://www.reddit.com/r/SaaS/comments/1mtlfo0/how_did_this_guy_turn_a_google_spreadsheet_into/) — reddit.com
