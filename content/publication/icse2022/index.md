---
title: 'Toward the Analysis of Graph Neural Network'
authors:
  - Nguyen Thanh-Dat
  - admin
  - Nguyen H. ThanhVu
  - bachldx
  - thanghq

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  
date: '2021-12-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *the 44th IEEE/ACM International Conference on Software Engineering, NIER Track*
publication_short: ICSE 2022

abstract: Graph Neural Networks (GNNs) have recently emerged as an effective framework for representing and analyzing graph-structured data. GNNs have been applied to many real-world problems such as knowledge graph analysis, social networks recommendation, and even COVID-19 detection and vaccine development. However, unlike other deep neural networks such as Feedforward Neural Networks (FFNNs), few verification and property inference techniques exist for GNNs. This is potentially due to dynamic behaviors of GNNs, which can take arbitrary graphs as input, whereas FFNNs which only take fixed size numerical vectors as inputs. This paper proposes GNN-Infer, an approach to analyze and infer properties of GNNs by extracting influential structures of the GNNs and then converting them into FFNNs. This allows us to leverage existing powerful FFNNs analyses to obtain results for the original GNNs. We discuss various designs of CNN-lnfer to ensure the scalability and accuracy of the conversions. We also illustrate CNN-Infer on a study case of node classification. We believe that CNN-Infer opens new research directions for understanding and analyzing GNNs.

# # Summary. An optional shortened abstract.
summary: A new ideas about the analysis of Graph Neural Networks. 

tags:
  - ICSE
featured: true

# links:
#   - name: Custom Link
#     url: '#'
url_pdf: 'https://arxiv.org/pdf/2201.00115.pdf'
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: 'https://conf.researchr.org/details/icse-2022/icse-2022-nier---new-ideas-and-emerging-results/10/Toward-the-Analysis-of-Graph-Neural-Network'
# url_source: '#'
url_video: 'https://conf.researchr.org/details/icse-2022/icse-2022-nier---new-ideas-and-emerging-results/10/Toward-the-Analysis-of-Graph-Neural-Network'

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
