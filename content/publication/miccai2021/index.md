---
title: 'VinDr-SpineXR: A deep learning framework for spinal lesions detection and classification from radiographs'
Pham, Hieu H and Nguyen, Nghia T and Nguyen, Ha Q and Huynh, Thang Q and Dao, Minh and Vu, Van
authors:
  - hieunt
  - Pham Huy Hieu
  - Nguyen Q. Ha
  - thanghq
  - Dao Minh
  - Vu Van 

date: '2021-09-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE 24nd International Conference on Medical Image Computing and Computer-Assisted Intervention*
publication_short: MICCAI 2022

abstract: Radiographs are used as the most important imaging tool for identifying spine anomalies in clinical practice. The evaluation of spinal bone lesions, however, is a challenging task for radiologists. This work aims at developing and evaluating a deep learning-based framework, named VinDr-SpineXR, for the classification and localization of abnormalities from spine X-rays. First, we build a large dataset, comprising 10,468 spine X-ray images from 5,000 studies, each of which is manually annotated by an experienced radiologist with bounding boxes around abnormal findings in 13 categories. Using this dataset, we then train a deep learning classifier to determine whether a spine scan is abnormal and a detector to localize 7 crucial findings amongst the total 13. The VinDr-SpineXR is evaluated on a test set of 2,078 images from 1,000 studies, which is kept separate from the training set. It demonstrates an area under the receiver operating characteristic curve (AUROC) of 88.61% (95% CI 87.19%, 90.02%) for the image-level classification task and a mean average precision (mAP@0.5) of 33.56% for the lesion-level localization task. These results serve as a proof of concept and set a baseline for future research in this direction. To encourage advances, the dataset, codes, and trained deep learning models are made publicly available.

# # Summary. An optional shortened abstract.
summary: A deep learning framework for automatically classifying and localizing abnormalities on spine X-rays. 

tags:
  - MICCAI
featured: true

# links:
#   - name: Custom Link
#     url: '#'
url_pdf: 'https://arxiv.org/pdf/2106.12930.pdf'
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: 'https://conf.researchr.org/details/icse-2022/icse-2022-nier---new-ideas-and-emerging-results/10/Toward-the-Analysis-of-Graph-Neural-Network'
# url_source: '#'
# url_video: 'https://conf.researchr.org/details/icse-2022/icse-2022-nier---new-ideas-and-emerging-results/10/Toward-the-Analysis-of-Graph-Neural-Network'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
