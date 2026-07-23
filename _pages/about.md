---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---   

Hello! I'm Sapana, a scientist at Amazon AGI, focused on reinforcement learning (RL) post-training. I build the RL systems that turn small open-source models into specialized agents and models—often matching much larger general-purpose ones. My PhD was on online learning, RL, and RLHF, with a focus on safe and adaptive sequential decision making—algorithms that satisfy unknown safety constraints and stay reliable under distribution shift. I received my doctorate from Texas A&M University (TAMU) working with [Dr. Dileep Kalathil](http://people.tamu.edu/~dileep.kalathil/).

## Multi-Turn Reinforcement Learning in Amazon SageMaker AI

I’m the **science tech lead** for **SageMaker AI Multi-Turn RL (MTRL)**, a fully serverless model customization service that runs the entire agentic RL loop—rollout orchestration, trajectory collection, training, checkpoints, and evaluation—on open-source models like **Qwen, GPT-OSS, and Gemma**, with no infrastructure setup required. To learn more, see this best-practices guide using the Amazon Science SOP (Standard Operating Procedure)-Bench benchmark as a running example: [Best practices for Multi-Turn RL in Amazon SageMaker AI](https://aws.amazon.com/blogs/machine-learning/best-practices-for-multi-turn-reinforcement-learning-in-amazon-sagemaker-ai/).

![Multi-turn reinforcement learning service overview in Amazon SageMaker AI](/images/multi-turn-rl-sagemaker.jpg)

## Reinforcement Fine-Tuning on Amazon Bedrock and SageMaker AI

Before MTRL, I was a core contributor to **Amazon Bedrock and SageMaker AI Reinforcement Fine-Tuning (RFT)**, the single-turn post-training service for open-source models ([launched December 2025](https://aws.amazon.com/blogs/aws/new-serverless-customization-in-amazon-sagemaker-ai-accelerates-model-fine-tuning/)). RFT customizes models like **Qwen, Meta’s Llama, DeepSeek, OpenAI’s gpt-oss**—from reward signals instead of large labeled datasets, via **RLAIF**, **RLVR**, **SFT**, and **DPO**, with no infrastructure to manage. I co-authored the best-practices guide: [Reinforcement fine-tuning on Amazon Bedrock: Best practices](https://aws.amazon.com/blogs/machine-learning/reinforcement-fine-tuning-on-amazon-bedrock-best-practices/).

<!-- My PhD was on online learning, RL, and RLHF, with a focus on safe and adaptive sequential decision making—algorithms that satisfy unknown safety constraints and stay reliable under distribution shift. I received my doctorate from Texas A&M University (TAMU) working with [Dr. Dileep Kalathil](http://people.tamu.edu/~dileep.kalathil/). Previously, I was a research fellow at MPI-SWS, Germany with [Dr. Adish Singla](https://machineteaching.mpi-sws.org/adishsingla.html), and did an MS (Research) at IIT Madras with [Dr. Balaraman Ravindran](http://www.cse.iitm.ac.in/~ravi/) and [Dr. Radha Krishna Ganti](http://www.ee.iitm.ac.in/~rganti/).  -->

<!-- Happy to chat about agentic RL, post-training recipes, or how to get RL working on your own agent—Please email to connect. -->

## Selected Work

1. **MaxCode** (arXiv 2026) — max-reward RL framework for LLM-driven code optimization on CUDA ([KernelBench](https://github.com/ScalingIntelligence/KernelBench)) and C++ (PIE). +20.3% relative improvement in absolute speedup value and +10.1% in relative speedup ranking over baselines.
2. **RA-RLHF** (NeurIPS 2024) — CVaR-based PPO objective that suppresses rare-but-significant toxic generations during RLHF.
3. **AgentOccam** (ICLR 2025) — showed that aligning a web agent's observation and action space to LLM pretraining beats elaborate prompting, search, and multi-agent scaffolds. +9.8 pts over prior SOTA and +26.6 pts (+161%) over plain web agents on WebArena, without in-context examples or search.

Full publication list: [sapanachaudhary.github.io/publications](https://sapanachaudhary.github.io/publications/).

<!---  I have worked on multiple algorithmic paradigms in RL ranging from generative adversarial imitation learning to meta-RL. More recently, I have pivoted towards fine-tuning Large Language Models (LLMs) using Reinforcement Learning from Human Feedback (RLHF). This pivot reflects my growing interest in the intersection of natural language processing and reinforcement learning. I have also built abstractive and extractive Q&A systems using retrieval augmented generation (RAG) and LLMs while doing an applied science internship at Amazon.

In the long run, I want to focus on using principles from the human cognition and psychology to build better reinforcement learning agents.   

Previously, I was a research fellow in the [Machine Teaching Group](https://machineteaching.mpi-sws.org/index.html) at the Max Planck Institute for Software Systems, Saarbrücken, Germany. I was advised by [Dr. Adish Singla](https://machineteaching.mpi-sws.org/adishsingla.html).

I have completed MS (Research) in Computational Science from IIT Madras, India. My advisors during MS were [Dr. Balaraman Ravindran](http://www.cse.iitm.ac.in/~ravi/) and [Dr. Radha Krishna Ganti](http://www.ee.iitm.ac.in/~rganti/). My MS thesis is titled 'On Learning Smooth Policies in Imitation Learning'. -->

Aside from work, I like to hike, cook, paint, and [photograph](https://www.instagram.com/a.thing.of.art/).

## News
- **[Jun 2026]** Multi-Turn RL (MTRL) launched on Amazon SageMaker AI!
- **[Jan 2026]** VeriCoT accepted to ICLR!
- **[Jan 2026]** New paper on kernel code optimization out on arxiv!
- **[Dec 2025]** Serverless open source model reinforcement finetuning (RFT) launched on AWS SageMaker!

