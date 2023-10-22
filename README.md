# Training Language Models to Follow Instructions with Human Feedback

#### a paper by Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Paul Christiano, Jan Leike, Ryan Lowe, and the OpenAI Alignment team
___
## Table of Contents
|Section| Description                  |
|:---|:-----------------------------|
|[Introduction](#introduction)| Motivation and Goal of the Paper |
|[Other Resources](#other-resources)| Related Papers, Links, Videos|


___

Introduction
---
### Motivation
Large language models like GPT-3 are adaptable to many downstream tasks via prompting, but can exhibit unintended behaviors when deployed, such as toxicity, bias, and misinformation. This happens because their objective of predicting the next token does not align with objectives like being **helpful, honest, and harmless**.

### Goal
The authors aim to address this mismatch and improve the alignment of large language models with human intentions. Their goal is to modify model behavior to be more helpful, truthful, and harmless when following instructions. This is an important step towards safer deployment of capable language models.

___

Approach
---
![InstructGPT](diagram.png)







Other Resources
---
- [Play around with InstructGPT in the OpenAI Playground*](https://platform.openai.com/playground?mode=complete)
- [InstructGPT Video with One of the Authors](https://www.youtube.com/watch?v=QGpaBWOaHQI)
- [OpenAI InstructGPT Repo with Model Card and Samples](https://github.com/openai/following-instructions-human-feedback#instructgpt-training-language-models-to-follow-instructions-with-human-feedback)
- [OpenAI Paper Summary](https://openai.com/research/instruction-following#sample1)
- [HuggingFace RLHF Blog Post](https://huggingface.co/blog/rlhf)
- [For More on PPO - from OpenAI](https://openai.com/research/openai-baselines-ppo)
- 

*Note: You need to make an OpenAI account to access the Playground. If you don't want to make an account, you can watch the video to see how InstructGPT works.
___
Citation for this Paper:\
Ouyang, L., Wu, J., Jiang, X., Almeida, D., Wainwright, C., Mishkin, P., ... & Lowe, R. (2022). _Training language models to follow instructions with human feedback_. Advances in Neural Information Processing Systems, 35, 27730-27744.
