---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently an Assistant Professor in the Department of Electromechanical Engineering at [University of Macau](https://www.um.edu.mo/). My research interests include:

* Learning-based control and optimal control
* Dexterous manipulation, robot control, and motion planning
* RL/ML in robotics, imitation learning, and transfer learning
* Embodied AI for robotic systems
* Safety analysis for AI-driven robotic system

I am focused on developing intelligent and robust AI-enabled autonomous and robotic systems with safety and reliability guarantees, ensuring their applicability to a wide range of complex real-world tasks and scenarios. Prior to joining the University of Macau, I was a Postdoctoral Research Fellow in the Department of Electrical and Computer Engineering at [University of Alberta](https://www.ualberta.ca/index.html) from 2022 to 2025, under the mentorship of Prof. Lei Ma and Prof. Zhan Shu. I received my Ph.D. from the [Technical University of Munich](https://www.tum.de/) in 2022, where I specialized in automatic control and robotics under the supervision of Prof. Martin Buss.

Available Positions:
======
<b>Seeking exceptional Ph.D., Master's, and Research Assistant (RA) candidates passionate about robotics research.</b> We are looking for highly motivated students with strong academic backgrounds and a drive to tackle cutting-edge challenges in robotics. Competitive funding/support is available for outstanding applicants. Feel free to reach me at <u>zhzhou@um.edu.mo</u>!

News
======
* <b>08/2025:</b> I joined the Department of Electromechanical Engineering at <b>University of Macau</b> as an <b>Assistant Professor</b>. 
* <b>06/2025:</b> Our paper "<i>VLATest: Testing and Evaluating Vision-Language-Action Models for Robotic Manipulation</i>" was presented at <b>ACM FSE 2025</b>!
* <b>01/2025:</b> Our paper "<i>Multilingual Blending: LLM Safety Alignment Evaluation with Language Mixture</i>" was accpeted by <b>NAACL 2025</b>!
* <b>11/2024:</b> Our paper "<i>GenSafe: A Generalizable Safety Enhancer for Safe Reinforcement Learning Algorithms Based on Reduced Order Markov Decision Process Model</i>" was published on <b>IEEE Transactions on Neural Networks and Learning Systems</b>!
* <b>06/2024:</b> We gave a tutorial on "<i>Quality Assurance for Autonomous Driving Systems: A Software Engineering Perspective</i>" at <b>Autoware Tutorial, IEEE IV 2024</b>.
* <b>05/2024:</b> Our paper "<i>ISR-LLM: Iterative Self-Refined Large Language Model for Long-Horizon Sequential Task Planning</i>" was presented at <b>IEEE ICRA 2024</b>!
* <b>03/2024:</b> Our paper "<i>Towards Building AI-CPS with Nvidia Isaac Sim: An Industrial Benchmark and Case Study for Robotics Manipulation</i>" was presented at <b>IEEE/ACM ICSE-SEIP 2024</b>!
* <b>02/2024:</b> Our paper "<i>Enabling Versatility and Dexterity of the Dual-Arm Manipulators: A General Framework Toward Universal Cooperative Manipulation</i>" was published on <b>IEEE Transactions on Robotics</b>!
* <b>10/2022:</b> Our paper "<i>Off-Policy Risk-Sensitive Reinforcement Learning-Based Constrained Robust Optimal Control</i>" was published on <b>IEEE Transactions on Systems, Man, and Cybernetics: Systems</b>!
* <b>09/2022:</b> I gave a talk on "<i>Safe Reinforcement Learning with Model Order Reduction Techniques</i>" at <b>The 1st International Workshop on Safe Reinforcement Learning Theory and its Applications, IEEE MFI 2022</b>.
* <b>07/2022:</b> I joined the Department of Electrical and Computer Engineering at <b>University of Alberta</b> as a <b>Postdoctoral Research Fellow</b>. 
* <b>07/2022:</b> I received my <b>Ph.D.</b> degree from the <b>Chair of Automatic Control Engineering (LSR)</b> at the <b>Technical University of Munich (TUM)</b>, supervised by Prof. Martin Buss.
* <b>09/2021:</b> Our paper "<i>Learning a Low-Dimensional Representation of a Safe Region for Safe Reinforcement Learning on Dynamical Systems</i>" was published on <b>IEEE Transactions on Neural Networks and Learning Systems</b>!
* <b>06/2020:</b> Our paper "<i>A General Framework to Increase Safety of Learning Algorithms for Dynamical Systems Based on Region of Attraction Estimation</i>" was published on <b>IEEE Transactions on Robotics</b>!

Featured Publications
======
{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.highlight == 'yes' %}
    {% include archive-single_double.html %}
  {% endif %}
{% endfor %}


