---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Voice and accompaniment separation in music using self-attention convolutional
  neural network
subtitle: ''
summary: ''
authors:
- Yuzhou Liu
- Balaji Thoshkahna
- Ali Milani
- Trausti Kristjansson
tags:
- '"Computer Science - Machine Learning"'
- '"Computer Science - Sound"'
- '"Electrical Engineering and Systems Science - Audio and Speech Processing"'
- '"Statistics - Machine Learning"'
categories: []
date: '2020-03-01'
lastmod: 2021-05-19T04:58:11-07:00
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
publishDate: '2021-05-19T11:58:11.148633Z'
publication_types:
- '2'
abstract: Music source separation has been a popular topic in signal processing for
  decades, not only because of its technical difﬁculty, but also due to its importance
  to many commercial applications, such as automatic karoake and remixing. In this
  work, we propose a novel self-attention network to separate voice and accompaniment
  in music. First, a convolutional neural network (CNN) with densely-connected CNN
  blocks is built as our base network. We then insert self-attention subnets at different
  levels of the base CNN to make use of the long-term intra-dependency of music, i.e.,
  repetition. Within self-attention subnets, repetitions of the same musical patterns
  inform reconstruction of other repetitions, for better source separation performance.
  Results show the proposed method leads to 19.5% relative improvement in vocals separation
  in terms of SDR. We compare our methods with state-of-the-art systems i.e. MMDenseNet
  [1] and MMDenseLSTM.[2].
publication: '*arXiv:2003.08954 [cs, eess, stat]*'
url_pdf: http://arxiv.org/abs/2003.08954
---
