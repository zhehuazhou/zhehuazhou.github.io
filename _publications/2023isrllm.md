---
title: "ISR-LLM: Iterative Self-Refined Large Language Model for Long-Horizon Sequential Task Planning"
collection: publications
permalink: /publication/2023isrllm
authorlist: '<b>Zhehua Zhou</b>, Jiayang Song, Kunpeng Yao, Zhan Shu, Lei Ma'
excerpt: 'In this work, we introduce ISR-LLM, a novel framework that improves LLM-based planning through an iterative self-refinement process.'
date: 2024-05-26
venue: '2024 IEEE International Conference on Robotics and Automation (ICRA)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://events.infovaya.com/uploads/documents/pdfviewer/07/da/129529-0239.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
teaser: '/images/2023isrllm.png'
pubtype: 'conference'
highlight: 'yes'
---

Motivated by the substantial achievements observed in Large Language Models (LLMs) in the field of natural language processing, recent research has commenced investigations into the application of LLMs for complex, long-horizon sequential task planning challenges in robotics. LLMs are advantageous in offering the potential to enhance the generalizability as task-agnostic planners and facilitate flexible interaction between human instructors and planning systems. However, task plans generated by LLMs often lack feasibility and correctness. To address this challenge, we introduce ISR-LLM, a novel framework that improves LLM-based planning through an iterative self-refinement process. The framework operates through three sequential steps: preprocessing, planning, and iterative self-refinement. During preprocessing, an LLM translator is employed to convert natural language input into a Planning Domain Definition Language (PDDL) formulation. In the planning phase, an LLM planner formulates an initial plan, which is then assessed and refined in the iterative self-refinement step by using a validator. We examine the performance of ISR-LLM across three distinct planning domains. The results show that ISR-LLM is able to achieve markedly higher success rates in task accomplishments compared to state-of-the-art LLM-based planners. Moreover, it also preserves the broad applicability and generalizability of working with natural language instructions. 