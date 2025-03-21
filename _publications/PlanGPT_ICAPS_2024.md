---
title: "Learning general policies for planning through GPT models"
collection: publications
category: conferences
permalink: 'https://ojs.aaai.org/index.php/ICAPS/article/view/31510'
excerpt: 'This paper introduces PlanGPT, a GPT-based model customized for classical planning. PlanGPT is trained from scratch on a dataset of solved planning instances to learn a general policy. Once trained, it can generate solution plans for new problems within the same domain. We enhance the model performance by incorporating automated planning knowledge into the training process. We evaluate PlanGPT across several planning domains and compare its performance to other deep learning techniques for generalized planning, demonstrating the effectiveness of our approach. [link paper](https://ojs.aaai.org/index.php/ICAPS/article/view/31510)'
date: 2024-05-30
venue: '34th International Conference on Automated Planning and Scheduling (ICAPS)'
slidesurl: 'http://academicpages.github.io/files/slides_plangpt_icaps_2024.pdf'
paperurl: 'http://academicpages.github.io/files/paper_plangpt_icaps24.pdf'
citation: 'Learning general policies for planning through GPT models, N. Rossetti, M. Tummolo, AE. Gerevini, L. Putelli, I. Serina, M. Chiari, M. Olivato - Proceedings of the 34th International Conference on Automated Planning and Scheduling (ICAPS), 2024'
---

Transformer-based architectures, such as T5, BERT and GPT, have demonstrated revolutionary capabilities in Natural Language Processing. Several studies showed that deep learning models using these architectures not only possess remarkable linguistic knowledge, but they also exhibit forms of factual knowledge, common sense, and even programming skills. However, the scientific community still debates about their reasoning capabilities, which have been recently tested in the context of automated AI planning; the literature presents mixed results, and the prevailing view is that current transformer-based models may not be adequate for planning. In this paper, we address this challenge differently. We introduce a GPT-based model customised for planning (PLANGPT) to learn a general policy for classical planning by training the model from scratch with a dataset of solved planning instances. Once PLANGPT has been trained for a domain, it can be used to generate a solution plan for an input problem instance in that domain. Our training procedure exploits automated planning knowledge to enhance the performance of the trained model. We build and evaluate our GPT model with several planning domains, and we compare its performance wrt other recent deep learning techniques for generalised planning, demonstrating the effectiveness of the proposed approach.  [link paper](https://ojs.aaai.org/index.php/ICAPS/article/view/31510)
