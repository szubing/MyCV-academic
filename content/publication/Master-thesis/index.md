---
title: "基于超像素分割的高光谱图像特征变换和分类算法研究"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-06-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-06-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: In *Shenzhen University*
publication_short: In *SZU*

abstract: 高光谱图像是由成像光谱仪获取的包含几十乃至上百个连续谱段信息的数据立方体。这种三维图像具备丰富的地表空间信息和光谱信息,已被广泛应用于地表分类、目标探测、环境管理、农业监测和军事目标识别等诸多领域,为我国国民经济和国防建设等方面发挥了重要的作用。然而,分类作为高光谱图像处理和应用的一项重要技术,仍然面临着诸多问题和挑战。一方面,高光谱图像数据所呈现的高度非线性使得直接对其原始数据进行分类难以达到可观的效果;另一方面,极其有限的先验样本使得分类模型的参数难以估计准确。为了更好的解决这些问题,在基于高光谱图像特性和分析研究现状的基础上,本文重点在两个方面上研究了如何利用超像素来实现有效的小样本地物分类。首先,在提取高光谱图像特征上,为了能够得到更加空谱一体化的特征以及充分利用这些特征信息,本文提出了一个由超像素引导的基于支持向量机的多任务学习框架。该框架在原有的薛定谔特征映射的基础上,将多组Gabor特征作用其中,并采用基于超像素水平的特征降维方法,从而充分挖掘了高光谱图像的空间-光谱信息,并降低了时间复杂度。在得到多组空谱一体特征之后,为了更好地利用这些特征来进行分类,本文首次采用了基于支持向量机的多任务学习方法,该方法对比于传统的基于稀疏表示的多任务学习方法,大大减少了时间复杂度。实验结果表明,对比于当前一些先进的特征提取方法,该分类框架能够提取出表征性更强的特征并能得到更高的分类精度。另一方面,在高光谱图像分类结果决策融合上,为了能够得到更加符合地表实际情况的分类结果,本文提出了由超像素引导的基于局部二值模式(Local Binary Pattern,LBP)的分类方法。首先,该方法最核心部分就是能够分割出更加基于地物分布的超像素,这通过对高光谱图像的过分割以及区域合并操作完成。接着,该方法使用了统一模式的局部二值模式(Uniform Local Binary Pattern,ULBP)来提取纹理特征,并利用支持向量机对该特征进行预分类,得到每个像素属于每一类的概率。最后,一个基于超像素的软决策融合方法将被提出并得到最终的分类标签。实验结果表明,该方法能够在小样本的情况下得到非常好的分类效果,尤其是对于地物分布更均匀的图像。

# Summary. An optional shortened abstract.
summary: Master Thesis, 2018

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
