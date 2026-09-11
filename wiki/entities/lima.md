---
type: entity
title: LIMA（Less Is More for Alignment）
tags: [AI模型, Meta, 对齐研究]
related: [meta, 表面对齐假说, 监督微调-sft, 后训练]
sources: ["117_预训练和后训练：你能力的上限和下限.md"]
created: 2026-09-09
updated: 2026-09-09
---

# LIMA（Less Is More for Alignment）

LIMA 是 Meta AI 提出的对齐研究项目名称（也是其训练的模型名），全称 "Less Is More for Alignment"。

## 在本课中的引用

- **核心实验**：用仅 **1,000 条精心挑选的示范数据**，对 **65B 参数基座模型**做监督微调，就调出像样的助手表现
- **意义**：以最少的 SFT 数据证明了基座模型本身已具备几乎全部所需知识——后训练只是"调出"已有能力
- 与 OpenAI InstructGPT（13 亿参数后训练胜 1750 亿 GPT-3）共同构成 [[表面对齐假说]] 的两大实证支柱

## 对应研究主张

> "对于对齐来说，几乎所有的知识都是在预训练中学会的；有限的对齐数据足以教会模型产生高质量输出。"

## 相关引用

- Meta AI 论文（2023 年发布）
- 与 [[表面对齐假说]]、[[监督微调-sft]] 直接相关