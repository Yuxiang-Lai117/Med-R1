# Med-R1: Reinforcement Learning for Medical Vision-Language Models

**Med-R1** is a reinforcement learning-enhanced vision-language model (VLM) tailored for generalizable medical reasoning. Built on Qwen2-VL-2B, Med-R1 is trained with Group Relative Policy Optimization (GRPO) to support **8 medical imaging modalities** and **5 key diagnostic tasks**, delivering high performance with parameter efficiency.

[![🤗 Model on Hugging Face](https://img.shields.io/badge/HuggingFace-Med--R1-blue?logo=huggingface)](https://huggingface.co/yuxianglai117/Med-R1)

---

## 🔍 Overview

Med-R1 explores the potential of reinforcement learning (RL) to improve medical reasoning in vision-language models. Unlike traditional supervised fine-tuning (SFT), which may overfit to task-specific data, Med-R1 leverages reward-driven optimization to guide reasoning paths that are robust, diverse, and interpretable.

---

## 🧪 Supported Modalities

We provide **cross-modality checkpoints**, each trained on a specific imaging type:

- **CT**
- **MRI**
- **X-Ray**
- **Fundus (FP)**
- **Dermoscopy (Der)**
- **Microscopy (Micro)**
- **Optical Coherence Tomography (OCT)**
- **Ultrasound (US)**

---

## 🧠 Supported Tasks

We also provide **cross-task checkpoints**, each focused on a key medical reasoning task:

- **Anatomy Identification (AI)**
- **Disease Diagnosis (DD)**
- **Lesion Grading (LG)**
- **Modality Recognition (MR)**
- **Biological Attribute Analysis (OBA)**

---

## Use of Models and Checkpoints

[![🤗 Model on Hugging Face](https://img.shields.io/badge/HuggingFace-Med--R1-blue?logo=huggingface)](https://huggingface.co/yuxianglai117/Med-R1)
