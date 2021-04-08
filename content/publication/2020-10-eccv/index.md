---
title: "Label Propagation with Augmented Anchors: A Simple Semi-supervised Learning Baseline for Unsupervised Domain Adaptation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yabin Zhang
- admin
- Kui Jia
- Lei Zhang

# Author notes (optional)
# author_notes:

date: "2020-10-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision*
publication_short: In *ECCV*

abstract: Motivated by the problem relatedness between unsupervised domain adaptation (UDA) and semi-supervised learning (SSL), many state-of-the-art UDA methods adopt SSL principles (e.g., the cluster assumption) as their learning ingredients. However, they tend to overlook the very domain-shift nature of UDA. In this work, we take a step further to study the proper extensions of SSL techniques for UDA. Taking the algorithm of label propagation (LP) as an example, we analyze the challenges of adopting LP to UDA and theoretically analyze the conditions of affinity graph/matrix construction in order to achieve better propagation of true labels to unlabeled instances. Our analysis suggests a new algorithm of Label Propagation with Augmented Anchors (A2LP), which could potentially improve LP via generation of unlabeled virtual instances (i.e., the augmented anchors) with high-confidence label predictions. To make the proposed A2LP useful for UDA, we propose empirical schemes to generate such virtual instances. The proposed schemes also tackle the domain-shift challenge of UDA by alternating between pseudo labeling via A2LP and domain-invariant feature learning. Experiments show that such a simple SSL extension improves over representative UDA methods of domain-invariant feature learning, and could empower two state-of-the-art methods on benchmark UDA datasets. Our results show the value of further investigation on SSL techniques for UDA problems.

# Summary. An optional shortened abstract.
summary: European Conference on Computer Vision (ECCV), 2020

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/content/pdf/10.1007%2F978-3-030-58548-8_45.pdf'
url_code: 'https://github.com/YBZh/Label-Propagation-with-Augmented-Anchors'
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
