---
title: "Counterfactual Supervision-Based Information Bottleneck for Out-of-Distribution Generalization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kui Jia

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-08-16T00:00:00Z"
doi: "https://doi.org/10.3390/e25020193"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Entropy*
publication_short: In *Entropy*

abstract: Learning invariant (causal) features for out-of-distribution (OOD) generalization have attracted extensive attention recently, and among the proposals, invariant risk minimization (IRM) is a notable solution. In spite of its theoretical promise for linear regression, the challenges of using IRM in linear classification problems remain. By introducing the information bottleneck (IB) principle into the learning of IRM, the IB-IRM approach has demonstrated its power to solve these challenges. In this paper, we further improve IB-IRM from two aspects. First, we show that the key assumption of support overlap of invariant features used in IB-IRM guarantees OOD generalization, and it is still possible to achieve the optimal solution without this assumption. Second, we illustrate two failure modes where IB-IRM (and IRM) could fail in learning the invariant features, and to address such failures, we propose a Counterfactual Supervision-based Information Bottleneck (CSIB) learning algorithm that recovers the invariant features. By requiring counterfactual inference, CSIB works even when accessing data from a single environment. Empirical experiments on several datasets verify our theoretical results.

# Summary. An optional shortened abstract.
summary: Entropy, 2023

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2208.07798.pdf'
url_code: 'https://github.com/szubing/csib'
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
