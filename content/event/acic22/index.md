---
title: Simple yet Efficient Estimators for Network Causal Inference Even When the Network is Unknown

event: American Causal Inference Conference (2022)
event_url: https://ctml.berkeley.edu/american-causal-inference-conference-2022

location: UC Berkeley
address:
  street: 2121 Berkeley Way West
  city: Berkeley
  region: CA
  postcode: '94704'
  country: United States

summary: We propose unbiased estimators for the total treatment effect in settings with network interference. We use a low-degree assumption on the potential outcomes to establish bounds on the variance of our estimators. In settings where the network is unknown, we leverage a staggered rollout experimental design. Beyond our formal guarantees, our estimators are shown to work well in our experiments on simulated data.

abstract:  Randomized experiments are widely used to estimate causal effects of proposed treatments in domains spanning the physical and biological sciences, social sciences, engineering, medicine and health, as well as in public service domains and the technology industry. However, classical approaches to experimental design rely on critical independence assumptions that are violated when the outcome of an individual may be affected by the treatment of another individual, referred to as network interference. This interference introduces computational and statistical challenges to causal inference. Our work focuses on estimating the Total Treatment Effect, informally described by the difference in average outcomes across the population when everyone versus no one is treated. We present a new hierarchy of low-degree polynomial potential outcomes models and unbiased estimators that enable statistically efficient and computationally simple solutions. When the network is completely unknown, we provide a simple estimator along with a staggered rollout randomized design which is unbiased and has low variance. To our knowledge, we are the first to propose a statistically grounded solution for the case where the underlying network is completely unknown. We evaluate the finite-sample performance of our proposed estimators relative to existing estimators on simulated data. Our proposed estimator has reduced mean squared error relative to previous approaches when the network is complex or unknown, or when the network interference effects are fully heterogeneous or nonlinear. Our approach also extends to other estimands and to settings beyond neighborhood interference.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-05-23T00:00:00Z'
date_end: '2022-05-25T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-07-28T00:00:00Z'

authors: ["Mayleen Cortez","Matthew Eichhorn","Christina Lee Yu"]
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

#links:
#  - name: Slides
#    url: slides.pdf

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
