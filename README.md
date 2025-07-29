# Awesome Alignment of Diffusion Models

The collection of awesome papers on the alignment of diffusion models. 

If you are interested in the alignment of diffusion models, please refer to our survey paper "[Alignment of Diffusion Models: Fundamentals, Challenges, and Future](https://arxiv.org/pdf/2409.07253)", which is the first survey on this topic to our knowledge.

We hope to enjoy the adventure of exploring alignment and diffusion models with more researchers. 

We try to include recent papers in time, which will be soon added in future revision of our survey paper. Corrections and suggestions are welcomed.

[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/zeke-xie/awesome-alignment-of-diffusion-models)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Alignment Techniques of Diffusion Models
### RLHF/RLAIF
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2304.05977)
* DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models, NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2305.16381)
* Aligning Text-to-Image Models using Human Feedback. arXiv 2023, [[pdf]](https://arxiv.org/pdf/2302.12192)
* Aligning Text-to-Image Diffusion Models with Reward Backpropagation. arXiv 2023, [[pdf]](https://arxiv.org/pdf/2310.03739v2)
* Training Diffusion Models with Reinforcement Learning. ICLR 2024, [[pdf]](https://arxiv.org/abs/2305.13301)
* Directly Fine-Tuning Diffusion Models on Differentiable Rewards. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2309.17400)
* CoMat: Aligning Text-to-Image Diffusion Model with Image-to-Text Concept Matching. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2404.03653)
* PRDP: Proximal Reward Difference Prediction for Large-Scale Reward Finetuning of Diffusion Models. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2402.08714)
* Confronting Reward Overoptimization for Diffusion Models: A Perspective of Inductive and Primacy Biases. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08552)
* Feedback Efficient Online Fine-Tuning of Diffusion Models. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.16359)
* Deep Reward Supervisions for Tuning Text-to-Image Diffusion Models. ECCV 2024, [[pdf]](https://arxiv.org/abs/2405.00760)
* Fine-Tuning of Continuous-Time Diffusion Models as Entropy-Regularized Control. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2402.15194)
* Understanding Reinforcement Learning-Based Fine-Tuning of Diffusion Models: A Tutorial and Review. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.13734)
* Aligning Few-Step Diffusion Models with Dense Reward Difference Learning. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.11727)
* Reward Fine-Tuning Two-Step Diffusion Models via Learning Differentiable Latent-Space Surrogate Reward. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.15247)
* Information Theoretic Text-to-Image Alignment. ICLR 2025, [[pdf]](https://arxiv.org/pdf/2405.20759)
* Improving Long-Text Alignment for Text-to-Image Diffusion Models. ICLR 2025, [[pdf]](https://arxiv.org/pdf/2410.11817)
* Efficient Diversity-Preserving Diffusion Alignment via Gradient-Informed GFlowNets. ICLR 2025, [[pdf]](https://arxiv.org/pdf/2412.07775)
* Towards Better Alignment: Training Diffusion Models with Reinforcement Learning Against Sparse Rewards. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2501.06655)
* Focus-N-Fix: Region-Aware Fine-Tuning for Text-to-Image Generation. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2501.06481)
* Diffusion Model as a Noise-Aware Latent Reward Model for Step-Level Preference Optimization. arXiv 2025, [[pdf]](https://arxiv.org/abs/2502.01051)
* ADT: Tuning Diffusion Models with Adversarial Supervision. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2504.11423)

### DPO 
* Diffusion Model Alignment Using Direct Preference Optimization. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2311.12908)
* Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2311.13231)
* A Dense Reward View on Aligning Text-to-Image Diffusion with Preference. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08265)
* Self-Play Fine-tuning of Diffusion Models for Text-to-image Generation. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2402.10210)
* Aligning Diffusion Models by Optimizing Human Utility. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2404.04465)
* Tuning Timestep-Distilled Diffusion Model Using Pairwise Sample Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2410.03190)
* Scalable Ranked Preference Optimization for Text-to-Image Generation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2410.18013)
* Prioritize Denoising Steps on Diffusion Model Preference Alignment via Explicit Denoised Distribution Estimation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.14871)
* PatchDPO: Patch-level DPO for Finetuning-free Personalized Image Generation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.03177)
* SafetyDPO: Scalable Safety Alignment for Text-to-Image Generation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.10493)
* Margin-aware Preference Optimization for Aligning Diffusion Models without Reference. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2406.06424)
* DSPO: Direct Score Preference Optimization for Diffusion Model Alignment. ICLR 2025, [[pdf]](https://openreview.net/forum?id=xyfb9HHvMe)
* Direct Distributional Optimization for Provable Alignment of Diffusion Models. ICLR 2025, [[pdf]](https://arxiv.org/pdf/2502.02954)
* Boost Your Human Image Generation Model via Direct Preference Optimization. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2405.20216)
* Curriculum Direct Preference Optimization for Diffusion and Consistency Models. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2405.13637)
* Aesthetic Post-Training Diffusion Models from Generic Preferences with Step-by-step Preference Optimization. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2406.04314)
* Personalized Preference Fine-tuning of Diffusion Models. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2501.06655)
* Calibrated Multi-Preference Optimization for Aligning Diffusion Models. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2502.02588)
* InPO: Inversion Preference Optimization with Reparametrized DDIM for Efficient Diffusion Model Alignment. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2503.18454)
* CHATS: Combining Human-Aligned Optimization and Test-Time Sampling for Text-to-Image Generation. ICML 2025, [[pdf]](https://arxiv.org/pdf/2502.12579)
* D-Fusion: Direct Preference Optimization for Aligning Diffusion Models with Visually Consistent Samples. ICML 2025, [[pdf]](https://arxiv.org/abs/2505.22002)
* Smoothed Preference Optimization via ReNoise Inversion for Aligning Diffusion Models with Varied Human Preferences. ICML 2025, [[pdf]](https://arxiv.org/abs/2506.02698)
* Refining Alignment Framework for Diffusion Models with Intermediate-Step Preference Ranking. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2502.01667)
* Aligning Text to Image in Diffusion Models is Easier Than You Think. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2503.08250)

### Training-Free/Test-Time Alignment
* Optimizing Prompts for Text-to-Image Generation. NeurIPS 2023, [[pdf]](https://arxiv.org/pdf/2212.09611)
* RePrompt: Automatic Prompt Editing to Refine AI-Generative Art Towards Precise Expressions. CHI 2023, [[pdf]](https://arxiv.org/pdf/2302.09466)
* Improving Text-to-Image Consistency via Automatic Prompt Optimization. TMLR 2024, [[pdf]](https://arxiv.org/pdf/2403.17804)
* Dynamic Prompt Optimizing for Text-to-Image Generation. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2404.04095)
* InitNO: Boosting Text-to-Image Diffusion Models via Initial Noise Optimization. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2404.04650)
* ReNO: Enhancing One-step Text-to-Image Models through Reward-based Noise Optimization. NeurIPS 2024, [[pdf]](https://arxiv.org/pdf/2406.04312)
* Towards Better Text-to-Image Generation Alignment via Attention Modulation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2404.13899)
* Not All Noises Are Created Equally: Diffusion Noise Selection and Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.14041)
* Derivative-Free Guidance in Continuous and Discrete Diffusion Models with Soft Value-Based Decoding. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2408.08252)
* Golden Noise for Diffusion Models: A Learning Framework. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.09502)
* Preference Alignment for Diffusion Model via Explicit Denoised Distribution Estimation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.14871)
* Training-Free Diffusion Model Alignment with Sampling Demons. ICLR 2025, [[pdf]](https://arxiv.org/pdf/2410.05760) 
* Zigzag Diffusion Sampling: Diffusion Models Can Self-Improve via Self-Reflection. ICLR 2025, [[pdf]](https://arxiv.org/abs/2412.10891)
* Test-time Alignment of Diffusion Models without Reward Over-optimization. ICLR 2025, [[pdf]](https://arxiv.org/pdf/2501.05803)
* ReNeg: Learning Negative Embedding with Reward Guidance. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2412.19637)
* DyMO: Training-Free Diffusion Model Alignment with Dynamic Multi-Objective Scheduling. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2412.00759)
* Inference-Time Alignment of Diffusion Models with Direct Noise Optimization. ICML 2025, [[pdf]](https://arxiv.org/pdf/2405.18881)
* A General Framework for Inference-time Scaling and Steering of Diffusion Models. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2501.06848)
* Inference-Time Alignment in Diffusion Models with Reward-Guided Generation: Tutorial and Review. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2501.09685)
* Inference-Time Scaling for Diffusion Models beyond Scaling Denoising Steps. arXiv 2025, [[pdf]](https://arxiv.org/abs/2501.09732)


### Alignment Beyond Text-to-Image Diffusion Models
* AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2310.02054)
* HIVE: Harnessing Human Feedback for Instructional Visual Editing. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2303.09618)
* InstructVideo: Instructing Video Diffusion Models with Human Feedback. CVPR 2024, [[pdf]](https://arxiv.org/pdf/2312.12490)
* DreamReward: Text-to-3D Generation with Human Preference. ECCV 2024, [[pdf]](https://arxiv.org/pdf/2403.14613)
* Tango 2: Aligning diffusion-based text-to-audio generations through direct preference optimization. ACM MM 2024, [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3664647.3681688)
* Video Diffusion Alignment via Reward Gradients. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.08737)
* Aligning Target-Aware Molecule Diffusion Models with Exact Energy Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.01648)
* VideoRepair: Improving Text-to-Video Generation via Misalignment Evaluation and Localized Refinement. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2411.15115)
* LiFT: Leveraging Human Feedback for Text-to-Video Model Alignment. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.04814)
* SoPo: Text-to-Motion Generation Using Semi-Online Preference Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.05095)
* OnlineVPO: Align Video Diffusion Model with Online Video-Centric Preference Optimization. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.15159)
* VisionReward: Fine-Grained Multi-Dimensional Human Preference Learning for Image and Video Generation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.21059)
* A3D: Does Diffusion Dream about 3D Alignment? ICLR 2025, [[pdf]](https://arxiv.org/pdf/2406.15020)
* VideoDPO: Omni-Preference Alignment for Video Diffusion Generation. CVPR 2025, [[pdf]](https://arxiv.org/pdf/2412.14167)
* DreamDPO: Aligning Text-to-3D Generation with Human Preferences via Direct Preference Optimization. ICML 2025, [[pdf]](https://arxiv.org/abs/2502.04370)
* Flow-DPO: Improving Video Generation with Human Feedback. arXiv 2025, [[pdf]](https://arxiv.org/abs/2501.13918)
* Inference-Time Text-to-Video Alignment with Diffusion Latent Beam Search. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2501.19252)
* HuViDPO: Enhancing Video Generation through Direct Preference Optimization for Human-Centric Alignment. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2502.01690)


## Benchmarks and Evaluation 
* DALL-Eval: Probing the Reasoning Skills and Social Biases of Text-to-Image Generative Transformers. ICCV 2023, [[pdf]](https://arxiv.org/pdf/2202.04053)
* Human Evaluation of Text-to-Image Models on a Multi-Task Benchmark.	NeurIPS 2022 Workshop, [[pdf]](https://arxiv.org/pdf/2211.12112)
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
* Evaluating Text-to-Visual Generation with Image-to-Text Generation. ECCV 2024, [[pdf]](https://arxiv.org/pdf/2404.01291)
* Multimodal Large Language Models Make Text-to-Image Generative Models Align Better. NeurIPS 2024, [[pdf]](https://openreview.net/pdf?id=IRXyPm9IPW)
* Measuring Style Similarity in Diffusion Models. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2404.01292)
* T2I-CompBench++: An Enhanced and Comprehensive Benchmark for Compositional Text-to-Image Generation. TPAMI 2025, [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10847875)
* DreamBench++: A Human-Aligned Benchmark for Personalized Image Generation. ICLR 2025, [[pdf]](https://arxiv.org/pdf/2406.16855)
* PAL: Sample-Efficient Personalized Reward Modeling for Pluralistic Alignment. ICLR 2025 [[pdf]](https://openreview.net/pdf?id=1kFDrYCuSu)

  

## Fundamentals of Human Alignment
### Preference Modeling 
* Rank Analysis of Incomplete Block Designs: I. The Method of Paired Comparisons. Biometrika 1952, [[pdf]](https://www.jstor.org/stable/2334029)
* Individual Choice Behavior. John Wiley 1959, [[pdf]](https://psycnet.apa.org/record/1960-03588-000)
* The Analysis of Permutations. Journal of the Royal Statistical Society. Series C (Applied Statistics) 1975, [[pdf]](https://www.jstor.org/stable/2346567)
* Learning-to-Rank with Partitioned Preference: Fast Estimation for the Plackett-Luce Model. AISTATS 2021, [[pdf]](https://arxiv.org/pdf/2006.05067)
* Bradley-Terry and Multi-Objective Reward Modeling Are Complementary. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2507.07375)

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
* Energy-Based Preference Model Offers Better Offline Alignment than the Bradley-Terry Preference Model. ICML 2025, [[pdf]](https://arxiv.org/abs/2412.13862)


## Potential Challenges and Opportunities of Diffusion Alignment
* Scaling Laws for Reward Model Overoptimization. ICML 2023, [[pdf]](https://arxiv.org/pdf/2210.10760)
* The Alignment Problem from a Deep Learning Perspective. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2209.00626)
* Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2309.16240)
* Finetuning Text-to-Image Diffusion Models for Fairness. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2311.07604)
* Nash Learning from Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2312.00886)
* Iterative Preference Learning from Human Feedback: Bridging Theory and Practice for RLHF under KL-constraint. ICML 2024, [[pdf]](https://arxiv.org/pdf/2312.11456)
* Dense Reward for Free in Reinforcement Learning from Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.00782)
* Position: A Roadmap to Pluralistic Alignment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05070)
* Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05162)
* MaxMin-RLHF: Alignment with Diverse Human Preferences. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.08925)
* Rewards-in-Context: Multi-objective Alignment of Foundation Models with Dynamic Preference Adjustment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.10207)
* Reward Model Learning vs. Direct Policy Optimization: A Comparative Analysis of Learning from Human Preferences. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.01857)
* Generalized Preference Optimization: A Unified Approach to Offline Alignment. ICML 2024, [[pdf]](https://arxiv.org/pdf/2402.05749)
* Human Alignment of Large Language Models through Online Preference Optimisation. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.08635)
* Understanding the Learning Dynamics of Alignment with Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2403.18742)
* Position: Social Choice Should Guide AI Alignment in Dealing with Diverse Human Feedback. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.10271)
* Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study. ICML 2024, [[pdf]](https://arxiv.org/pdf/2404.10719)
* BOND: Aligning LLMs with Best-of-N Distillation. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2407.14622)
* Safety Alignment Backfires: Preventing the Re-emergence of Suppressed Concepts in Fine-tuned Text-to-Image Diffusion Models. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.00357)
* Does RLHF Scale? Exploring the Impacts From Data, Model, and Method. arXiv 2024, [[pdf]](https://arxiv.org/pdf/2412.06000)
* Test-Time Preference Optimization: On-the-Fly Alignment via Iterative Textual Feedback. arXiv 2025, [[pdf]](https://arxiv.org/abs/2501.12895)
* Can We Generate Images with CoT? Let's Verify and Reinforce Image Generation Step by Step. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2501.13926)
* BadReward: Clean-Label Poisoning of Reward Models in Text-to-Image RLHF. arXiv 2025, [[pdf]](https://arxiv.org/pdf/2506.03234)


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

