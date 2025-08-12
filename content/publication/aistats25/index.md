---
title: "Analysis of Two-Stage Rollout Designs with Clustering for Causal Inference under Network Interference"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mayleen Cortez-Rodriguez
- admin
- Christina Lee Yu

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-05-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [Conference paper]

# Publication name and optional abbreviated publication name.
publication: In *Artificial Intelligence and Statistics*
publication_short: In *AISTATS*

abstract: Estimating causal effects under interference is pertinent to many real-world settings. Recent work with low-order potential outcomes models uses a rollout design to obtain unbiased estimators that require no interference network information. However, the required extrapolation can lead to prohibitively high variance. To address this, we propose a two-stage experiment that selects a sub-population in the first stage and restricts treatment rollout to this sub-population in the second stage. We explore the role of clustering in the first stage by analyzing the bias and variance of a polynomial interpolation-style estimator under this experimental design. Bias increases with the number of edges cut in the clustering of the interference network, but variance depends on qualities of the clustering that relate to homophily and covariate balance. There is a tension between clustering objectives that minimize the number of cut edges versus those that maximize covariate balance across clusters. Through simulations, we explore a bias-variance trade-off and compare the performance of the estimator under different clustering strategies.

# Summary. An optional shortened abstract.
summary: Causal inference under network interference is made more challenging when the interference network is not fully known to the practitioner. An existing approach for this problem leverages polynomial interpolation over multiple experimental periods to estimate the total treatment effect, but experiences high variance due to extrapolation in higher-order potential outcomes models. We design a two-stage staggered rollout design and an accompanying total treatment effect estimator that reduces the magnitude of variance due to extrapolation in exchange for some bias. We quantify this bias-variance trade-off and illustrate the performance of our estimator in a variety of experiments. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2405.05119

url_pdf: 'aistats25.pdf'
url_code: 'https://github.com/mayscortez/two-stage-rollout-2025'
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

