---
title: "A Hybrid Framework for Understanding and Predicting Human Reaching Motions"
collection: publications
permalink: /publication/2017hybrid
authorlist: 'Ozgur S Oguz, <b>Zhehua Zhou</b>, Dirk Wollherr	'
excerpt: 'In this work, we propose a hybrid framework for understanding and predicting human reaching motions for human-robot collaboration.'
date: 2018-03-27
venue: 'Frontiers in Robotics and AI'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2018.00027/full'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
teaser: '/images/2017hybrid.jpg'
pubtype: 'journal'
highlight: 'yes'
---

Robots collaborating naturally with a human partner in a confined workspace need to understand and predict human motions. For understanding, a model-based approach is required as the human motor control system relies on the biomechanical properties to control and execute actions. The model-based control models explain human motions descriptively, which in turn enables predicting and analyzing human movement behaviors. In motor control, reaching motions are framed as an optimization problem. However, different optimality criteria predict disparate motion behavior. Therefore, the inverse problem—finding the optimality criterion from a given arm motion trajectory—is not unique. This paper implements an inverse optimal control (IOC) approach to determine the combination of cost functions that governs a motion execution. The results indicate that reaching motions depend on a trade-off between kinematics and dynamics related cost functions. However, the computational efficiency is not sufficient for online prediction to be utilized for HRI. In order to predict human reaching motions with high efficiency and accuracy, we combine the IOC approach with a probabilistic movement primitives formulation. This hybrid model allows an online-capable prediction while taking into account motor variability and the interpersonal differences. The proposed framework affords a descriptive and a generative model of human reaching motions which can be effectively utilized online for human-in-the-loop robot control and task execution.