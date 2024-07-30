---
title: "Guided Sequential Manipulation Planning Using a Hierarchical Policy"
collection: publications
permalink: /publication/2020guided
authorlist: 'Hoai My Van, Ozgur S Oguz, <b>Zhehua Zhou</b>, Marc Toussaint'
excerpt: 'In this work, we introduce a hierarchical policy structure that selects high-level actions for effective task and motion planning (TAMP) in sequential manipulation tasks.'
date: 2020-06-01
venue: 'Robotics: Science and Systems (RSS) Conference 2020 - Learning in Task and Motion Planning Workshop'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.academia.edu/download/99743486/20-oz-RSSws-ltamp.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
pubtype: 'conference'
highlight: 'no'
---

We introduce a hierarchical policy structure that selects high-level actions for effective task and motion planning (TAMP) in sequential manipulation tasks. For such problems, scalability of the methods is a major challenge, due to the combinatorial complexity of possible discrete decisions. To overcome this, we propose to learn an upper-level policy that selects the next manipulation action, and a lower-level policy that decides on the end-effector and objects to be involved in the action given the encoded current state. We demonstrate the generalizability of our approach in various pick-and-place experiments. We further show that the time and space complexity is significantly reduced compared to a state-of-the-art TAMP framework especially for tasks involving many objects.