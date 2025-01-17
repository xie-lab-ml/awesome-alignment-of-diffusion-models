# Awesome Alignment of Diffusion Models

The collection of awesome papers on the alignment of diffusion models. 

If you are interested in the alignment of diffusion models, please refer to our survey paper "[Alignment of Diffusion Models: Fundamentals, Challenges, and Future](https://arxiv.org/pdf/2409.07253)", which is the first survey on this topic to our knowledge.

We hope to enjoy the adventure of exploring alignment and diffusion models with more researchers. Corrections and suggestions are welcomed.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/zeke-xie/awesome-alignment-of-diffusion-models)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

## Alignment Techniques of Diffusion Models
### RLHF/RLAIF
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2304.05977)
* DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models, NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.16381)
* Aligning Text-to-Image Models using Human Feedback. arXiv 2023, [[pdf]](https://arxiv.org/pdf/2302.12192)
* Aligning Text-to-Image Diffusion Models with Reward Backpropagation. arXiv 2023, [[pdf]](https://arxiv.org/pdf/2310.03739v2)
* Directly Fine-Tuning Diffusion Models on Differentiable Rewards. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2309.17400)
* PRDP: Proximal Reward Difference Prediction for Large-Scale Reward Finetuning of Diffusion Models. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2402.08714)
* Feedback Efficient Online Fine-Tuning of Diffusion Models. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.16359)
* Fine-Tuning of Continuous-Time Diffusion Models as Entropy-Regularized Control. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2402.15194)
* Understanding Reinforcement Learning-Based Fine-Tuning of Diffusion Models: A Tutorial and Review. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.13734)
* Aligning Few-Step Diffusion Models with Dense Reward Difference Learning. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.11727)

### DPO 
* Diffusion Model Alignment Using Direct Preference Optimization. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2311.12908)
* Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2311.13231)
* A Dense Reward View on Aligning Text-to-Image Diffusion with Preference. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08265)
* Self-Play Fine-tuning of Diffusion Models for Text-to-image Generation. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2402.10210)
* Aligning Diffusion Models by Optimizing Human Utility. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2404.04465)
* Aesthetic Post-Training Diffusion Models from Generic Preferences with Step-by-step Preference Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2406.04314)
* Tuning Timestep-Distilled Diffusion Model Using Pairwise Sample Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2410.03190)
* Scalable Ranked Preference Optimization for Text-to-Image Generation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2410.18013)
* Prioritize Denoising Steps on Diffusion Model Preference Alignment via Explicit Denoised Distribution Estimation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.14871)
* SafetyDPO: Scalable Safety Alignment for Text-to-Image Generation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.10493)


### Training-Free Implicit Alignment
* Optimizing Prompts for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2212.09611)
* RePrompt: Automatic Prompt Editing to Refine AI-Generative Art Towards Precise Expressions. CHI 2023, [[pdf]](https://arxiv.org/pdf/2302.09466)
* Improving Text-to-Image Consistency via Automatic Prompt Optimization. TMLR 2024, [[pdf]](https://arxiv.org/pdf/2403.17804)
* Dynamic Prompt Optimizing for Text-to-Image Generation. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2404.04095)
* ReNO: Enhancing One-step Text-to-Image Models through Reward-based Noise Optimization. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2406.04312)
* Towards Better Text-to-Image Generation Alignment via Attention Modulation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2404.13899)
* Inference-Time Alignment of Diffusion Models with Direct Noise Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2405.18881)
* Not All Noises Are Created Equally: Diffusion Noise Selection and Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.14041)
* Derivative-Free Guidance in Continuous and Discrete Diffusion Models with Soft Value-Based Decoding. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2408.08252)
* Golden Noise for Diffusion Models: A Learning Framework. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.09502)
* DyMO: Training-Free Diffusion Model Alignment with Dynamic Multi-Objective Scheduling. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.00759)
* Zigzag Diffusion Sampling: Diffusion Models Can Self-Improve via Self-Reflection. arXiv 2024, [[pdf]](https://arxiv.org/abs/2412.10891)
* Alignment without Over-optimization: Training-Free Solution for Diffusion Models. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2501.05803)
* A General Framework for Inference-time Scaling and Steering of Diffusion Models. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2501.06848)


### Alignment Beyond Text-to-Image Diffusion Models
* Aligning Optimization Trajectories with Diffusion Models for Constrained Design Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.18470)
* AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2310.02054)
* HIVE: Harnessing Human Feedback for Instructional Visual Editing. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2303.09618)
* InstructVideo: Instructing Video Diffusion Models with Human Feedback. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2312.12490)
* DreamReward: Text-to-3D Generation with Human Preference. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2403.14613)
* Alignment is Key for Applying Diffusion Models to Retrosynthesis. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2405.17656)
* Video Diffusion Alignment via Reward Gradients. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.08737)
* Aligning Target-Aware Molecule Diffusion Models with Exact Energy Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.01648)
* VideoRepair: Improving Text-to-Video Generation via Misalignment Evaluation and Localized Refinement. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.15115)
* LiFT: Leveraging Human Feedback for Text-to-Video Model Alignment. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.04814)
* VideoDPO: Omni-Preference Alignment for Video Diffusion Generation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.14167)



