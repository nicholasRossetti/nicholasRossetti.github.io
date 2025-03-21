---
title: "Enhancing GPT-based Planning Policies by Model-based Plan Validation"
collection: publications
category: conferences
permalink: 'https://link.springer.com/chapter/10.1007/978-3-031-71170-1_26'
excerpt: 'This paper builds on PlanGPT, a GPT-2 model tailored for automated planning tasks, which, despite strong performance, can produce invalid plans that violate preconditions or fail to meet goal fluents. To improve reliability, we propose an enhanced version of PlanGPT that incorporates a plan validator into the token generation process. This validator filters out invalid plan sequences as they are being generated, resulting in more accurate plans. The method is tested across multiple planning domains, showing improved robustness and effectiveness. [link paper](https://link.springer.com/chapter/10.1007/978-3-031-71170-1_26)'
date: 2024-09-09
venue: ' 18th International Conference of Neural-Symbolic Learning and Reasoning (NeSy)'
#slidesurl: 'http://academicpages.github.io/files/slides_plangpt_icaps_2024.pdf'
paperurl: 'http://academicpages.github.io/files/paper_plangpt_nesy2024.pdf'
citation: 'Enhancing GPT-based Planning Policies by Model-based Plan Validation, N. Rossetti, M. Tummolo, AE. Gerevini, M. Olivato, L. Putelli, I. Serina - Proceedings of the 18th International Conference of Neural-Symbolic Learning and Reasoning (NeSy), 2024'
---

Despite Large Language Models (LLMs) have revolutionised Natural Language Processing (NLP), their capability of performing logical reasoning and automated planning is still debated. In this context, the state of the art is PlanGPT, a GPT-2 model specifically trained for planning tasks. This recent approach provides GPT-based planning policies with remarkable performance, but it can generate invalid plans containing violated action preconditions or unsatisfied goals. To address this limitation, we propose an extension of PlanGPT that integrates a plan validator into the generation process. The validator is exploited to prune invalid plan prefixes during the GPT token generation, obtaining a more robust and powerful solution to planning via GPT. We empirically evaluate the effectiveness of our approach and demonstrate its potential in various planning domains. [link paper](https://link.springer.com/chapter/10.1007/978-3-031-71170-1_26)