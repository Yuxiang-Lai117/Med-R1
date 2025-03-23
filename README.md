# Med-R1: Reinforcement Learning for Medical Vision-Language Models

**Med-R1** is a reinforcement learning-enhanced vision-language model (VLM) tailored for generalizable medical reasoning. Built on Qwen2-VL-2B, Med-R1 is trained with Group Relative Policy Optimization (GRPO) to support **8 medical imaging modalities** and **5 key diagnostic tasks**, delivering high performance with parameter efficiency.

[![🤗 Model on Hugging Face](https://img.shields.io/badge/HuggingFace-Med--R1-blue?logo=huggingface)](https://huggingface.co/yuxianglai117/Med-R1)
[![arXiv](https://img.shields.io/badge/arXiv-2503.13939-b31b1b.svg)](https://arxiv.org/abs/2503.13939)

The code is coming soon!
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

## Acknowledgements

We thank the authors of **OmniMedVQA** and **R1-V** for their open-source contributions.  
🔗 [R1-V GitHub Repository](https://github.com/Deep-Agent/R1-V)
🔗 [OmniMedVQA GitHub Repository](https://github.com/OpenGVLab/Multi-Modality-Arena)


## Citation
```
@article{lai2025med,
  title={Med-R1: Reinforcement Learning for Generalizable Medical Reasoning in Vision-Language Models},
  author={Lai, Yuxiang and Zhong, Jike and Li, Ming and Zhao, Shitian and Yang, Xiaofeng},
  journal={arXiv preprint arXiv:2503.13939},
  year={2025}
}
```
