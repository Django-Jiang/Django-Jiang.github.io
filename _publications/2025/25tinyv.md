---
title:         "TinyV: Reducing False Negatives in Verification Improves RL for LLM Reasoning"
date:           2025-07-02 00:01:00 +0800
selected:       true
pub: "Preprint"
pub_date:       "2025"
abstract: >-
  Reinforcement Learning (RL) has become a powerful tool for enhancing the reasoning abilities of large language models (LLMs) by optimizing their policies with reward signals. Yet, RL's success relies on the reliability of rewards, which are provided by verifiers. In this paper, we expose and analyze a widespread problem--false negatives--where verifiers wrongly reject correct model outputs. Our in-depth study of the Big-Math-RL-Verified dataset reveals that over 38% of model-generated responses suffer from false negatives, where the verifier fails to recognize correct answers. We show, both empirically and theoretically, that these false negatives severely impair RL training by depriving the model of informative gradient signals and slowing convergence. To mitigate this, we propose tinyV, a lightweight LLM-based verifier that augments existing rule-based methods, which dynamically identifies potential false negatives and recovers valid responses to produce more accurate reward estimates. Across multiple math-reasoning benchmarks, integrating TinyV boosts pass rates by up to 10% and accelerates convergence relative to the baseline. Our findings highlight the critical importance of addressing verifier false negatives and offer a practical approach to improve RL-based fine-tuning of LLMs.
  
cover:          /assets/images/covers/img_magpie.png
authors:
- Zhangchen Xu
- Yuetai Li
- Fengqing Jiang
- Bhaskar Ramasubramanian
- Luyao Niu
- Bill Yuchen Lin
- Radha Poovendran
links:
  Preprint: https://arxiv.org/abs/2505.14625
  Code: https://github.com/uw-nsl/TinyV


---