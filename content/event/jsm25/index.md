---
title: "Combining Rollout Designs and Clustering for Causal Inference under Low-order Interference"

event: Joint Statistical Meeting (2025)
event_url: https://ww2.amstat.org/meetings/jsm/2025/

location: Music City Center
address: 
  street: 201 Rep. John Lewis Way S
  city: Nashville
  region: TN
  postcode: '37203'
  country: United States

summary: I'll introduce a two-stage rollout design to mitigate the high variance from extrapolation in interpolation-based estimators for the total treatment effect under unknown network interference. Then, I'll quantify the bias and variance of this estimator as a function of a clustering used in the two-stage design and illustrate their trade-off through a series of experiments.

abstract: Estimating causal effects under interference is pertinent to many real-world settings. Recent work with low-order potential outcomes models uses a rollout design to obtain unbiased estimators that require no interference network information. However, the required extrapolation can lead to prohibitively high variance. To address this, we propose a two-stage experiment that selects a sub-population in the first stage and restricts treatment rollout to this sub-population in the second stage. We explore the role of clustering in the first stage by analyzing the bias and variance of a polynomial interpolation-style estimator under this experimental design. Bias increases with the number of edges cut in the clustering of the interference network, but variance depends on qualities of the clustering that relate to homophily and covariate balance. There is a tension between clustering objectives that minimize the number of cut edges versus those that maximize covariate balance across clusters. Through simulations, we explore a bias-variance trade-off and compare the performance of the estimator under different clustering strategies.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-08-03T14:00:00Z'
#date_end: '2022-10-18T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-08-04T00:00:00Z'

authors: ["Mayleen Cortez-Rodriguez",admin,"Christina Lee Yu"]
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
  - name: Slides
    url: slides.pdf
#   - name: PDF
#     url: paper.pdf
  - name: arXiv
    url: https://arxiv.org/abs/2405.05119

url_code: ''
url_pdf: ''
url_slides: 'slides.pdf'
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---
