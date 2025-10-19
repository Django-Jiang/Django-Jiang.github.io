---
title:         "BadScientist: Can a Research Agent Write Convincing but Unsound Papers that Fool LLM Reviewers?"
date:           2025-07-04 00:01:00 +0800
selected:       true
pub: "Agents4Science 2025 (Oral)"
award:
 - Agents4Science 2025 Best Paper Award
pub_date:       "2025"
abstract: >-
  The convergence of LLM-powered research assistants and AI-based peer review systems creates a critical vulnerability: fully automated publication loops where AI-generated research is evaluated by AI reviewers without human oversight. We investigate this through BadScientist, a framework that evaluates whether fabrication-oriented paper generation agents can deceive multi-model LLM review systems. Our generator employs presentation-manipulation strategies requiring no real experiments. We develop a rigorous evaluation framework with formal error guarantees (concentration bounds and calibration analysis), calibrated on real data. Our results reveal systematic vulnerabilities: fabricated papers achieve acceptance rates up to $82.0\%$. Critically, we identify concern-acceptance conflict---reviewers frequently flag integrity issues yet assign acceptance-level scores. Our mitigation strategies show only marginal improvements, with detection accuracy barely exceeding random chance. Despite provably sound aggregation mathematics, integrity checking systematically fails, exposing fundamental limitations in current AI-driven review systems and underscoring the urgent need for defense-in-depth safeguards in scientific publishing.
  
cover:          /assets/images/covers/img_magpie.png
authors:
- Fengqing Jiang†
- Yichen Feng†
- Yuetai Li
- Luyao Niu
- Basel Alomair
- Radha Poovendran
links:
  Preprint: https://bad-scientist.github.io/#paper
  Project Page: https://bad-scientist.github.io/


---