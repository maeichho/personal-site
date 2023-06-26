---
title: "Exploiting Neighborhood Interference with Low Order Interactions under Unit Randomized Design"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mayleen Cortez-Rodriguez
- maeichho
- Christina Lee Yu

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2023-06-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: To appear in *Journal of Causal Inference*
publication_short: To appear in *JCI*

abstract: 'Network interference, where the outcome of an individual is affected by the treatment assignment of those in their social network, is pervasive in real-world settings. However, it poses a challenge to estimating causal effects. We consider the task of estimating the total treatment effect (TTE), or the difference between the average outcomes of the population when everyone is treated versus when no one is, under network interference. Under a Bernoulli randomized design, we provide an unbiased estimator for the TTE when network interference effects are constrained to low order interactions among neighbors of an individual. We make no assumptions on the graph other than bounded degree, allowing for well-connected networks that may not be easily clustered. We derive a bound on the variance of our estimator and show in simulated experiments that it performs well compared with standard estimators for the TTE. We also derive a minimax lower bound on the mean squared error of our estimator which suggests that the difficulty of estimation can be characterized by the degree of interactions in the potential outcomes model. We also prove that our estimator is asymptotically normal under boundedness conditions on the network degree and potential outcomes model. Central to our contribution is a new framework for balancing model flexibility and statistical complexity as captured by this low order interactions structure.'

# Summary. An optional shortened abstract.
summary: We consider estimating the total treatment effect (TTE) causal estimand in a setting with network interference. To model this interference, we introduce a potential outcomes framework where individuals receive additive effects for each sufficiently small subset of their neithborhood that is entirely exposed to a treatment. In this setting, we develop an unbiased estimator for TTE and reason about its variance. We validate our approach using experiments on simulated data.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/pdf/2208.05553.pdf

url_pdf: 'jci.pdf'
url_code: 'https://github.com/mayscortez/low-order-unitRD'
url_dataset: ''
url_poster: 'poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: ''
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

