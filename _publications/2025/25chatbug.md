---
title:          "ChatBug: A Common Vulnerability of Aligned LLMs Induced by Chat Templates"
date:           2025-01-07 00:01:00 +0800
selected:       true
# pub:            "39th AAAI Conference on Artificial Intelligence (AAAI)"
pub: "AAAI 2025 (AIA)"
pub_date:       "2025"
abstract: >-
  This paper reveals that using rigid chat templates for instruction tuning can inadvertently introduce a vulnerability, termed ChatBug, which attackers can exploit by deviating from the expected format to bypass safety alignments. The authors demonstrate that ChatBug can trigger unintended responses in multiple state-of-the-art LLMs and, although adversarial training can mitigate this risk, it significantly degrades performance, highlighting a trade-off between safety and helpfulness.
  
cover:          /assets/images/covers/img_chatbug.png
authors:
- Fengqing Jiang
- Zhangchen Xu
-  Luyao Niu
-   Bill Yuchen Lin
-    Radha Poovendran
links:
  # Paper: https://dl.acm.org/doi/10.5555/3698900.3699134
  Full Version: https://arxiv.org/abs/2406.12935
  Code: https://github.com/uw-nsl/ChatBug
---