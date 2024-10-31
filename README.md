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
* InstructVideo: Instructing Video Diffusion Models with Human Feedback. CVPR2024, [[pdf]](https://arxiv.org/pdf/2312.12490)
* HIVE: Harnessing Human Feedback for Instructional Visual Editing. CVPR2024, [[pdf]](https://arxiv.org/pdf/2303.09618)
* AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model. ICLR 2024, [[pdf]](https://arxiv.org/pdf/2310.02054)
* Alignment is Key for Applying Diffusion Models to Retrosynthesis. arXiv:2405, [[pdf]](https://arxiv.org/pdf/2405.17656)


## Benchmarks and Evaluation 
* Human Preference Score: Better Aligning Text-to-Image Models with Human Preference. , [[pdf]]()
* Human Preference Score v2: A Solid Benchmark for Evaluating Human Preferences of Text-to-Image Synthesis. , [[pdf]]()
* Pick-a-Pic: An Open Dataset of User Preferences for Text-to-Image Generation. , [[pdf]]()
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation. , [[pdf]]()
* Social Reward: Evaluating and Enhancing Generative AI through Million-User Feedback from an Online Creative Community. , [[pdf]]()
* Learning multi-dimensional human preference for text-to-image generation. , [[pdf]]()
* Rich Human Feedback for Text to Image Generation. , [[pdf]]()
* Multimodal Large Language Model is a Human-Aligned Annotator for Text-to-Image Generation. , [[pdf]]()
* DALL-Eval: Probing the reasoning skills and social biases of text-to-image generative transformers. , [[pdf]]()
* GenEval: An Object-Focused Framework for Evaluating Text-to-Image Alignment. , [[pdf]]()
* VPGen & VPEval: Visual Programming for Text-to-Image Generation and Evaluation. , [[pdf]]()
* Holistic Evaluation of Text-to-Image Models. , [[pdf]]()
* LLMScore: Unveiling the Power of Large Language Models in Text-to-Image Synthesis Evaluation. , [[pdf]]()
* Measuring style similarity in diffusion models. , [[pdf]]()
  

## Fundamentals of Human Alignment
### Preference Modeling 
* Rank analysis of incomplete block designs: I. The method of paired comparisons. , [[pdf]]()
* Individual choice behavior. , [[pdf]]()
* The analysis of permutations. , [[pdf]]()
* Learning-to-Rank with Partitioned Preference: Fast Estimation for the Plackett-Luce Model. , [[pdf]]()
* Models of human preference for learning reward functions. , [[pdf]]()
* Beyond Preferences in AI Alignment. , [[pdf]]()

### RLHF 
* Training language models to follow instructions with human feedback. , [[pdf]]()
* Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs. , [[pdf]]()
* Raft: Reward ranked finetuning for generative foundation model alignment. , [[pdf]]()
* Rrhf: Rank responses to align language models with human feedback without tears. , [[pdf]]()
* Constitutional AI: Harmlessness from AI Feedback. , [[pdf]]()
* RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback. , [[pdf]]()

### DPO 
* Direct Preference Optimization: Your Language Model is Secretly a Reward Model. , [[pdf]]()
* A General Theoretical Paradigm to Understand Learning from Human Preferences. , [[pdf]]()
* ORPO- Monolithic Preference Optimization without Reference Model. , [[pdf]]()
* KTO: Model Alignment as Prospect Theoretic Optimization. , [[pdf]]()
* Preference Ranking Optimization for Human Alignment. , [[pdf]]()
* Lipo: Listwise preference optimization through learning-to-rank. , [[pdf]]()

## Potential Challenges and Opportunities of Diffusion Alignment
* Scaling laws for reward model overoptimization. , [[pdf]]()
* AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback. , [[pdf]]()
* Stepwise Alignment for Constrained Language Model Policy Optimization. , [[pdf]]()
* The Alignment Problem from a Deep Learning Perspective. , [[pdf]]()
* Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints. , [[pdf]]()
* Self-Play Preference Optimization for Language Model Alignment. , [[pdf]]()
* SimPO: Simple Preference Optimization with a Reference-Free Reward. , [[pdf]]()
* What Makes Good Data for Alignment? A Comprehensive Study of Automatic Data Selection in Instruction Tuning. , [[pdf]]()
* Generalized Preference Optimization: A Unified Approach to Offline Alignment. , [[pdf]]()
* Nash Learning from Human Feedback. , [[pdf]]()
* Human Alignment of Large Language Models through Online Preference Optimisation. , [[pdf]]()
* Active Preference Learning for Large Language Models. , [[pdf]]()
* Token-level Direct Preference Optimization. , [[pdf]]()
* Dense Reward for Free in Reinforcement Learning from Human Feedback. , [[pdf]]()
* Coactive Learning for Large Language Models using Implicit User Feedback. , [[pdf]]()
* BRAIn: Bayesian Reward-conditioned Amortized Inference for natural language generation from feedback. , [[pdf]]()
* BOND: Aligning LLMs with Best-of-N Distillation. , [[pdf]]()
* Self-Alignment of Large Language Models via Monopolylogue-based Social Scene Simulation. , [[pdf]]()
* ULTRAFEEDBACK: Boosting Language Models with Scaled AI Feedback. , [[pdf]]()
* A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity. , [[pdf]]()
* Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study. , [[pdf]]()
* Understanding the Learning Dynamics of Alignment with Human Feedback. , [[pdf]]()
* Fundamental Limitations of Alignment in Large Language Models. , [[pdf]]()
* Reward Model Learning vs. Direct Policy Optimization: A Comparative Analysis of Learning from Human Preferences. , [[pdf]]()
* Iterative Preference Learning from Human Feedback: Bridging Theory and Practice for RLHF under KL-constraint. , [[pdf]]()
* Preference Fine-Tuning of LLMs Should Leverage Suboptimal, On-Policy Data. , [[pdf]]()
* AI Alignment with Changing and Influenceable Reward Functions. , [[pdf]]()
* Rewards-in-Context: Multi-objective Alignment of Foundation Models with Dynamic Preference Adjustment. , [[pdf]]()
* MaxMin-RLHF: Alignment with Diverse Human Preferences. , [[pdf]]()
* Provably Robust DPO: Aligning Language Models with Noisy Feedback. , [[pdf]]()
* Visual Adversarial Examples Jailbreak Aligned Large Language Models. , [[pdf]]()
* Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications. , [[pdf]]()
* Decoding-time Realignment of Language Models. , [[pdf]]()
* Towards Efficient Exact Optimization of Language Model Alignment. , [[pdf]]()
* Linear Alignment: A Closed-form Solution for Aligning Human Preferences without Tuning and Feedback. , [[pdf]]()
* Feedback Efficient Online Fine-Tuning of Diffusion Models. , [[pdf]]()
* Position: A Roadmap to Pluralistic Alignment. , [[pdf]]()
* Position: Social Choice Should Guide AI Alignment in Dealing with Diverse Human Feedback. , [[pdf]]()


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

