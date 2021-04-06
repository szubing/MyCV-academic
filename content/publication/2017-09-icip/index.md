---
title: "A Gabor feature fusion framework for hyperspectral imagery classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sen Jia
- admin
- Huimin
- Lin Deng

# Author notes (optional)
author_notes:
- "Supervisor"

date: "2017-09-17T00:00:00Z"
doi: "10.1109/ICIP.2017.8296711"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-09-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Image Processing*
publication_short: In *ICIP*

abstract: Hyperspectral imagery acquired by a hyperspectral sensor contains hundreds of narrow contiguous spectral bands, providing the opportunity to identify the various materials present on the surface. Due to the three-dimensional (3D) nature of hyperspectral data, 3D filters that could extract joint spatial-spectral features have been recently considered in the literature. In this paper, after the 3D Gabor features with certain orientations have been extracted from the raw hyperspectral image data, both the Gabor magnitude and phase features have been used for hyperspectral imagery classification, which is named as Gabor-MP. Specifically, the confidence score of each test sample is computed by support vector machine for each Gabor magnitude feature cube, while the Hamming distance is calculated based on the quadrant bit coding of each Gabor phase feature cube. Then the label of the test sample is identified by simple calculation between the confidence scores and Hamming distance values. Experimental results on two real hyperspectral data have demonstrated the effectiveness of the proposed Gabor feature fusion framework for hyperspectral imagery classification.

# Summary. An optional shortened abstract.
summary: IEEE International Conference on Image Processing (ICIP), 2017

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8296711'
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
