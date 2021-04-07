---
title: "DETECT: A Deep Discriminative Clustering Baseline for Unsupervised and Universal Domain Adaptation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yain Zhang
- Kui Jia

# Author notes (optional)
# author_notes:

date: "2020-06-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Given a set of labeled instances on a source domain, unsupervised domain adaptation (UDA) aims to learn a prediction function to classify instances in a shifted, target domain. Depending on the degrees of overlap between the label spaces of the two domains, the problem variants of UDA range from the classical, closed set setting to the most general --- arguably the most challenging --- setting of universal domain adaptation. In this work, we argue that no matter what the degree of label space overlap, the problem nature of UDA remains unchanged when it comes to learning the intrinsic discrimination of target data in an unsupervised manner, regularized by the labeled discrimination of source data in an unknown but shared label space, and we argue that this regularization should not overwhelm the learning of a target prediction function. To this end, we propose a simple but strong baseline of neighborhooD-prEserved deep discriminaTivE ClusTering ($DETECT$) for UDA, whose design complies with the above learning principles. We conduct thorough experiments that verify the efficacy of constituent components in $DETECT$ across a range of label space overlaps. Such a simple baseline also outperforms all existing methods on four UDA benchmarks.

# Summary. An optional shortened abstract.
summary: Technique Report, 2020-06-15

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
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
