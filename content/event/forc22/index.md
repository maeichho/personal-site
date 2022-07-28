---
title: "Mind your Ps and Qs: Allocation with Priorities and Quotas"

event: The Symposium of Foundations of Responsible Computing (2022)
event_url: https://cmsa.fas.harvard.edu/2022-forc/

location: Harvard University CMSA
address:
  street: 20 Garden Street
  city: Cambridge
  region: MA
  postcode: '02138'
  country: United States

summary: We consider the problem of finding Pareto efficient allocations that adhere to quota, eligibility, and priority constraints. We show that this problem can be encoded as a weighted bipartite matching problem with carefully chosen weights. This framework provides us the flexibility to enforce additional criteria in our selected allocations, including notions of fairness.

abstract:  In many settings, such as university admissions, the rationing of medical supplies, and the assignment of public housing, decision-makers use normative criteria (ethical, financial, legal, etc.) to justify who gets an allocation. These criteria can often be translated into quotas for the number of units available to particular demographics and priorities over agents who qualify in each demographic. Each agent may qualify in multiple categories at different priority levels, so many allocations may conform to a given set of quotas and priorities. Which of these allocations should be chosen? In this talk, I’ll formalize this reserve allocation problem and motivate Pareto efficiency as a natural desideratum. I’ll present an algorithm to locate efficient allocations that conform to the quota and priority constraints. This algorithm relies on beautiful techniques from integer and linear programming, and it is both faster and more straightforward than existing techniques in this space. Moreover, its clean formulation allows for further refinement, such as the secondary optimization of some heuristics for fairness.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-06-06T00:00:00Z'
date_end: '2022-06-08T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-07-28T00:00:00Z'

authors: ["Siddhartha Banerjee","Matthew Eichhorn","David Kempe"]
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
#  - name: Slides
#    url: slides.pdf
  - name: PDF
    url: paper.pdf
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
