---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ALGONQUIN: Iterating Laplace’s Method to Remove Multiple Types of Acoustic
  Distortion for Robust Speech Recognition'
subtitle: ''
summary: ''
authors:
- Brendan J Frey
- Li Deng
- Alex Acero
- Trausti Kristjansson
tags: []
categories: []
date: '2001-01-01'
lastmod: 2021-05-19T04:58:09-07:00
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
publishDate: '2021-05-19T11:58:09.576692Z'
publication_types:
- '1'
abstract: One approach to robust speech recognition is to use a simple speech model
  to remove the distortion, before applying the speech recognizer. Previous attempts
  at this approach have relied on unimodal or point estimates of the noise for each
  utterance. In challenging acoustic environments, e.g., an airport, the spectrum
  of the noise changes rapidly during an utterance, making a point estimate a poor
  representation. We show how an iterative form of Laplace’s method can be used to
  estimate the clean speech, using a time-varying probability model of the log-spectra
  of the clean speech, noise and channel distortion. We use this method, called ALGONQUIN,
  to denoise speech features and then feed these features into a large vocabulary
  speech recognizer whose WER on the clean Wall Street Journal data is 4.9%. When
  10 dB of noise consisting of an airplane engine shutting down is added to the data,
  the recognizer obtains a WER of 28.8%. ALGONQUIN reduces the WER to 12.6%, well
  below the WER of 25.0% obtained by our spectral subtraction algorithm, and close
  to the WER of 9.7% obtained by the slow procedure of retraining the recognizer on
  training data corrupted by the exact same noise. In fact, if ALGONQUIN is used to
  denoise the noisy training data before the recognizer is retrained, the WER is improved
  to 8.5%. For 10 dB of additive uniform white noise, our spectral subtraction algorithm
  reduces the WER from 55.1% to 33.8%. ALGONQUIN reduces the WER to 14.2%. The recognizer
  trained on noisy data obtains a WER of 14%, whereas the recognizer trained on noisy
  data denoised by ALGONQUIN obtains a WER of 9.9%.
publication: '*Eurospeech*'
---
