---
title: "Unsupervised Multi-Class Domain Adaptation: Theory, Algorithms, and Practice"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yabin Zhang
- admin
- Hui Tang
- Lei Zhang
- Kui Jia

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-11-10T00:00:00Z"
doi: "10.1109/TPAMI.2020.3036956"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence*
publication_short: In *TPAMI*

abstract: In this paper, we study the formalism of unsupervised multi-class domain adaptation (multi-class UDA), which underlies a few recent algorithms whose learning objectives are only motivated empirically. Multi-Class Scoring Disagreement (MCSD) divergence is presented by aggregating the absolute margin violations in multi-class classification, and this proposed MCSD is able to fully characterize the relations between any pair of multi-class scoring hypotheses. By using MCSD as a measure of domain distance, we develop a new domain adaptation bound for multi-class UDA; its data-dependent, probably approximately correct bound is also developed that naturally suggests adversarial learning objectives to align conditional feature distributions across source and target domains. Consequently, an algorithmic framework of Multi-class Domain-adversarial learning Networks (McDalNets) is developed, and its different instantiations via surrogate learning objectives either coincide with or resemble a few recently popular methods, thus (partially) underscoring their practical effectiveness. Based on our identical theory for multi-class UDA, we also introduce a new algorithm of Domain-Symmetric Networks (SymmNets), which is featured by a novel adversarial strategy of domain confusion and discrimination. SymmNets affords simple extensions that work equally well under the problem settings of either closed set, partial, or open set UDA. We conduct careful empirical studies to compare different algorithms of McDalNets and our newly introduced SymmNets. Experiments verify our theoretical analysis and show the efficacy of our proposed SymmNets. In addition, we have made our implementation code publicly available.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2020

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2002.08681.pdf'
url_code: 'https://github.com/YBZh/MultiClassDA'
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
