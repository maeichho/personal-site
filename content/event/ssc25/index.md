---
title: "Combining Design and Analysis for Causal Inference under Network Interference"

event: Statistical Society of Canada Annual Meeting (2025)
event_url: https://ssc.ca/en/meetings/annual/2025-ssc-annual-meeting-saskatoon

location: University of Saskatchewan
address: 
  street: 107 Wiggins Rd
  city: Saskatoon
  region: SK
  postcode: 'S7N 2Z4'
  country: Canada

summary: Interference effects, where the treatment of one individual has an effect on the outcome of another, are pervasive in real-world settings but violate assumptions of many classical causal estimators. While the Horvitz-Thompson estimator can account for interference, it has prohibitively high variance. In this talk, we'll survey recent approaches to improve on this variance guarantee by imposing additional structural assumptions on the potential outcomes model or the interference network. Then, I'll introduce a class of estimators, pseudoinverse estimators, that can be adapted to any experimental design and have strong bias and variance guarantees. For the setting of cluster randomized designs, I'll quantify the bias and variance as functions of the selected clustering.

abstract: 'In settings from public health to advertising, practitioners use randomized experiments to estimate the causal effect of a population-wide rollout of a new treatment. Traditional estimators that account for interference (where the treatment of one individual can affect the outcome of another) often have prohibitively high variance. Recent literature provides two, largely disjoint, techniques to address this: leveraging parametric assumptions on the potential outcomes to design better estimators and leveraging structural assumptions on the interference to choose a smarter experimental design. Combining these approaches, we present a pseudoinverse estimator for the total treatment effect in low-order outcome models when the data are collected under general experimental designs. For cluster randomized designs, we show this estimator is unbiased with variance scaling like the smaller of the variance obtained from a low-order assumption and the variance obtained from cluster randomization.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-05-26T14:00:00Z'
#date_end: '2022-10-18T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-05-27T00:00:00Z'

authors: [admin,"Samir Khan","Johan Ugander","Christina Lee Yu"]
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
    url: https://arxiv.org/abs/2405.07979

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
