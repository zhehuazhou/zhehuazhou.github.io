---
title: "Multilingual Blending: LLM Safety Alignment Evaluation with Language Mixture"
collection: publications
permalink: /publication/2024multilingual
authorlist: 'Jiayang Song, Yuheng Huang, <b>Zhehua Zhou</b>, Lei Ma'
excerpt: 'In this work, we introduce Multilingual Blending, a mixed-language query-response scheme designed to evaluate the safety alignment of various state-of-the-art LLMs.'
date: 2024-07-10
venue: '2025 Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics (NAACL)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2407.07342'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
pubtype: 'conference'
highlight: 'no'
---

As safety remains a crucial concern throughout the development lifecycle of Large Language Models (LLMs), researchers and industrial practitioners have increasingly focused on safeguarding and aligning LLM behaviors with human preferences and ethical standards. LLMs, trained on extensive multilingual corpora, exhibit powerful generalization abilities across diverse languages and domains. However, current safety alignment practices predominantly focus on single-language scenarios, which leaves their effectiveness in complex multilingual contexts, especially for those complex mixed-language formats, largely unexplored. In this study, we introduce Multilingual Blending, a mixed-language query-response scheme designed to evaluate the safety alignment of various state-of-the-art LLMs (e.g., GPT-4o, GPT-3.5, Llama3) under sophisticated, multilingual conditions. We further investigate language patterns such as language availability, morphology, and language family that could impact the effectiveness of Multilingual Blending in compromising the safeguards of LLMs. Our experimental results show that, without meticulously crafted prompt templates, Multilingual Blending significantly amplifies the detriment of malicious queries, leading to dramatically increased bypass rates in LLM safety alignment (67.23% on GPT-3.5 and 40.34% on GPT-4o), far exceeding those of single-language baselines. Moreover, the performance of Multilingual Blending varies notably based on intrinsic linguistic properties, with languages of different morphology and from diverse families being more prone to evading safety alignments. These findings underscore the necessity of evaluating LLMs and developing corresponding safety alignment strategies in a complex, multilingual context to align with their superior cross-language generalization capabilities. 