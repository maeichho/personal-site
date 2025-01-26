---
title: "Causal Inference under Low-Order Interference"

event: Statistical Inference for Network Models (2024)
event_url: https://sinm.network/assets/sinm2024/

location: Québec City Convention Center
address: 
  street: 1000 Bd René-Lévesque E
  city: Québec
  region: QC
  postcode: 'G1R 5T8'
  country: Canada

summary: Interference effects, where the treatment of one individual has an effect on the outcome of another, are pervasive in real-world settings but violate assumptions of many classical causal estimators. While the Horvitz-Thompson estimator can account for interference, it has prohibitively high variance. In this talk, we'll survey recent approaches to improve on this variance guarantee by imposing additional structural assumptions on the potential outcomes model or the interference network. Then, I'll introduce a class of estimators, pseudoinverse estimators, that can be adapted to any experimental design and have strong bias and variance guarantees. Finally, I'll show how theoretical bounds on the performance of the pseudoinverse estimator can provide practical advice when selecting an experimental design.

abstract: 'In many settings, we are interested in quantifying how a population will be affected by some global treatment: how will a vaccination campaign affect the rate of infection; how will the adoption of a new recommendation algorithm influence engagement on an online platform; will increased revenues driven by an advertising campaign be sufficient to offset its cost? To answer these questions, practitioners carry out randomized experiments and use the results to estimate a causal quantity known as the total treatment effect (TTE). In the presence of network interference, where the treatment of some individuals can spill over and affect the outcomes of their untreated peers, the classical Horvitz-Thompson TTE estimator has prohibitively high variance. To address this, existing literature largely falls into one of two disjoint approaches: imposing structural assumptions on individuals’ potential outcomes which can be leveraged by more sophisticated estimators, or imposing structural assumptions on the interference network which can be leveraged by more sophisticated experimental designs. Our work is one of the first to consider these approaches in tandem.
 
I’ll posit a low-order interactions structure on the potential outcomes model that stipulates that individuals’ outcomes can be decomposed into additive effects from small treated subsets of their social neighbors. This assumption can be leveraged to design a TTE estimator, the Pseudoinverse (PI) estimator, that can be adapted to data collected under an arbitrary experimental design. Specializing to Bernoulli randomized designs, I’ll obtain a closed form for this estimator and demonstrate both theoretically and empirically that this estimator outperforms other existing approaches. Next, for an arbitrary experimental design, I’ll derive novel bias and variance bounds for the PI estimator in terms of properties of that design. Under graph cluster randomized (GCR) designs, these bounds illustrate a “best of both worlds” trade-off of the PI estimator: its variance scales as the smaller of the variance obtained from a low-order assumption and the variance obtained from cluster randomization, showing that combining these variance reduction strategies is preferable to using either individually. Finally, I’ll show the bias and variance bounds provide a principled approach for selecting a clustering to use for an experiment. Across a range of graphs and clustering algorithms, this method consistently selects clusterings that perform well on a range of potential outcomes models, suggesting that our bounds are useful to practitioners.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-06-17T13:30:00Z'
#date_end: '2022-10-18T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-06-18T00:00:00Z'

authors: [admin,"Samir Khan","Mayleen Cortez-Rodriguez","Johan Ugander","Christina Lee Yu"]
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
#   - name: Slides
#     url: slides.pdf
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
