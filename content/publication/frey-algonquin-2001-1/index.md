---
# Documentation: https://wowchemy.com/docs/managing-content/

title: ALGONQUIN - Learning Dynamic Noise Models From Noisy Speech for Robust Speech
  Recognition
subtitle: ''
summary: ''
authors:
- Brendan J Frey
- Trausti T Kristjansson
- Li Deng
- Alex Acero
tags: []
categories: []
date: '2001-01-01'
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
publishDate: '2021-05-19T11:58:11.463622Z'
publication_types:
- '2'
abstract: A challenging, unsolved problem in the speech recognition community is recognizing
  speech signals that are corrupted by loud, highly nonstationary noise. One approach
  to noisy speech recognition is to automatically remove the noise from the cepstrum
  sequence before feeding it in to a clean speech recognizer. In previous work published
  in Eurospeech, we showed how a probability model trained on clean speech and a separate
  probability model trained on noise could be combined for the purpose of estimating
  the noisefree speech from the noisy speech. We showed how an iterative 2nd order
  vector Taylor series approximation could be used for probabilistic inference in
  this model. In many circumstances, it is not possible to obtain examples of noise
  without speech. Noise statistics may change significantly during an utterance, so
  that speechfree frames are not sufficient for estimating the noise model. In this
  paper, we show how the noise model can be learned even when the data contains speech.
  In particular, the noise model can be learned from the test utterance and then used
  to denoise the test utterance. The approximate inference technique is used as an
  approximate E step in a generalized EM algorithm that learns the parameters of the
  noise model from a test utterance. For both Wall Street J ournal data with added
  noise samples and the Aurora benchmark, we show that the new noise adaptive technique
  performs as well as or significantly better than the non-adaptive algorithm, without
  the need for a separate training set of noise examples.
publication: '*NeurIPS*'
---
