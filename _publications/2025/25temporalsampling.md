---
title:         "Temporal Sampling for Forgotten Reasoning in LLMs"
date:           2025-07-01 00:01:00 +0800
selected:       true
# pub:            "Thirteenth International Conference on Learning Representations (ICLR)"
pub: "Preprint"
pub_date:       "2025"
abstract: >-
  Fine-tuning large language models (LLMs) is intended to improve their reasoning capabilities, yet we uncover a counterintuitive effect: models often forget how to solve problems they previously answered correctly during training. We term this phenomenon temporal forgetting and show that it is widespread across model sizes, fine-tuning methods (both Reinforcement Learning and Supervised Fine-Tuning), and multiple reasoning benchmarks. To address this gap, we introduce Temporal Sampling, a simple decoding strategy that draws outputs from multiple checkpoints along the training trajectory. This approach recovers forgotten solutions without retraining or ensembling, and leads to substantial improvements in reasoning performance, gains from 4 to 19 points in Pass@k and consistent gains in Majority@k across several benchmarks. We further extend our method to LoRA-adapted models, demonstrating that storing only adapter weights across checkpoints achieves similar benefits with minimal storage cost. By leveraging the temporal diversity inherent in training, Temporal Sampling offers a practical, compute-efficient way to surface hidden reasoning ability and rethink how we evaluate LLMs.
  
cover:          /assets/images/covers/img_magpie.png
authors:
- Yuetai Li
- Zhangchen Xu
- Fengqing Jiang
- Bhaskar Ramasubramanian
- Luyao Niu
- Bill Yuchen Lin
- Xiang Yue
- Radha Poovendran
links:
  Preprint: https://arxiv.org/abs/2505.20196


---