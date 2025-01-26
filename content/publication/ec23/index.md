---
title: "Allocating with Priorities and Quotas: Algorithms, Complexity, and Dynamics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Siddhartha Banerjee
- admin
- David Kempe

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2023-07-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [Conference paper]

# Publication name and optional abbreviated publication name.
publication: In *Economics and Computation*
publication_short: In *EC*

abstract: 'In many applications such as rationing medical care and supplies, university admissions, and the assignment of public housing, the decision of who receives an allocation can be justified by various normative criteria (ethical, financial, legal, etc.). Such settings have motivated the following priority-respecting allocation problem: several categories, each with a quota of interchangeable items, wish to allocate the items among a set of agents. Each category has a list of eligible agents and a priority ordering over these agents; agents may be eligible in multiple categories. The goal is to select a valid allocation: one that respects quotas, eligibility, and priorities and ensures Pareto efficiency.  
We provide a complete algorithmic characterization of all valid allocations, exhibiting a bijection between sets of agents who can be allocated and maximum-weight matchings under carefully chosen rank-based weights. While prior work provides a polynomial-time algorithm to locate a valid allocation, our characterization admits a simpler algorithm that enables two wide-reaching extensions:

1. Selecting valid allocations that satisfy additional criteria: Via three examples -- inclusion/exclusion of some chosen agent; agent-side Pareto efficiency vs. welfare maximization; and fairness from the perspective of allocated vs. unallocated agents -- we show that finding priority-respecting allocations subject to some secondary constraint straddles a complexity knife-edge; in each example, one problem variant can be solved efficiently, while a closely related variant is NP-hard. 

2. Efficiency-envy tradeoffs in dynamic allocation: In settings where allocations must be made to T agents arriving sequentially via some stochastic process, we show that while insisting on zero priority violations leads to an Omega(T) loss in efficiency, one can design allocation policies ensuring that the sum of the efficiency loss and priority violations in hindsight is O(1) (under mild regularity conditions on the arrival process).'

# Summary. An optional shortened abstract.
summary: We consider a setting where resource units are allocated to unit demand agents through reserved categories. Valid allocations must respect quotas, eligibility requirements, and priority constraints in each category and be Pareto efficient. We give a characterization of all valid allocations as solutions to a family of LPs. We use this characterization to study the complexity of many related problems and to give a constant-loss algorithm for an online variant. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2204.13019

url_pdf: 'ec23.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'slides.pdf' 
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

