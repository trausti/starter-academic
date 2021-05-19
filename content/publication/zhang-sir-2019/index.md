---
# Documentation: https://wowchemy.com/docs/managing-content/

title: SIR Beam Selector for Amazon Echo Devices Audio Front-End
subtitle: ''
summary: ''
authors:
- Xianxian Zhang
- Trausti Kristjansson
- Philip Hilmes
tags: []
categories: []
date: '2019-10-01'
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
publishDate: '2021-05-19T11:58:10.679164Z'
publication_types:
- '1'
abstract: The Audio Front-End (AFE) is a key component in mitigating acoustic environmental
  challenges for far-field automatic speech recognition (ASR) on Amazon Echo family
  of products. A critical component of the AFE is the Beam Selector, which identifies
  which beam points to the target user. In this paper, we proposed a new SIR beam
  selector that utilizes subband-based signal-to-interference ratios to learn the
  locations of the audio sources and therefore further improve the beam selection
  accuracy for multi-microphone based AFE system. We analyzed the performance of a
  Signal to Interference Ratio (SIR) beam selector with a comparison to classic beam
  selector using the datasets collected under various conditions. This method is evaluated
  and shown to simultaneously decrease word-error-rate (WER) for speech recognition
  by up to 46.20% and improve barge-in performance via FRR by up to 39.18%.
publication: '*2019 IEEE International Workshop on Signal Processing Systems (SiPS)*'
url_pdf: https://ieeexplore.ieee.org/document/9020406/
doi: 10.1109/SiPS47522.2019.9020406
---
