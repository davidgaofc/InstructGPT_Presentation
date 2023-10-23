# Training Language Models to Follow Instructions with Human Feedback

#### a paper by Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Paul Christiano, Jan Leike, Ryan Lowe, and the OpenAI Alignment team
___
## Table of Contents
|Section| Description                          |
|:---|:-------------------------------------|
|[Introduction](#introduction)| Motivation and Goal of the Paper     |
|[Approach](#approach)| How the Authors Achieved Their Goal  |
|[Critical Analysis](#critical-analysis)| Analysis of the Paper                |
|[Discussion Questions](#discussion-questions)| Questions to Consider for Discussion |
|[Other Resources](#other-resources)| Related Papers, Links, Videos        |


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
![InstructGPT](images/diagram.png)

### Reward Model
The main part of RLHF starts with the second step in the diagram above. The authors use a reward model to evaluate the model's behavior. The reward model is trained to predict whether a model's behavior is helpful, honest, and harmless and is based off hired human labelers.

Labelers are given responses to a corresponding prompt and asked to rank them.
This creates the following loss function for the reward model, which is pretty much a pairwise comparison of the responses:
![Reward Model Loss Function](images/reward_loss.png)

### 






___
Results
---


___
Critical Analysis
---
- blah
- blah

___
Discussion Questions
---
### Question 1:
### Question 2:

Other Resources
---
- [Play around with InstructGPT in the OpenAI Playground*](https://platform.openai.com/playground?mode=complete)
- [InstructGPT Video with One of the Authors](https://www.youtube.com/watch?v=QGpaBWOaHQI)
- [OpenAI InstructGPT Repo with Model Card and Samples](https://github.com/openai/following-instructions-human-feedback#instructgpt-training-language-models-to-follow-instructions-with-human-feedback)
- [OpenAI Paper Summary](https://openai.com/research/instruction-following#sample1)
- [HuggingFace RLHF Blog Post](https://huggingface.co/blog/rlhf)
- [For More on PPO - from OpenAI](https://openai.com/research/openai-baselines-ppo)
- [For More on RLHF - from OpenAI](https://openai.com/research/learning-from-human-preferences)

*Note: You need to make an OpenAI account to access the Playground.
___
Citation for this Paper:\
Ouyang, L., Wu, J., Jiang, X., Almeida, D., Wainwright, C., Mishkin, P., ... & Lowe, R. (2022). _Training language models to follow instructions with human feedback_. Advances in Neural Information Processing Systems, 35, 27730-27744.
