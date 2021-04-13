---
title: "On Universal Black-Box Domain Adaptation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yabin Zhang
- Hui Tang
- Changxing Ding
- Kui Jia

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-04-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arVix*
publication_short: In *arVix*

abstract: In this paper, we study an arguably least restrictive setting of domain adaptation in a sense of practical deployment, where only the interface of source model is available to the target domain, and where the label-space relations between the two domains are allowed to be different and unknown. We term such a setting as Universal Black-Box Domain Adaptation (UB$^2$DA). The great promise that UB$^2$DA makes, however, brings significant learning challenges, since domain adaptation can only rely on the predictions of unlabeled target data in a partially overlapped label space, by accessing the interface of source model. To tackle the challenges, we first note that the learning task can be converted as two subtasks of in-class (In this paper we use in-class (out-class) to describe the classes observed (not observed) in the source black-box model) discrimination and out-class detection, which can be respectively learned by model distillation and entropy separation. We propose to unify them into a self-training framework, regularized by consistency of predictions in local neighborhoods of target samples. Our framework is simple, robust, and easy to be optimized. Experiments on domain adaptation benchmarks show its efficacy. Notably, by accessing the interface of source model only, our framework outperforms existing methods of universal domain adaptation that make use of source data and/or source models, with a newly proposed (and arguably more reasonable) metric of H-score, and performs on par with them with the metric of averaged class accuracy.

# Summary. An optional shortened abstract.
summary: arVix, 2021

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2104.04665.pdf'
url_code: 'https://github.com/Gorilla-Lab-SCUT/UB2DA'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
