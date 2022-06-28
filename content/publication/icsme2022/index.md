---
title: 'FFL: Fine-grained Fault Localization for Student Programs'
authors:
  - Nguyen Thanh-Dat
  - admin
  - minhld
  - Duong Van Hai
  - bachldx
  - David Lo
  - thanghq

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  
date: '2022-06-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE 38th International Conference on Software Maintenance and Evolution, Research Track*
publication_short: ICSME 2022

abstract: Fault localization has been used to provide feedback for incorrect student programs since locations of faults can be a valuable hint for students about what caused their programs to crash. Unfortunately, existing fault localization techniques for student programs are limited because they usually consider either the program’s syntax or semantics alone. This motivates the new design of fault localization techniques that use both semantic and syntactical information of the program. In this paper, we introduce FFL (Fine grained Fault Localization), a novel technique using syntactic and semantic reasoning for localizing bugs in student programs. The novelty in FFL that allows it to capture both syntactic and semantic of a program is three-fold, (1) A fine-grained graph-based representation of a program that is adaptive for statement-level fault localization; (2) an effective and efficient model to leverage the designed representation for fault-localization task and (3) a node-level training objective that allows deep learning model to learn from fine-grained syntactic patterns. We compare FFL’s effectiveness with state-of-the-art fault localization techniques for student programs (NBL, Tarantula, Ochiai and DStar) on two real-world datasets, Prutor and Codeflaws. Experimental results show that FFL successfully localizes bug for 84.6% out of 2136 programs on Prutor and 83.1% out of 780 programs on Codeflaws concerning the top-10 suspicious statements. FFL also remarkably outperforms the best baselines by 197%, 104%, 70%, 22% on Codeflaws dataset and 10%, 17%, 15% and 8% on Prutor dataset, in term of top-1, top-3, top-5, top-10, respectively.

# # Summary. An optional shortened abstract.
summary: A novel GNN-based technique for localizing fault student program

tags:
  - ICSME
featured: true

# links:
#   - name: Custom Link
#     url: '#'
# url_pdf: '#'
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
