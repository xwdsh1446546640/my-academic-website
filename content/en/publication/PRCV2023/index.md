---
title: "Pose Transfer using Multiple Input Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xin Jin
- Chenyu Fan
- admin
- Chaoen Xiao
- Chao Xia
- Shengxin Li
- Huilin Zhou
- Yujin Li

# Author notes (optional)
# author_notes:

date: "2023-08-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: []

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In [*Chinese Conference on Pattern Recognition and Computer Vision (PRCV) (CCF-C), Xiamen, Oct 13—15, 2023.*]
publication_short: In *PRCV 2023*

abstract: 'One key challenge of pose transfer lies in its large variation and occlusion. Existing methods are basically aimed at the migration of the pose in a single input image. So these methods have difficulties predicting reasonable invisible re-gions and fail to decouple the shape and style of clothing. Although pose transfer method using single input image can generate the results with correct structure, it cannot keep the original details of the image. To solve this problem, we propose a two-stage generative model for pose transfer based on multiple input images. First, the Feature Extraction Stage, then Reposing Stage. In feature extraction stage, we extract relevant features from each input image. Then, in reposing stage, we propose a pose-conditioned transformer-based StyleGAN generator, adding residual module and fusion module at different levels of the generator. In this way, we can get the most relevant features from each input image for weighted fusion, thus improving the quality of the results. We show that our method compares favorably against those using single input image in both quantitative evaluation and visual comparison.'

# Summary. An optional shortened abstract.
summary: 'This study compares the performance of the pose transfer task in the case of multiple input images.'
tags: [Pose Transfer,  Pose-guided Person Image Synthesis, Muti-source Image Generation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:

url_pdf: 'publication/PRCV2023/10.pdf'
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
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---
