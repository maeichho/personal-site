---
title: "Automated Survey of Selected Common Plant Species in Thai Homegardens Using Google Street View Imagery and a Deep Neural Network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- John Ringland
- Martha Bohm
- So-Ra Baek
- admin

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-01-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [Journal article]

# Publication name and optional abbreviated publication name.
publication: In *Earth Science Informatics*
publication_short: In *ESI*

abstract: Most previous studies of homegardens have used labor-intensive boots-on-the-ground plant surveys, owner questionnaires, and interviews, limiting them to at most a few hundred homegardens. We show that automated analysis of publicly available imagery can enable surveys of much greater scale that can augment these traditional data sources. Specifically, we demonstrate the feasibility of using the high-resolution street-level photographs in Google Street View and an object-detection network (RetinaNet) to create a large-scale high-resolution survey of the prevalence of at least six plant species widely grown in road-facing homegardens in Thailand. Our research team examined 4000 images facing perpendicular to the street and located within 10 m of a homestead, and manually outlined all perceived instances of eleven common plant species. A neural network trained on these tagged images was used to detect instances of these species in approximately 150,000 images constituting views of roughly one in every ten homesteads in five provinces of northern Thailand. The results for six of the plant species were visualized as heatmaps of both the average number of target species detected in each image and individual species prevalence, with spatial averaging performed at scales of 500 m and 2.5 km. Urban-rural contrasts in the average number of target species in each image are quantified, and large variations are observed even among neighboring villages. Spatial heterogeneity is seen to be more pronounced for banana and coconut than for other species. Star gooseberry and papaya are more frequently present immediately outside of towns while dracaena and mango persist into the cores of towns.

# Summary. An optional shortened abstract.
summary: We demonstrate the feasibility of using the high-resolution street-level photographs in Google Street View and an object-detection network (RetinaNet) to create a large-scale high-resolution survey of the prevalence of at least six plant species widely grown in road-facing homegardens in Thailand.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: SpringerLink
  url: https://link.springer.com/article/10.1007/s12145-020-00557-3

url_pdf: 'esi21.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
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

