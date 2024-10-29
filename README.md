# Awesome Alignment of Diffusion Models

The collection of awesome papers on alignment of diffusion models. 

If you are interested in alignment of diffusion mdoels, please refer to our survery paper "[Alignment of Diffusion Models: Fundamentals, Challenges, and Future](https://arxiv.org/pdf/2409.07253)", which is the first survey on this topic to our knowledge.

We hope to enjoy the adventure of exploring alignment and diffusion models with more researchers. Corrections and suggestions are welcomed.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/zeke-xie/awesome-alignment-of-diffusion-models)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

## Alignment Techniques of Diffusion Models
### RLHF
* Aligning Text-to-Image Models using Human Feedback
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation
* DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models
* Aligning Text-to-Image Diffusion Models with Reward Backpropagation
* Directly Fine-Tuning Diffusion Models on Differentiable Rewards
* PRDP: Proximal Reward Difference Prediction for Large-Scale Reward Finetuning of Diffusion Models

### DPO 
* Diffusion Model Alignment Using Direct Preference Optimization
* Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model
* A Dense Reward View on Aligning Text-to-Image Diffusion with Preference
* Step-aware Preference Optimization: Aligning Preference with Denoising Performance at Each Step
* Aligning Diffusion Models by Optimizing Human Utility
* Tuning Timestep-Distilled Diffusion Model Using Pairwise Sample Optimization
* Scalable Ranked Preference Optimization for Text-to-Image Generation

### Training-Free Implicit Alignment
* Improving Text-to-Image Consistency via Automatic Prompt Optimization
* Optimizing Prompts for Text-to-Image Generation
* Model-Agnostic Human Preference Inversion in Diffusion Models
* RePrompt: Automatic Prompt Editing to Refine AI-Generative Art Towards Precise Expressions
* Dynamic Prompt Optimizing for Text-to-Image Generation
* Towards Better Text-to-Image Generation Alignment via Attention Modulation
* Not All Noises Are Created Equally: Diffusion Noise Selection and Optimization


### Alignment Beyond Text-to-Image Diffusion Models
* Video Diffusion Alignment via Reward Gradients
* Aligning Target-Aware Molecule Diffusion Models with Exact Energy Optimization
* DreamReward- Text-to-3D Generation with Human Preference
* InstructVideo: Instructing Video Diffusion Models with Human Feedback
* HIVE: Harnessing Human Feedback for Instructional Visual Editing
* AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model
* Alignment is Key for Applying Diffusion Models to Retrosynthesis


## Benchmarks and Evaluation 
* Human Preference Score: Better Aligning Text-to-Image Models with Human Preference
* Human Preference Score v2: A Solid Benchmark for Evaluating Human Preferences of Text-to-Image Synthesis
* Pick-a-Pic: An Open Dataset of User Preferences for Text-to-Image Generation
* ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation
* Social Reward: Evaluating and Enhancing Generative AI through Million-User Feedback from an Online Creative Community
* Learning multi-dimensional human preference for text-to-image generation
* Rich Human Feedback for Text to Image Generation
* Multimodal Large Language Model is a Human-Aligned Annotator for Text-to-Image Generation
* DALL-Eval: Probing the reasoning skills and social biases of text-to-image generative transformers
* GenEval: An Object-Focused Framework for Evaluating Text-to-Image Alignment
* VPGen & VPEval: Visual Programming for Text-to-Image Generation and Evaluation
* Holistic Evaluation of Text-to-Image Models
* LLMScore: Unveiling the Power of Large Language Models in Text-to-Image Synthesis Evaluation
* Measuring style similarity in diffusion models
  

## Fundamentals of Human Alignment
### Preference Modeling 
* Rank analysis of incomplete block designs: I. The method of paired comparisons
* Individual choice behavior
* The analysis of permutations
* Learning-to-Rank with Partitioned Preference: Fast Estimation for the Plackett-Luce Model
* Models of human preference for learning reward functions
* Beyond Preferences in AI Alignment

### RLHF 
* Training language models to follow instructions with human feedback
* Back to Basics: Revisiting REINFORCE Style Optimization for Learning from Human Feedback in LLMs
* Raft: Reward ranked finetuning for generative foundation model alignment
* Rrhf: Rank responses to align language models with human feedback without tears
* Constitutional AI: Harmlessness from AI Feedback
* RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback

### DPO 
* Direct Preference Optimization: Your Language Model is Secretly a Reward Model
* A General Theoretical Paradigm to Understand Learning from Human Preferences
* ORPO- Monolithic Preference Optimization without Reference Model
* KTO: Model Alignment as Prospect Theoretic Optimization
* Preference Ranking Optimization for Human Alignment
* Lipo: Listwise preference optimization through learning-to-rank.

## Potential Challenges and Opportunities of Diffusion Alignment
* Scaling laws for reward model overoptimization
* AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback
* Stepwise Alignment for Constrained Language Model Policy Optimization
* The Alignment Problem from a Deep Learning Perspective
* Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints
* Self-Play Preference Optimization for Language Model Alignment
* SimPO: Simple Preference Optimization with a Reference-Free Reward
* What Makes Good Data for Alignment? A Comprehensive Study of Automatic Data Selection in Instruction Tuning, ICLR2024
* Generalized Preference Optimization: A Unified Approach to Offline Alignment
* Nash Learning from Human Feedback
* Human Alignment of Large Language Models through Online Preference Optimisation
* Active Preference Learning for Large Language Models
* Token-level Direct Preference Optimization
* Dense Reward for Free in Reinforcement Learning from Human Feedback
* Coactive Learning for Large Language Models using Implicit User Feedback
* BRAIn: Bayesian Reward-conditioned Amortized Inference for natural language generation from feedback
* BOND: Aligning LLMs with Best-of-N Distillation
* Self-Alignment of Large Language Models via Monopolylogue-based Social Scene Simulation
* ULTRAFEEDBACK: Boosting Language Models with Scaled AI Feedback
* A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity
* Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study
* Understanding the Learning Dynamics of Alignment with Human Feedback
* Fundamental Limitations of Alignment in Large Language Models
* Reward Model Learning vs. Direct Policy Optimization: A Comparative Analysis of Learning from Human Preferences
* Iterative Preference Learning from Human Feedback: Bridging Theory and Practice for RLHF under KL-constraint
* Preference Fine-Tuning of LLMs Should Leverage Suboptimal, On-Policy Data
* AI Alignment with Changing and Influenceable Reward Functions
* Rewards-in-Context: Multi-objective Alignment of Foundation Models with Dynamic Preference Adjustment
* MaxMin-RLHF: Alignment with Diverse Human Preferences
* Provably Robust DPO: Aligning Language Models with Noisy Feedback
* Visual Adversarial Examples Jailbreak Aligned Large Language Models
* Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications
* Decoding-time Realignment of Language Models
* Towards Efficient Exact Optimization of Language Model Alignment
* Linear Alignment: A Closed-form Solution for Aligning Human Preferences without Tuning and Feedback
* Feedback Efficient Online Fine-Tuning of Diffusion Models
* Position: A Roadmap to Pluralistic Alignment
* Position: Social Choice Should Guide AI Alignment in Dealing with Diverse Human Feedback


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

