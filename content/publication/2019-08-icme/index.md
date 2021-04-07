---
title: "Multi-Task Embedded Convolutional Neural Network for Hyperspectral Image Classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhijie Lin
- Sen Jia
- admin

# Author notes (optional)
# author_notes:

date: "2019-08-05T00:00:00Z"
doi: "10.1109/ICME.2019.00247"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Multimedia & Expo*
publication_short: In *ICME*

abstract: Convolutional neural network (CNN) is a powerful visual model which has a significant performance in various visual recognition issues, and attracted considerable attention in recent years. Due to the strong correlation between bands and small sample set (3S) problem, hyperspectral image classification issue remains a challenging problem. In this paper, we construct a novel multi-task framework with embedded convolutional neural network to obtain stronger discriminative capability for hyperspectral image classification. A variance of CNN, which is named Network in Network (NIN), is used to construct three sub-model. Here 1 × 1 convolutional filter is adopted and average pooling layer is employed to replace the full connect layer. The input of the first sub-model is spatial-spectral schroedinger Eigenmapes (SSSE) which can provide fused information of spatial and spectral information. Meanwhile, due to the significant capability of extracting spatial texture of the uniform local binary (ULBP), the histogram feature extracted from ULBP is used as the second sub-model input. Raw hyperspectral data is input to the last sub-model for supplying external information that SSSE and ULBP have lost. Experimental results demonstrate the effectiveness of the proposed model.

# Summary. An optional shortened abstract.
summary: IEEE International Conference on Multimedia & Expo (ICME), 2019

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8795023'
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
