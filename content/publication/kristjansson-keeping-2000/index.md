---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Keeping ﬂexible active contours on track using Metropolis updates
subtitle: ''
summary: ''
authors:
- Trausti T Kristjansson
- Brendan J Frey
tags: []
categories: []
date: '2000-01-01'
lastmod: 2021-05-19T04:58:10-07:00
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
publishDate: '2021-05-19T11:58:10.049302Z'
publication_types:
- '2'
abstract: Condensation, a form of likelihood-weighted particle ﬁltering, has been
  successfully used to infer the shapes of highly constrained “active” contours in
  video sequences. However, when the contours are highly ﬂexible (e.g. for tracking
  ﬁngers of a hand), a computationally burdensome number of particles is needed to
  successfully approximate the contour distribution. We show how the Metropolis algorithm
  can be used to update a particle set representing a distribution over contours at
  each frame in a video sequence. We compare this method to condensation using a video
  sequence that requires highly ﬂexible contours, and show that the new algorithm
  performs dramatically better that the condensation algorithm. We discuss the incorporation
  of this method into the “active contour” framework where a shape-subspace is used
  constrain shape variation.
publication: '*NeurIPS*'
---
