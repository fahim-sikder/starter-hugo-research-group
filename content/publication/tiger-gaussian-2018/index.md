---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Gaussian Process Based Motion Pattern Recognition with Sequential Local Models
subtitle: ''
summary: ''
authors:
- Mattias Tiger
- Fredrik Heintz
tags: []
categories: []
date: '2018-06-01'
lastmod: 2022-04-09T00:48:27+02:00
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
publishDate: '2022-04-08T22:48:26.310959Z'
publication_types:
- '1'
abstract: Conventional trajectory-based vehicular trafﬁc analysis approaches work
  well in simple environments such as a single crossing but they do not scale to more
  structurally complex environments such as networks of interconnected crossings (e.g.
  urban road networks). Local trajectory models are necessary to cope with the multi-modality
  of such structures, which in turn introduces new challenges. These larger and more
  complex environments increase the occurrences of lack of motion and self-overlaps
  in observed trajectories which impose further challenges. In this paper we consider
  the problem of motion pattern recognition in the setting of sequential local motion
  pattern models. That is, classifying sub-trajectories from observed trajectories
  in accordance with which motion pattern that best explains it. We introduce a Gaussian
  process (GP) based modeling approach which outperforms the stateof-the-art GP based
  motion pattern approaches at this task. We investigate the impact of varying local
  model overlap and the length of the observed trajectory trace on the classiﬁcation
  quality. We further show that introducing a pre-processing step ﬁltering out stops
  from the training data signiﬁcantly improves the classiﬁcation performance. The
  approach is evaluated using real GPS position data from city buses driving in urban
  areas.
publication: '*2018 IEEE Intelligent Vehicles Symposium (IV)*'
doi: 10.1109/IVS.2018.8500676
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/8500676/
---
