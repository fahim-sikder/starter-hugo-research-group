---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Enhancing Lattice-based Motion Planning with Introspective Learning and Reasoning
subtitle: ''
summary: ''
authors:
- Mattias Tiger
- David Bergstrom
- Andreas Norrstig
- Fredrik Heintz
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-04-09T00:48:29+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-04-08T22:48:28.420725Z'
publication_types:
- '2'
abstract: Lattice-based motion planning is a hybrid planning method where a plan is
  made up of discrete actions, while simultaneously also being a physically feasible
  trajectory. The planning takes both discrete and continuous aspects into account,
  for example action pre-conditions and collision-free action-duration in the conﬁguration
  space. Safe motion planning rely on wellcalibrated safety-margins for collision
  checking. The trajectory tracking controller must further be able to reliably execute
  the motions within this safety margin for the execution to be safe. In this work
  we are concerned with introspective learning and reasoning about controller performance
  over time. Normal controller execution of the different actions is learned using
  machine learning techniques with explicit uncertainty quantiﬁcation, for safe usage
  in safety-critical applications. By increasing the model accuracy the safety margins
  can be reduced while maintaining the same safety as before. Reasoning takes place
  to both verify that the learned models stays safe and to improve collision checking
  effectiveness in the motion planner using more accurate execution predictions with
  a smaller safety margin. The presented approach allows for explicit awareness of
  controller performance under normal circumstances, and detection of incorrect performance
  in abnormal circumstances. Evaluation is made on the nonlinear dynamics of a quadcopter
  in 3D using simulation.
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2021.3068550
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9385931/
---
