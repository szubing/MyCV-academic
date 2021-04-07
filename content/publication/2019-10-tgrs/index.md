---
title: "Deep Metric Learning-Based Feature Embedding for Hyperspectral Image Classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Sen Jia
- Daming Shi

# Author notes (optional)
# author_notes:

date: "2019-10-30T00:00:00Z"
doi: "10.1109/TGRS.2019.2946318"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Geoscience and Remote Sensing*
publication_short: In *TGRS*

abstract: Learning from a limited number of labeled samples (pixels) remains a key challenge in the hyperspectral image (HSI) classification. To address this issue, we propose a deep metric learning-based feature embedding model, which can meet the tasks both for same- and cross-scene HSI classifications. In the first task, when only a few labeled samples are available, we employ ideas from metric learning based on deep embedding features and make a similarity learning between pairs of samples. In this case, the proposed model can learn well to compare whether two samples belong to the same class. In another task, when an HSI image (target scene) that needs to be classified is not labeled at all, the embedding model can learn from another similar HSI image (source scene) with sufficient labeled samples and then transfer to the target model by using an unsupervised domain adaptation technique, which not only employs the adversarial approach to make the embedding features from the source and target samples indistinguishable but also encourages the target scene's embeddings to form similar clusters with the source scene one. After the domain adaptation between the HSIs of the two scenes is finished, any traditional HSI classifier can be used. In a simple manner, the nearest neighbor (NN) algorithm is selected as the classifier for the classification tasks throughout this article. The experimental results from a series of popular HSIs demonstrate the advantages of the proposed model both in the same- and cross-scene classification tasks.

# Summary. An optional shortened abstract.
summary: IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2019

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8887497'
url_code: 'https://github.com/szubing/S-DMM'
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
