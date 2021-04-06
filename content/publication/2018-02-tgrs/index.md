---
title: "Local Binary Pattern-Based Hyperspectral Image Classification With Superpixel Guidance"

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

date: "2017-10-16T00:00:00Z"
doi: "10.1109/TGRS.2017.2754511"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-10-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Geoscience and Remote Sensing*
publication_short: In *TGRS*

abstract: Since it is usually difficult and time-consuming to obtain sufficient training samples by manually labeling, feature extraction, which investigates the characteristics of hyperspectral images (HSIs), such as spectral continuity and spatial locality of surface objects, to achieve the most discriminative feature representation, is very important for HSI classification. Meanwhile, due to the spatial regularity of surface materials, it is desirable to improve the classification performance of HSIs from the superpixel viewpoint. In this paper, we propose a novel local binary pattern (LBP)-based superpixel-level decision fusion method for HSI classification. The proposed framework employs uniform LBP (ULBP) to extract local image features, and then, a support vector machine is utilized to formulate the probability description of each pixel belonging to every class. The composite image of the first three components extracted by a principal component analysis from the HSI data is oversegmented into many homogeneous regions by using the entropy rate segmentation method. Then, a region merging process is applied to make the superpixels obtained more homogeneous and agree with the spatial structure of materials more precisely. Finally, a probability-oriented classification strategy is applied to classify each pixel based on superpixel-level guidance. The proposed framework “ULBP-based superpixel-level decision fusion framework” is named ULBP-SPG. Experimental results on two real HSI data sets have demonstrated that the proposed ULBP-SPG framework is more effective and powerful than several state-of-the-art methods.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2017

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8068950'
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
