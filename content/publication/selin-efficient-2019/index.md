---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient Autonomous Exploration Planning of Large-Scale 3-D Environments
subtitle: ''
summary: ''
authors:
- Magnus Selin
- Mattias Tiger
- Daniel Duberg
- Fredrik Heintz
- Patric Jensfelt
tags:
- 3D exploration
- Motion planning
categories: []
date: '2019-04-01'
lastmod: 2022-04-09T00:48:24+02:00
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
publishDate: '2022-04-08T22:48:22.964014Z'
publication_types:
- '2'
abstract: Exploration is an important aspect of robotics, whether it is for mapping,
  rescue missions or path planning in an unknown environment. Frontier Exploration
  planning (FEP) and Receding Horizon Next-Best-View planning (RH-NBVP) are two different
  approaches with different strengths and weaknesses. FEP explores a large environment
  consisting of separate regions with ease, but is slow at reaching full exploration
  due to moving back and forth between regions. RH-NBVP shows great potential and
  efﬁciently explores individual regions, but has the disadvantage that it can get
  stuck in large environments not exploring all regions. In this work we present a
  method that combines both approaches, with FEP as a global exploration planner and
  RH-NBVP for local exploration. We also present techniques to estimate potential
  information gain faster, to cache previously estimated gains and to exploit these
  to efﬁciently estimate new queries.
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2019.2897343
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/8633925/
---
