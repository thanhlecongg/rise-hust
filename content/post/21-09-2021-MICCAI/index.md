---
title: An accepted paper in MICCAI 2021
date: 2021-10-09
---

Congratulations to Nguyen Trung-Hieu and Prof. Huynh Quyet-Thang for the acceptance of their MICCAI 2021 (Rank A*, Acceptance Rate = 30%) full research paper titled "VinDr-SpineXR: A Deep Learning Framework for Spinal Lesions Detection and Classification from Radiographs"

<!--more-->

Radiographs are used as the most important imaging tool for identifying spine anomalies in clinical practice. The evaluation of spinal bone lesions, however, is a challenging task for radiologists. This work aims at developing and evaluating a deep learning-based framework, named VinDr-SpineXR, for the classification and localization of abnormalities from spine X-rays. First, we build a large dataset, comprising 10,468 spine X-ray images from 5,000 studies, each of which is manually annotated by an experienced radiologist with bounding boxes around abnormal findings in 13 categories. Using this dataset, we then train a deep learning classifier to determine whether a spine scan is abnormal and a detector to localize 7 crucial findings amongst the total 13. The VinDr-SpineXR is evaluated on a test set of 2,078 images from 1,000 studies, which is kept separate from the training set. It demonstrates an area under the receiver operating characteristic curve (AUROC) of 88.61% (95% CI 87.19%, 90.02%) for the image-level classification task and a mean average precision (mAP@0.5) of 33.56% for the lesion-level localization task. These results serve as a proof of concept and set a baseline for future research in this direction. To encourage advances, the dataset, codes, and trained deep learning models are made publicly available.