## Benchmarks and Evaluation 
* DALL-Eval: Probing the Reasoning Skills and Social Biases of Text-to-Image Generative Transformers. ICCV 2023, [[pdf]](https://arxiv.org/pdf/2202.04053)
* Human Preference Score: Better Aligning Text-to-Image Models with Human Preference. ICCV 2023, [[pdf]](https://arxiv.org/pdf/2303.14420)
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2304.05977)
* Pick-a-Pic: An Open Dataset of User Preferences for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.01569)
* LLMScore: Unveiling the Power of Large Language Models in Text-to-Image Synthesis Evaluation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.11116)
* VPGen & VPEval: Visual Programming for Text-to-Image Generation and Evaluation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.15328)
* Human Preference Score v2: A Solid Benchmark for Evaluating Human Preferences of Text-to-Image Synthesis. arXiv 2023, [[pdf]](https://arxiv.org/pdf/2306.09341)
* GenEval: An Object-Focused Framework for Evaluating Text-to-Image Alignment. NeurIPS 2023 Datasets and Benchmarks, [[pdf]](https://arxiv.org/pdf/2310.11513)
* Holistic Evaluation of Text-to-Image Models. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2311.04287)
* Social Reward: Evaluating and Enhancing Generative AI through Million-User Feedback from an Online Creative Community. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2402.09872)
* Rich Human Feedback for Text to Image Generation. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2312.10240)
* Learning Multi-Dimensional Human Preference for Text-to-Image Generation. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2405.14705)
* Multimodal Large Language Models Make Text-to-Image Generative Models Align Better. NeurIPS 2024, [[pdf]](https://openreview.net/pdf?id=IRXyPm9IPW)
* Measuring Style Similarity in Diffusion Models. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2404.01292)

  

## Fundamentals of Human Alignment
### Preference Modeling 
* Rank Analysis of Incomplete Block Designs: I. The Method of Paired Comparisons. Biometrika 1952, [[pdf]](https://www.jstor.org/stable/2334029)
* Individual Choice Behavior. John Wiley 1959, [[pdf]](https://psycnet.apa.org/record/1960-03588-000)
* The Analysis of Permutations. Journal of the Royal Statistical Society. Series C (Applied Statistics) 1975, [[pdf]](https://www.jstor.org/stable/2346567)
* Learning-to-Rank with Partitioned Preference: Fast Estimation for the Plackett-Luce Model. AISTATS 2021, [[pdf]](https://arxiv.org/pdf/2006.05067)
* Models of Human Preference for Learning Reward Functions. arXiv 2022, [[pdf]](https://arxiv.org/pdf/2206.02231)
* Beyond Preferences in AI Alignment. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2408.16984)

### RLHF 
* Training Language Models to Follow Instructions with Human Feedback. NeurIPS 2022, [[pdf]](https://arxiv.org/pdf/2203.02155)
* Constitutional AI: Harmlessness from AI Feedback. arXiv 2022, [[pdf]](https://arxiv.org/pdf/2212.08073)
* RRHF: Rank Responses to Align Language Models with Human Feedback without Tears. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2304.05302)
* RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment. TMLR 2024, [[pdf]](https://arxiv.org/pdf/2304.06767)
* RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2309.00267)
* Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs. ACL 2024, [[pdf]](https://arxiv.org/pdf/2402.14740)

### DPO 
* Direct Preference Optimization: Your Language Model is Secretly a Reward Model. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.18290)
* Preference Ranking Optimization for Human Alignment. AAAI 2024, [[pdf]](https://arxiv.org/pdf/2306.17492)
* A General Theoretical Paradigm to Understand Learning from Human Preferences. AISTATS 2024, [[pdf]](https://arxiv.org/pdf/2310.12036)
* KTO: Model Alignment as Prospect Theoretic Optimization. 	ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.01306)
* LiPO: Listwise Preference Optimization through Learning-to-Rank. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2402.01878)
* ORPO: Monolithic Preference Optimization without Reference Model. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2403.07691)
* DPO Kernels: A Semantically-Aware, Kernel-Enhanced, and Divergence-Rich Paradigm for Direct Preference Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2501.03271)

## Potential Challenges and Opportunities of Diffusion Alignment
* Scaling Laws for Reward Model Overoptimization. ICML 2023, [[pdf]](https://arxiv.org/pdf/2210.10760)
* The Alignment Problem from a Deep Learning Perspective. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2209.00626)
* Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2309.16240)
* Nash Learning from Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2312.00886)
* Iterative Preference Learning from Human Feedback: Bridging Theory and Practice for RLHF under KL-constraint. ICML 2024, [[pdf]](https://arxiv.org/pdf/2312.11456)
* Dense Reward for Free in Reinforcement Learning from Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.00782)
* Position: A Roadmap to Pluralistic Alignment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05070)
* Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05162)
* Confronting Reward Overoptimization for Diffusion Models: A Perspective of Inductive and Primacy Biases. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08552)
* MaxMin-RLHF: Alignment with Diverse Human Preferences. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08925)
* Rewards-in-Context: Multi-objective Alignment of Foundation Models with Dynamic Preference Adjustment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.10207)
* Reward Model Learning vs. Direct Policy Optimization: A Comparative Analysis of Learning from Human Preferences. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.01857)
* Generalized Preference Optimization: A Unified Approach to Offline Alignment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05749)
* Human Alignment of Large Language Models through Online Preference Optimisation. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.08635)
* Understanding the Learning Dynamics of Alignment with Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.18742)
* Position: Social Choice Should Guide AI Alignment in Dealing with Diverse Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.10271)
* Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.10719)
* BOND: Aligning LLMs with Best-of-N Distillation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.14622)
* Does RLHF Scale? Exploring the Impacts From Data, Model, and Method. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.06000)


# Citing

If you find the paper list useful for your research, you are highly welcome to cite our survey paper on this topic！


```
@article{liu2024alignment,
  title = {Alignment of Diffusion Models: Fundamentals, Challenges, and Future},
  author = {Liu, Buhua and Shao, Shitong and Li, Bao and Bai, Lichen, and Xu, Zhiqiang and Xiong, Haoyi and Kwok, James and Helal, Sumi and Xie, Zeke},
  journal = {arXiv preprint arXiv 2024.07253},
  year = {2024}
}
```

