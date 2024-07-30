---
title: "Towards Building AI-CPS with NVIDIA Isaac Sim: An Industrial Benchmark and Case Study for Robotics Manipulation"
collection: publications
permalink: /publication/2024towards
authorlist: '<b>Zhehua Zhou</b>, Jiayang Song, Xuan Xie, Zhan Shu, Lei Ma, Dikai Liu, Jianxiong Yin, Simon See'
excerpt: 'As a foundational step towards building reliable AI-enabled robotics systems, in this paper, we propose a public benchmark for robotics manipulation.'
date: 2024-04-16
venue: 'IEEE/ACM 46th International Conference on Software Engineering: Software Engineering in Practice (ICSE-SEIP)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3639477.3639740'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
teaser: '/images/2024towards.png'
pubtype: 'conference'
highlight: 'yes'
---

As a representative cyber-physical system (CPS), robotic manipulators have been widely adopted in various academic research and industrial processes, indicating their potential to act as a universal interface between the cyber and the physical worlds. Recent studies in robotics manipulation have started employing artificial intelligence (AI) approaches as controllers to achieve better adaptability and performance. However, the inherent challenge of explaining AI components introduces uncertainty and unreliability to these AI-enabled robotics systems, necessitating a reliable development platform for system design and performance assessment. As a foundational step towards building reliable AI-enabled robotics systems, in this paper, we propose a public benchmark for robotics manipulation. It leverages NVIDIA Omniverse Isaac Sim as the simulation platform, encompassing eight representative manipulation tasks and multiple AI software controllers. An extensive empirical evaluation is conducted to analyze the performance of AI controllers in solving robotics manipulation tasks, enabling a relatively thorough understanding of their effectiveness. To further demonstrate the applicability of our benchmark, we also developed the first falsification framework that is compatible with Isaac Sim. This framework bridges the gap between traditional falsification methods and modern physics engine-based simulations. The effectiveness of different optimization methods in falsifying AI-enabled robotics manipulation with physical simulators is also examined. Our work not only establishes a foundation for the design and development of AI-enabled robotics systems but also provides practical experience and guidance to practitioners in this field, promoting further research in this critical academic and industrial domain. The benchmarks, source code, and detailed evaluation results are available at https://sites.google.com/view/ai-cps-robotics-manipulation/home.