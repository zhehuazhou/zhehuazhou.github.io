---
title: "VLATest: Testing and Evaluating Vision-Language-Action Models for Robotic Manipulation"
collection: publications
permalink: /publication/2024vlatest
authorlist: 'Zhijie Wang, <b>Zhehua Zhou</b>, Jiayang Song, Yuheng Huang, Zhan Shu, Lei Ma'
excerpt: 'We present VLATest, a fuzzing framework designed to generate robotic manipulation scenes for testing VLA models.'
date: 2025-06-20
venue: '2025 ACM International Conference on the Foundations of Software Engineering (FSE)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3729343'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
pubtype: 'conference'
highlight: 'yes'
teaser: '/images/2024vlatest.png'
---

The rapid advancement of generative AI and multi-modal foundation models has shown significant potential in advancing robotic manipulation. Vision-language-action (VLA) models, in particular, have emerged as a promising approach for visuomotor control by leveraging large-scale vision-language data and robot demonstrations. However, current VLA models are typically evaluated using a limited set of hand-crafted scenes, leaving their general performance and robustness in diverse scenarios largely unexplored. To address this gap, we present VLATest, a fuzzing framework designed to generate robotic manipulation scenes for testing VLA models. Based on VLATest, we conducted an empirical study to assess the performance of seven representative VLA models. Our study results revealed that current VLA models lack the robustness necessary for practical deployment. Additionally, we investigated the impact of various factors, including the number of confounding objects, lighting conditions, camera poses, unseen objects, and task instruction mutations, on the VLA model's performance. Our findings highlight the limitations of existing VLA models, emphasizing the need for further research to develop reliable and trustworthy VLA applications.