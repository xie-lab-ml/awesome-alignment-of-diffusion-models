# Awesome Alignment of Diffusion Models

The collection of awesome papers on alignment of diffusion models. 

If you are interested in alignment of diffusion mdoels, please refer to our survery paper "[Alignment of Diffusion Models: Fundamentals, Challenges, and Future](https://arxiv.org/pdf/2409.07253)", which is the first survey on this topic to our knowledge.

We hope to enjoy the adventure of exploring alignment and diffusion models with more researchers. Corrections and suggestions are welcomed.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/zeke-xie/awesome-alignment-of-diffusion-models)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

## Alignment Techniques of Diffusion Models
### RLHF
* Aligning Text-to-Image Models using Human Feedback. arXiv:2302, [[pdf]](https://arxiv.org/pdf/2302.12192)
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2304.05977)
* DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models, NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.16381)
* Aligning Text-to-Image Diffusion Models with Reward Backpropagation. arXiv:2310, [[pdf]](https://arxiv.org/pdf/2310.03739v2)
* Directly Fine-Tuning Diffusion Models on Differentiable Rewards. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2309.17400)
* PRDP: Proximal Reward Difference Prediction for Large-Scale Reward Finetuning of Diffusion Models. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2402.08714)
* Understanding Reinforcement Learning-Based Fine-Tuning of Diffusion Models: A Tutorial and Review. arXiv:2407, [[pdf]](https://arxiv.org/pdf/2407.13734)
* Fine-Tuning of Continuous-Time Diffusion Models as Entropy-Regularized Control. arXiv:2402, [[pdf]](https://arxiv.org/pdf/2402.15194)

### DPO 
* Diffusion Model Alignment Using Direct Preference Optimization. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2311.12908)
* Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2311.13231)
* A Dense Reward View on Aligning Text-to-Image Diffusion with Preference. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08265)
* Step-aware Preference Optimization: Aligning Preference with Denoising Performance at Each Step. arXiv:2406, [[pdf]](https://arxiv.org/pdf/2406.04314)
* Aligning Diffusion Models by Optimizing Human Utility. arXiv:2404, [[pdf]](https://arxiv.org/pdf/2404.04465)
* Tuning Timestep-Distilled Diffusion Model Using Pairwise Sample Optimization. arXiv:2410, [[pdf]](https://arxiv.org/pdf/2410.03190)
* Scalable Ranked Preference Optimization for Text-to-Image Generation. arXiv:2410, [[pdf]](https://arxiv.org/pdf/2410.18013)
* Self-Play Fine-tuning of Diffusion Models for Text-to-image Generation. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2402.10210)

### Training-Free Implicit Alignment
* Improving Text-to-Image Consistency via Automatic Prompt Optimization. TMLR 2024, [[pdf]](https://arxiv.org/pdf/2403.17804)
* Optimizing Prompts for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2212.09611)
* Model-Agnostic Human Preference Inversion in Diffusion Models. arXiv:2404, [[pdf]](https://arxiv.org/pdf/2404.00879)
* RePrompt: Automatic Prompt Editing to Refine AI-Generative Art Towards Precise Expressions. CHI23, [[pdf]](https://arxiv.org/pdf/2302.09466)
* Dynamic Prompt Optimizing for Text-to-Image Generation. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2404.04095)
* Towards Better Text-to-Image Generation Alignment via Attention Modulation. arXiv:2404, [[pdf]](https://arxiv.org/pdf/2404.13899)
* Not All Noises Are Created Equally: Diffusion Noise Selection and Optimization. arXiv:2407, [[pdf]](https://arxiv.org/pdf/2407.14041)
* Derivative-Free Guidance in Continuous and Discrete Diffusion Models with Soft Value-Based Decoding. arXiv:2408, [[pdf]](https://arxiv.org/pdf/2408.08252)


### Alignment Beyond Text-to-Image Diffusion Models
* Video Diffusion Alignment via Reward Gradients. arXiv:2407, [[pdf]](https://arxiv.org/pdf/2407.08737)
* Aligning Target-Aware Molecule Diffusion Models with Exact Energy Optimization. arXiv:2407, [[pdf]](https://arxiv.org/pdf/2407.01648)
* DreamReward: Text-to-3D Generation with Human Preference. arXiv:2403, [[pdf]](https://arxiv.org/pdf/2403.14613)
* InstructVideo: Instructing Video Diffusion Models with Human Feedback. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2312.12490)
* HIVE: Harnessing Human Feedback for Instructional Visual Editing. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2303.09618)
* AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2310.02054)
* Alignment is Key for Applying Diffusion Models to Retrosynthesis. arXiv:2405, [[pdf]](https://arxiv.org/pdf/2405.17656)


## Benchmarks and Evaluation 
* Human Preference Score: Better Aligning Text-to-Image Models with Human Preference. ICCV 2023, [[pdf]](https://arxiv.org/pdf/2303.14420)
* Human Preference Score v2: A Solid Benchmark for Evaluating Human Preferences of Text-to-Image Synthesis. arXiv:2306, [[pdf]](https://arxiv.org/pdf/2306.09341)
* Pick-a-Pic: An Open Dataset of User Preferences for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.01569)
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2304.05977)
* Social Reward: Evaluating and Enhancing Generative AI through Million-User Feedback from an Online Creative Community. ICLR 2024 Spotlight, [[pdf]](https://arxiv.org/pdf/2402.09872)
* Learning Multi-Dimensional Human Preference for Text-to-Image Generation. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2405.14705)
* Rich Human Feedback for Text to Image Generation. CVPR 2024 Best Paper, [[pdf]](https://arxiv.org/pdf/2312.10240)
* Multimodal Large Language Model is a Human-Aligned Annotator for Text-to-Image Generation. arXiv:2404, [[pdf]](https://arxiv.org/pdf/2404.15100)
* DALL-Eval: Probing the Reasoning Skills and Social Biases of Text-to-Image Generative Transformers. ICCV 2023, [[pdf]](https://arxiv.org/pdf/2202.04053)
* GenEval: An Object-Focused Framework for Evaluating Text-to-Image Alignment. NeurIPS 2023 Datasets and Benchmarks, [[pdf]](https://arxiv.org/pdf/2310.11513)
* VPGen & VPEval: Visual Programming for Text-to-Image Generation and Evaluation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.15328)
* Holistic Evaluation of Text-to-Image Models. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2311.04287)
* LLMScore: Unveiling the Power of Large Language Models in Text-to-Image Synthesis Evaluation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.11116)
* Measuring Style Similarity in Diffusion Models. arXiv:2404, [[pdf]](https://arxiv.org/pdf/2404.01292)
  

## Fundamentals of Human Alignment
### Preference Modeling 
* Rank analysis of incomplete block designs: I. The method of paired comparisons. Biometrika 1952, [[pdf]](https://www.jstor.org/stable/2334029)
* Individual choice behavior. John Wiley 1959, [[pdf]](https://psycnet.apa.org/record/1960-03588-000)
* The analysis of permutations. Journal of the Royal Statistical Society. Series C (Applied Statistics) 1975, [[pdf]](https://www.jstor.org/stable/2346567)
* Learning-to-Rank with Partitioned Preference: Fast Estimation for the Plackett-Luce Model. AISTATS, [[pdf]](https://arxiv.org/pdf/2006.05067)
* Models of human preference for learning reward functions. arXiv:2206, [[pdf]](https://arxiv.org/pdf/2206.02231)
* Beyond Preferences in AI Alignment. arXiv:2408, [[pdf]](https://arxiv.org/pdf/2408.16984)

### RLHF 
* Training language models to follow instructions with human feedback. NeurIPS 2022, [[pdf]](https://arxiv.org/pdf/2203.02155)
* Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs. ACL 2024, [[pdf]](https://arxiv.org/pdf/2402.14740)
* Raft: Reward ranked finetuning for generative foundation model alignment. TMLR 2024, [[pdf]](https://arxiv.org/pdf/2304.06767)
* Rrhf: Rank responses to align language models with human feedback without tears. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2304.05302)
* Constitutional AI: Harmlessness from AI Feedback. arXiv:2212, [[pdf]](https://arxiv.org/pdf/2212.08073)
* RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2309.00267)

### DPO 
* Direct Preference Optimization: Your Language Model is Secretly a Reward Model. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.18290)
* A General Theoretical Paradigm to Understand Learning from Human Preferences. AISTATS 2024, [[pdf]](https://arxiv.org/pdf/2310.12036)
* ORPO: Monolithic Preference Optimization without Reference Model. arXiv:2403, [[pdf]](https://arxiv.org/pdf/2403.07691)
* KTO: Model Alignment as Prospect Theoretic Optimization. 	ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.01306)
* Preference Ranking Optimization for Human Alignment. AAAI 2024, [[pdf]](https://arxiv.org/pdf/2306.17492)
* Lipo: Listwise preference optimization through learning-to-rank. arXiv:2402, [[pdf]](https://arxiv.org/pdf/2402.01878)

## Potential Challenges and Opportunities of Diffusion Alignment
* Scaling laws for reward model overoptimization. ICML 2023, [[pdf]](https://arxiv.org/pdf/2210.10760)
* AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.14387)
* Stepwise Alignment for Constrained Language Model Policy Optimization. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2404.11049)
* The Alignment Problem from a Deep Learning Perspective. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2209.00626)
* Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints. ICLR 2024 Spotlight, [[pdf]](https://arxiv.org/pdf/2309.16240)
* Self-Play Preference Optimization for Language Model Alignment. arXiv:2405, [[pdf]](https://arxiv.org/pdf/2405.00675)
* SimPO: Simple Preference Optimization with a Reference-Free Reward. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2405.14734)
* What Makes Good Data for Alignment? A Comprehensive Study of Automatic Data Selection in Instruction Tuning. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2312.15685)
* Generalized Preference Optimization: A Unified Approach to Offline Alignment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05749)
* Nash Learning from Human Feedback. ICML 2024 Spotlight, [[pdf]](https://arxiv.org/pdf/2312.00886)
* Human Alignment of Large Language Models through Online Preference Optimisation. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.08635)
* Active Preference Learning for Large Language Models. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08114)
* Token-level Direct Preference Optimization. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.11999)
* Dense Reward for Free in Reinforcement Learning from Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.00782)
* Coactive Learning for Large Language Models using Implicit User Feedback. ICML 2024, [[pdf]](https://openreview.net/pdf?id=rVWsTjMW1m)
* BRAIn: Bayesian Reward-conditioned Amortized Inference for natural language generation from feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.02479)
* BOND: Aligning LLMs with Best-of-N Distillation. arXiv:2407, [[pdf]](https://arxiv.org/pdf/2407.14622)
* Self-Alignment of Large Language Models via Monopolylogue-based Social Scene Simulation. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05699)
* UltraFeedback: Boosting Language Models with Scaled AI Feedback. ICML 2024 , [[pdf]](https://arxiv.org/pdf/2310.01377)
* A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity. ICML 2024, [[pdf]](https://arxiv.org/pdf/2401.01967)
* Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.10719)
* Understanding the Learning Dynamics of Alignment with Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.18742)
* Fundamental Limitations of Alignment in Large Language Models. ICML 2024, [[pdf]](https://arxiv.org/pdf/2304.11082)
* Reward Model Learning vs. Direct Policy Optimization: A Comparative Analysis of Learning from Human Preferences. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.01857)
* Iterative Preference Learning from Human Feedback: Bridging Theory and Practice for RLHF under KL-constraint. ICML 2024, [[pdf]](https://arxiv.org/pdf/2312.11456)
* Preference Fine-Tuning of LLMs Should Leverage Suboptimal, On-Policy Data. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.14367)
* AI Alignment with Changing and Influenceable Reward Functions. ICML 2024, [[pdf]](https://arxiv.org/pdf/2405.17713)
* Rewards-in-Context: Multi-objective Alignment of Foundation Models with Dynamic Preference Adjustment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.10207)
* MaxMin-RLHF: Alignment with Diverse Human Preferences. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08925)
* Provably Robust DPO: Aligning Language Models with Noisy Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.00409)
* Visual Adversarial Examples Jailbreak Aligned Large Language Models. AAAI 2024 Oral, [[pdf]](https://arxiv.org/pdf/2306.13213)
* Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05162)
* Decoding-time Realignment of Language Models. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.02992)
* Towards Efficient Exact Optimization of Language Model Alignment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.00856)
* Linear Alignment: A Closed-form Solution for Aligning Human Preferences without Tuning and Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2401.11458)
* Feedback Efficient Online Fine-Tuning of Diffusion Models. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.16359)
* Position: A Roadmap to Pluralistic Alignment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05070)
* Position: Social Choice Should Guide AI Alignment in Dealing with Diverse Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.10271)


# Citing

If you find the paper list useful for your research, you are highly welcomed to cite our survey paper on this topic！


```
@article{liu2024alignment,
  title = {Alignment of Diffusion Models: Fundamentals, Challenges, and Future},
  author = {Liu, Buhua and Shao, Shitong and Li, Bao and Bai, Lichen, and Xu, Zhiqiang and Xiong, Haoyi and Kwok, James and Helal, Sumi and Xie, Zeke},
  journal = {arXiv preprint arXiv:2409.07253},
  year = {2024}
}
```

