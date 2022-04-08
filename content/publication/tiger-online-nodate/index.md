---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Online Sparse Gaussian Process Regression for Trajectory Modeling
subtitle: ''
summary: ''
authors:
- Mattias Tiger
- Fredrik Heintz
tags: []
categories: []
date: -01-01
lastmod: 2022-04-09T00:48:21+02:00
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
publishDate: '2022-04-08T22:48:20.763850Z'
publication_types:
- '1'
abstract: Trajectories are used in many target tracking and other fusion-related applications.
  In this paper we consider the problem of modeling trajectories as Gaussian processes
  and learning such models from sets of observed trajectories. We demonstrate that
  the traditional approach to Gaussian process regression is not suitable when modeling
  a set of trajectories. Instead we introduce an approach to Gaussian process trajectory
  regression based on an alternative way of combing two Gaussian process (GP) trajectory
  models and inverse GP regression. The beneﬁt of our approach is that it works well
  online and efﬁciently supports sophisticated trajectory model manipulations such
  as merging and splitting of trajectory models. Splitting and merging is very useful
  in spatio-temporal activity modeling and learning where trajectory models are considered
  discrete objects. The presented method and accompanying approximation algorithm
  have time and memory complexities comparable to state of the art of regular full
  and approximative GP regression, while having a more ﬂexible model suitable for
  modeling trajectories. The novelty of our approach is in the very ﬂexible and accurate
  model, especially for trajectories, and the proposed approximative method based
  on solving the inverse problem of Gaussian process regression.
publication: ''
---
