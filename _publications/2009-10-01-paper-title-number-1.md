---
title:" GPT4Battery: Cross-battery State of Health Estimation via Physical-Guided Test-time Prompt Learning with LLM"
excerpt: State of health (SOH) is a crucial indicator to evaluate the level of
  degradation of  batteries that cannot be measured directly but requires
  estimation. Accurate SOH estimation enhances detection, control, and feedback
  for Li-ion batteries, allowing for safe and efficient energy management and
  guiding the development of new-generation batteries. Despite significant
  progress in data-driven SOH estimation methods, the time- and
  resource-consuming degradation experiments to generate lifelong training data
  pose a barrier to timely safety monitoring and the development of new battery
  technologies. To tackle this problem, We propose GPT4Battery, the first
  foundation model for battery to utilize the strong generalization ability of
  the large language model (LLM) for cross-battery SOH estimation. We design a
  translator to reprogram the voltage-time battery charging data into text
  prototype representations to align data from different modalities, adapting
  the LLM to battery tasks. We also design a novel physical guided test-time
  prompt tuning (PGTPT) method to learn adaptive prompts on the fly with a
  single test sample, enhancing the model's generalization ability and fitting
  the real-world scenarios. PGTPT optimizes the prompt by guiding the LLM to
  generate a complete battery charging curve in accordance with the physics
  equations of the 1-RC ECM model of a LIB cell. The validation results
  demonstrate that the proposed model achieves state-of-the-art accuracy that is
  even on par with domain adaptation or fine-tuning methods that require
  additional training data on five widely recognized datasets collected from 65
  batteries.
collection: portfolio
date: 2024-4-17
venue: 'Arxiv, Under Review'
---
State of health (SOH) is a crucial indicator to evaluate the level of
degradation of batteries that cannot be measured directly but requires
estimation. Accurate SOH estimation enhances detection, control, and feedback
for Li-ion batteries, allowing for safe and efficient energy management and
guiding the development of new-generation batteries. Despite significant
progress in data-driven SOH estimation methods, the time- and resource-consuming
degradation experiments to generate lifelong training data pose a barrier to
timely safety monitoring and the development of new battery technologies. To
tackle this problem, We propose GPT4Battery, the first foundation model for
battery to utilize the strong generalization ability of the large language model
(LLM) for cross-battery SOH estimation. We design a translator to reprogram the
voltage-time battery charging data into text prototype representations to align
data from different modalities, adapting the LLM to battery tasks. We also
design a novel physical guided test-time prompt tuning (PGTPT) method to learn
adaptive prompts on the fly with a single test sample, enhancing the model's
generalization ability and fitting the real-world scenarios. PGTPT optimizes the
prompt by guiding the LLM to generate a complete battery charging curve in
accordance with the physics equations of the 1-RC ECM model of a LIB cell. The
validation results demonstrate that the proposed model achieves state-of-the-art
accuracy that is even on par with domain adaptation or fine-tuning methods that
require additional training data on five widely recognized datasets collected
from 65 batteries.
