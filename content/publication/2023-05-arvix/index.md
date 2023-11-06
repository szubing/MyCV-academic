---
title: "Universal Domain Adaptation from Foundation Models: A Baseline Study"

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

date: "2023-05-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arVix*
publication_short: In *arVix*

abstract: Foundation models (e.g., CLIP or DINOv2) have shown their impressive learning and transfer capabilities in a wide range of visual tasks, by training on a large corpus of data and adapting to specific downstream tasks. It is, however, interesting that foundation models have not been fully explored for universal domain adaptation (UniDA), which is to learn models using labeled data in a source domain and unlabeled data in a target one, such that the learned models can successfully adapt to the target data. In this paper, we make comprehensive empirical studies of state-of-the-art UniDA methods using foundation models. We first observe that, unlike fine-tuning from ImageNet pre-trained models, as previous methods do, fine-tuning from foundation models yields significantly poorer results, sometimes even worse than training from scratch. While freezing the backbones, we demonstrate that although the foundation models greatly improve the performance of the baseline method that trains the models on the source data alone, existing UniDA methods generally fail to improve over the baseline. This suggests that new research efforts are very necessary for UniDA using foundation models. Based on these findings, we introduce \textit{CLIP distillation}, a parameter-free method specifically designed to distill target knowledge from CLIP models. The core of our \textit{CLIP distillation} lies in a self-calibration technique for automatic temperature scaling, a feature that significantly enhances the baseline's out-class detection capability. Although simple, our method outperforms previous approaches in most benchmark tasks, excelling in evaluation metrics including H-score/H$^3$-score and the newly proposed universal classification rate (UCR) metric. We hope that our investigation and the proposed simple framework can serve as a strong baseline to facilitate future studies in this field.

# Summary. An optional shortened abstract.
summary: arVix, 2023

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2305.11092.pdf'
url_code: 'https://github.com/szubing/uniood'
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
