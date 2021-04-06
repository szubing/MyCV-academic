---
title: "Superpixel-Based Multitask Learning Framework for Hyperspectral Image Classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sen Jia
- admin
- Jiasong Zhu
- Xiuping Jia
- Qingquan Li

# Author notes (optional)
author_notes:
- "Supervisor"

date: "2017-01-24T00:00:00Z"
doi: "10.1109/TGRS.2017.2647815"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Geoscience and Remote Sensing*
publication_short: In *TGRS*

abstract: Due to the high spectral dimensionality of hyperspectral images as well as the difficult and time-consuming process of collecting sufficient labeled samples in practice, the small sample size scenario is one crucial problem and a challenging issue for hyperspectral image classification. Fortunately, the structure information of materials, reflecting region of homogeneity in the spatial domain, offers an invaluable complement to the spectral information. Assuming some spatial regularity and locality of surface materials, it is reasonable to segment the image into different homogeneous parts in advance, called superpixel, which can be used to improve the classification performance. In this paper, a superpixel-based multitask learning framework has been proposed for hyperspectral image classification. Specifically, a set of 2-D Gabor filters are first applied to hyperspectral images to extract discriminative features. Meanwhile, a superpixel map is generated from the hyperspectral images. Second, a superpixel-based spatial-spectral Schroedinger eigenmaps (S4E) method is adopted to effectively reduce the dimensions of each extracted Gabor cube. Finally, the classification is carried out by a support vector machine (SVM)-based multitask learning framework. The proposed approach is thus termed Gabor S4E and SVM-based multitask learning (GS4E-MTLSVM). A series of experiments is conducted on three real hyperspectral image data sets to demonstrate the effectiveness of the proposed GS4E-MTLSVM approach. The experimental results show that the performance of the proposed GS4E-MTLSVM is better than those of several state-of-the-art methods, while the computational complexity has been greatly reduced, compared with the pixel-based spatial-spectral Schroedinger eigenmaps method.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2017

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7831466'
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
