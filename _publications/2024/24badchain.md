---
title:          "BadChain: Backdoor Chain-of-Thought Prompting for Large Language Models"
date:           2024-03-24 00:01:00 +0800
selected:       true
# pub:            "Twelfth International Conference on Learning Representations (ICLR 2024)"
pub: "ICLR 2024"
pub_date:       "2024"
abstract: >-
  This paper introduces BadChain, a backdoor attack against large language models that exploits chain-of-thought prompting by inserting a malicious reasoning step without needing access to the training data or model parameters. When a backdoor trigger is present in a query, the modified demonstration examples lead the model to output unintended content, with high attack success rates observed especially on models with strong reasoning capabilities like GPT-4.  
cover:          /assets/images/covers/img_badchain.png
authors:
- Zhen Xiang
- Fengqing Jiang
- Zidi Xiong
- Bhaskar Ramasubramanian
- Radha Poovendran
-  Bo Li
links:
  Paper: https://openreview.net/forum?id=c93SBwz1Ma
  Code: https://github.com/Django-Jiang/BadChain
---