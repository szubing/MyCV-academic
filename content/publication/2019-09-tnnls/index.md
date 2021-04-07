---
title: "Cascade Superpixel Regularized Gabor Feature Fusion for Hyperspectral Image Classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sen Jia
- Zhijie Lin
- admin
- Jiasong Zhu
- Qingquan Li

# Author notes (optional)
# author_notes:

date: "2019-07-02T00:00:00Z"
doi: "10.1109/TNNLS.2019.2921564"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Neural Networks and Learning Systems*
publication_short: In *TNNLS*

abstract: A 3-D Gabor wavelet provides an effective way to obtain the spectral-spatial-fused features for hyperspectral image, which has shown advantageous performance for material classification and recognition. In this paper, instead of separately employing the Gabor magnitude and phase features, which, respectively, reflect the intensity and variation of surface materials in local area, a cascade superpixel regularized Gabor feature fusion (CSRGFF) approach has been proposed. First, the Gabor filters with particular orientation are utilized to obtain Gabor features (including magnitude and phase) from the original hyperspectral image. Second, a support vector machine (SVM)-based probability representation strategy is developed to fully exploit the decision information in SVM output, and the achieved confidence score can make the following fusion with Gabor phase more effective. Meanwhile, the quadrant bit coding and Hamming distance metric are applied to encode the Gabor phase features and measure sample similarity in sequence. Third, the carefully defined characteristics of two kinds of features are directly combined together without any weighting operation to describe the weight of samples belonging to each class. Finally, a series of superpixel graphs extracted from the raw hyperspectral image with different numbers of superpixels are employed to successively regularize the weighting cube from over-segmentation to under-segmentation, and the classification performance gradually improves with the decrease in the number of superpixels in the regularization procedure. Four widely used real hyperspectral images have been conducted, and the experimental results constantly demonstrate the superiority of our CSRGFF approach over several state-of-the-art methods.
# Summary. An optional shortened abstract.
summary: IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2019

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8753677'
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
