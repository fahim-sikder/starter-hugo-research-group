---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Receding-Horizon Lattice-Based Motion Planning with Dynamic Obstacle Avoidance
subtitle: ''
summary: ''
authors:
- Olov Andersson
- Oskar Ljungqvist
- Mattias Tiger
- Daniel Axehill
- Fredrik Heintz
tags:
- Motion planning
- Trajectory generation
- Trajectory tracking
categories: []
date: '2018-12-01'
lastmod: 2022-04-09T00:48:28+02:00
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
publishDate: '2022-04-08T22:48:27.400461Z'
publication_types:
- '1'
abstract: A key requirement of autonomous vehicles is the capability to safely navigate
  in their environment. However, outside of controlled environments, safe navigation
  is a very difﬁcult problem. In particular, the real-world often contains both complex
  3D structure, and dynamic obstacles such as people or other vehicles. Dynamic obstacles
  are particularly challenging, as a principled solution requires planning trajectories
  with regard to both vehicle dynamics, and the motion of the obstacles. Additionally,
  the real-time requirements imposed by obstacle motion, coupled with real-world computational
  limitations, make classical optimality and completeness guarantees difﬁcult to satisfy.
  We present a uniﬁed optimizationbased motion planning and control solution, that
  can navigate in the presence of both static and dynamic obstacles. By combining
  optimal and receding-horizon control, with temporal multi-resolution lattices, we
  can precompute optimal motion primitives, and allow real-time planning of physically-feasible
  trajectories in complex environments with dynamic obstacles. We demonstrate the
  framework by solving difﬁcult indoor 3D quadcopter navigation scenarios, where it
  is necessary to plan in time. Including waiting on, and taking detours around, the
  motions of other people and quadcopters.
publication: '*2018 IEEE Conference on Decision and Control (CDC)*'
doi: 10.1109/CDC.2018.8618964
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/8618964/
---
