---
title: "MORTAR: A Model-based Runtime Action Repair Framework for AI-enabled Cyber-Physical Systems"
collection: publications
permalink: /publication/2024mortar
authorlist: 'Renzhi Wang, <b>Zhehua Zhou</b>, Jiayang Song, Xuan Xie, Xiaofei Xie, Lei Ma'
excerpt: 'We propose MORTAR, a runtime action repair framework designed for AI-CPSs in this work'
date: 2024-08-07
venue: 'ArXiv Preprint:2408.03892'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2408.03892'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
pubtype: 'preprint'
highlight: 'no'
---

Cyber-Physical Systems (CPSs) are increasingly prevalent across various industrial and daily-life domains, with applications ranging from robotic operations to autonomous driving. With recent advancements in artificial intelligence (AI), learning-based components, especially AI controllers, have become essential in enhancing the functionality and efficiency of CPSs. However, the lack of interpretability in these AI controllers presents challenges to the safety and quality assurance of AI-enabled CPSs (AI-CPSs). Existing methods for improving the safety of AI controllers often involve neural network repair, which requires retraining with additional adversarial examples or access to detailed internal information of the neural network. Hence, these approaches have limited applicability for black-box policies, where only the inputs and outputs are accessible during operation. To overcome this, we propose MORTAR, a runtime action repair framework designed for AI-CPSs in this work. MORTAR begins by constructing a prediction model that forecasts the quality of actions proposed by the AI controller. If an unsafe action is detected, MORTAR then initiates a repair process to correct it. The generation of repaired actions is achieved through an optimization process guided by the safety estimates from the prediction model. We evaluate the effectiveness of MORTAR across various CPS tasks and AI controllers. The results demonstrate that MORTAR can efficiently improve task completion rates of AI controllers under specified safety specifications. Meanwhile, it also maintains minimal computational overhead, ensuring real-time operation of the AI-CPSs. 