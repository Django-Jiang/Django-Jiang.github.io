---
title:          "CleanGen: Mitigating Backdoor Attacks for Generation Tasks in Large Language Models"
date:           2024-10-06 00:01:00 +0800
selected:       true
# pub:            "Conference on Empirical Methods in Natural Language Processing (EMNLP)"
pub: "EMNLP 2024"
pub_date:       "2024"
abstract: >-
  This paper introduces CleanGen, an inference-time defense for LLMs that mitigates backdoor attacks by identifying and replacing suspicious tokens—those with unusually high probabilities in compromised models—with tokens from a trusted, uncompromised LLM. Empirical evaluations demonstrate that CleanGen significantly reduces attack success rates across multiple backdoor attacks while preserving the quality and helpfulness of responses with minimal computational overhead.
cover:          /assets/images/covers/img_cleangen.png
authors:
- Yuetai Li
- Zhangchen Xu
-  Fengqing Jiang
-   Luyao Niu
-    Dinuka Sahabandu
-     Bhaskar Ramasubramanian
-      Radha Poovendran
links:
  Paper: https://aclanthology.org/2024.emnlp-main.514/
  Code: https://github.com/uw-nsl/CleanGen
---