---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Neural Network Based Time-Frequency Masking and Steering Vector Estimation
  for Two-Channel Mvdr Beamforming
subtitle: ''
summary: ''
authors:
- Yuzhou Liu
- Anshuman Ganguly
- Krishna Kamath
- Trausti Kristjansson
tags: []
categories: []
date: '2018-04-01'
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
publishDate: '2021-05-19T11:58:10.836636Z'
publication_types:
- '1'
abstract: We present a neural network based approach to two-channel beamforming. First,
  single- and cross-channel spectral features are extracted to form a feature map
  for each utterance. A large neural network that is the concatenation of a convolution
  neural network (CNN), long short-term memory recurrent neural network (LSTMRNN)
  and deep neural network (DNN) is then employed to estimate frame-level speech and
  noise masks. Later, these predicted masks are used to compute cross-power spectral
  density (CPSD) matrices which are used to estimate the minimum variance distortion-less
  response (MVDR) beamformer coefﬁcients. In the end, a DNN is trained to optimize
  the phase in the estimated steering vectors to make it robust for reverberant conditions.
  We compare our methods with two state-of-the-art two-channel speech enhancement
  systems, i.e., time-frequency masking and masking-based beamforming. Results show
  the proposed method leads to 21% relative improvement in word error rate (WER) over
  other systems.
publication: '*2018 IEEE International Conference on Acoustics, Speech and Signal
  Processing (ICASSP)*'
url_pdf: https://ieeexplore.ieee.org/document/8462069/
doi: 10.1109/ICASSP.2018.8462069
---
