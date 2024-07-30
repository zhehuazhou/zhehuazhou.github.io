---
title: "Safe Reinforcement Learning with Model Order Reduction Techniques"
collection: talks
type: "Invited Talk"
permalink: /talks/saferl
venue: "The 1st International Workshop on Safe Reinforcement Learning Theory and its Applications, 2022 IEEE International Conference on Multi-sensor Fusion and Integration (MFI 2022)"
date: 2022-09-21
location: "Cranfield, United Kingdom"
---

Although the state-of-the-art learning approaches exhibit impressive results for dynamical systems, only a few applications on real physical systems have been presented. One major impediment is that the intermediate policy during the training procedure may result in behaviors that are not only harmful to the system itself but also to the environment. In essence, imposing safety guarantees for learning algorithms is vital for autonomous systems acting in the real world. In this talk, we discuss a computationally effective safe reinforcement learning (SRL) framework for complex dynamical systems that is based on model order reduction (MOR) techniques. With a proper definition of the safe region, a supervisory control strategy, which switches the actions applied on the system between the learning-based controller and a predefined corrective controller, is given. A simplified system, found by either using physically inspired or data-driven MOR, formulates a low-dimensional safe region that approximates the high-dimensional safe region of the original dynamical system. To ensure the performance of the learning-based controller, the belief of the safe region is updated online by using the observed actual system's behavior. The proposed SRL framework leads to a safer learning process, and provides a possible solution to the challenging problem of how to safely apply learning algorithms in real-world scenarios.