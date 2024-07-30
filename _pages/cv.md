---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* <b>08/2017 - 07/2022:</b> <b>Ph.D.</b> in Electrical and Computer Engineering (Automatic Control and Robotics), <i>Technical University of Munich</i>, Munich, Germany 
* <b>10/2014 - 03/2017:</b> <b>M.Sc.</b> in Electrical and Computer Engineering, <i>Technical University of Munich</i>, Munich, Germany 
* <b>09/2010 - 07/2014:</b> <b>B.Eng.</b> in Mechatronics Engineering, <i>Tongji University</i>, Shanghai, PR China

Work experience
======
* <b>07/2022 - Current:</b> <b>Postdoctoral Research Fellow</b> at <i>University of Alberta</i>
  * Advisors: Assoc. Prof. Lei Ma, Prof. Zhan Shu
  * Developing AI-enabled robotic systems and cyper-physical systems with safety and reliability guarantees

* <b>08/2017 - 03/2022:</b> <b>Research Associate (Scientific Employee)</b> at <i>Technical University of Munich</i>
  * Advisor: Univ. Prof. Dr.-Ing./Univ. Tokio habil. Martin Buss
  * Designed general safe reinforcement learning approaches and AI-based control frameworks for robotic systems

* <b>11/2016 - 06/2017:</b> <b>Research Intern</b> at <i>Technical University of Munich</i>
  * Advisor: PD Dr.-Ing. habil. Dirk Wollherr
  * Designed learning-based human motion prediction framework for safe human-robot interaction in close-proximity

Research Projects and Collaborations
======
* <b>2024 - Current:</b> <b>Quality and Safety Assurance for AI-enabled Autonomous Driving Systems</b> at <i>University of Alberta</i>
  * Advisor: Assoc. Prof. Lei Ma
  * Developing AI-based perception and control modules for autonomous driving systems
  * Integrating quality and safety assurance into AI-enabled autonomous driving systems

* <b>2024 - Current:</b> <b>AI-enabled Resilient Grid for Clean Energy Integration</b> at <i>University of Alberta</i>
  * Advisors: Assoc. Prof. Lei Ma, Prof. Zhan Shu
  * Investigating the application of AI approaches in power grids and energy systems
  * Developing a testing and evaluation framework for AI-enabled energy systems

* <b>2023 - Current:</b> <b>Application of Foundation Models in Robotics with Safety Assurance</b> at <i>University of Alberta</i>
  * Advisors: Assoc. Prof. Lei Ma, Prof. Zhan Shu
  * Developing intelligent robotic systems guided by foundation models, e.g., Large Language Models (LLMs)
  * Incorporating safety assurance to robotic systems controlled by cutting-edge AI methods

* <b>2022 - 2023:</b> <b>Safety and Reliability Assurance of Next Generation AI-enabled Cyber-Physical Systems (AI-CPSs) for Energy Systems</b> at <i>University of Alberta</i>
  * Advisors: Assoc. Prof. Lei Ma, Prof. Zhan Shu
  * Developed safety analysis approaches for AI-CPSs across various application domains
  * Evaluated the performance and reliability of AI components in CPSs

* <b>2022 - 2023:</b> <b>Benchmarking and Evaluating AI-enabled Cyber-Physical Systems (AI-CPSs) for Robotic Manipulation</b> at <i>University of Alberta</i>
  * Advisors: Assoc. Prof. Lei Ma, Prof. Zhan Shu
  * Developed a benchmark and an evaluation framework for AI-CPSs in robotic manipulation using NVIDIA Isaac Sim
  * Conducted performance and safety analysis for AI-CPSs in diverse robotic manipulation tasks

* <b>2020 - 2021:</b> <b>AI-based Control Framework for Dual-Arm Robotic Manipulator System</b> at <i>Technical University of Munich</i>
  * Advisor: Univ. Prof. Dr.-Ing./Univ. Tokio habil. Martin Buss
  * Proposed an AI-based control framework for dual-arm robots, covering the entire perception-planning-control pipeline
  * Applied to various real-world dual-arm manipulation tasks

* <b>2018 - 2020:</b> <b>Safe Reinforcement Learning for Dynamical and Robotic Systems</b> at <i>Technical University of Munich</i>
  * Advisor: Univ. Prof. Dr.-Ing./Univ. Tokio habil. Martin Buss
  * Proposed general safe reinforcement learning frameworks for complex dynamical and robotic systems
  * Applied to diverse robotic systems, including UAVs, robotic manipulators, humanoids, and mobile robots

* <b>2016 - 2017:</b> <b>Understanding and Predicting Human Reaching Motions for Safe Close-Proximity Human-Robot Interaction</b> at <i>Technical University of Munich</i>
  * Advisor: PD Dr.-Ing. habil. Dirk Wollherr
  * Designed a learning-based human motion prediction framework for safe human-robot interaction in close-proximity
  * Validated and applied to real-world assembly tasks

Publications
======

<h2>Journal</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Conference</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Preprint</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
