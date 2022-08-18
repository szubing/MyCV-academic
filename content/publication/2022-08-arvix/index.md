---
title: "Counterfactual Supervision-based Information Bottleneck for Out-of-Distribution Generalization"

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
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arVix*
publication_short: In *arVix*

abstract: Learning invariant (causal) features for out-of-distribution (OOD) generalization has attracted extensive attention recently, and among the proposals invariant risk minimization (IRM) (Arjovsky et al., 2019) is a notable solution. In spite of its theoretical promise for linear regression, the challenges of using IRM in linear classification problems yet remain (Rosenfeld et al.,2020, Nagarajan et al., 2021). Along this line, a recent study (Arjovsky et al., 2019) has made a first step and proposes a learning principle of information bottleneck based invariant risk minimization (IB-IRM). In this paper, we first show that the key assumption of support overlap of invariant features used in (Arjovsky et al., 2019) is rather strong for the guarantee of OOD generalization and it is still possible to achieve the optimal solution without such assumption. To further answer the question of whether IB-IRM is sufficient for learning invariant features in linear classification problems, we show that IB-IRM would still fail in two cases whether or not the invariant features capture all information about the label. To address such failures, we propose a \textit{Counterfactual Supervision-based Information Bottleneck (CSIB)} learning algorithm that provably recovers the invariant features. The proposed algorithm works even when accessing data from a single environment, and has theoretically consistent results for both binary and multi-class problems. We present empirical experiments on three synthetic datasets that verify the efficacy of our proposed method.

# Summary. An optional shortened abstract.
summary: arVix, 2022

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
