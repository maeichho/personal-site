---
title: "Online Allocation with Priorities and Quotas"

event: INFORMS Annual Meeting (2023)
event_url: https://meetings.informs.org/wordpress/phoenix2023/

location: Phoenix Convention Center
address: 
  street: 100 N 3rd St
  city: Phoenix
  region: AZ
  postcode: '85004'
  country: United States

summary: We consider the problem of online allocation, where irrevocable decisions whether to allocate to agents must be made before all agents have been observed, in settings with priority and quota constraints, By leveraging structure from an offline variant of this problem, we develop a policy for which the sum of the efficiency loss (number of unallocated resource units) and priority loss (number of higher-priority agents who are blocked from an allocation by lower-priority agents) is constant with respect to the input size.

abstract: 'In online applications such as the rationing of medical care, the decision of who is treated is justified by various ethical, financial, and legal criteria. We build upon recent work on priority respecting allocations, adapting the model to an online setting. We highlight the fundamental trade-off between an allocation mechanism’s efficiency, its assurance that goods are allocated to the greatest extent, and its adherence to pre-defined notions of priority. In particular, in a setting with T online arrivals, we show that while insisting on zero priority violations leads to an Ω(T) loss in efficiency, one can design policies ensuring that the sum of the efficiency loss and priority violations is Ο(1) under mild regularity conditions.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-10-16T14:15:00Z'
#date_end: '2022-10-18T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-10-17T00:00:00Z'

authors: [admin,"Siddhartha Banerjee","David Kempe"]
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
    url: https://arxiv.org/abs/2204.13019

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
