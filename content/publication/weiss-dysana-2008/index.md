---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'DySANA: Dynamic Speech and Noise Adaptation for Voice Activity Detection'
subtitle: ''
summary: ''
authors:
- Ron J Weiss
- Trausti Kristjansson
tags: []
categories: []
date: '2008-01-01'
lastmod: 2021-05-19T04:58:07-07:00
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
publishDate: '2021-05-19T11:58:06.942181Z'
publication_types:
- '1'
abstract: We describe a method of simultaneusly tracking noise and speech levels for
  signal-to-noise ratio adaptive speech endpoint detection. The method is based on
  the Kalman ﬁlter framework with switching observations and uses a dynamic distribution
  that 1) limits the rate of change of these levels 2) enforces a range on the values
  for the two levels and 3) enforces a ratio between the noise and the signal levels.
  We call this a Lombard dynamic distribution since it encodes the expectation that
  a speaker will increase his or her vocal intensity in noise. The method also employs
  a state transition matrix which encodes a prior on the states and provides a continuity
  constraint. The new method provides 46.1% relative improvement in WER over a baseline
  GMM based endpointer at 20 dB SNR.
publication: '*Interspeech*'
---
