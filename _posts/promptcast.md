---
layout: post
title: PromptCast: A New Prompt-based Learning Paradigm for Time Series Forecasting
date: 2024-05-19 00:13:10
description: 
tags: note
categories: fsc-note
tabs: true
---

# PromptCast: A New Prompt-based Learning Paradigm for Time Series Forecasting

![PromptCast 模型架构图](/assets/img/pic/promptcast/structure.jpg)


这篇方法太平凡了，简单说下：

## 研究概述
这篇论文发表于2022年，尝试首次将语言模型（LM）应用于时间序列（TS）预测任务。尽管方法本身相对基础，但这标志着在该领域的一次新的尝试。

## 主要方法
作者采用了一个直接而简单的策略来实施这一新的学习范式。核心方法包括：

- **Prompt设计**：通过简单的设计修改，将时间序列数据以适合语言模型处理的方式呈现。
- **直接询问**：类似于提问式学习，直接向模型询问未来的时间序列预测，而不进行复杂的转换或额外的预处理步骤。

![PromptCast 方法示意图](/assets/img/pic/promptcast/prompt.jpg)

这种方法的简便性为时间序列预测领域提供了一种全新的途径，虽然它的技术深度和创新性可能不如其他更复杂的方法，但在简化流程和直接性方面具有其独特的价值。

## 结论
尽管“PromptCast”的方法可能看起来较为平凡，但它开创了利用语言模型进行时间序列预测的新领域，为后续的研究提供了基础。

