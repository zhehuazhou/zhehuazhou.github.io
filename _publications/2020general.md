---
title: "A General Framework to Increase Safety of Learning Algorithms for Dynamical Systems Based on Region of Attraction Estimation"
collection: publications
permalink: /publication/2020general
authorlist: '<b>Zhehua Zhou</b>, Ozgur S Oguz, Marion Leibold, Martin Buss'
excerpt: 'In this article, we propose a computationally effective and general safe learning framework, specifically for complex dynamical systems.'
date: 2020-06-02
venue: 'IEEE Transactions on Robotics'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9106864'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
teaser: '/images/2020general.gif'
pubtype: 'journal'
highlight: 'yes'
---

Although the state-of-the-art learning approaches exhibit impressive results for dynamical systems, only a few applications on real physical systems have been presented. One major impediment is that the intermediate policy during the training procedure may result in behaviors that are not only harmful to the system itself but also to the environment. In essence, imposing safety guarantees for learning algorithms is vital for autonomous systems acting in the real world. In this article, we propose a computationally effective and general safe learning framework, specifically for complex dynamical systems. With a proper definition of the safe region, a supervisory control strategy, which switches the actions applied on the system between the learning-based controller and a predefined corrective controller, is given. A simplified system facilitates the estimation of the safe region for the high-dimensional dynamical system. During the learning phase, the belief of the safe region is updated with the actual execution results of the corrective controller, which in turn enables the learning-based controller to have more freedom in choosing its actions. Two examples are given to demonstrate the performance of the proposed framework, one simple inverted pendulum to illustrate the online adaptation method, and one quadcopter control task to show the overall performance.
