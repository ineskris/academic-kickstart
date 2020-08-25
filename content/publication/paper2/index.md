---
title: Anomaly Detection Semi-Supervised Framework for Sepsis Treatment.
authors:
- Inès Krissaane
- Kingsley Hampton
- Jumanah Alshenaifi 
- Richard Wilkinson

date: "2019-09-08T00:00:00Z"
doi: "10.23919/CinC49843.2019.9005527"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE*
publication_short: In *IEEE*

abstract: Sepsis is one of the leading causes of morbidity and mortality in hospitals. Early diagnosis could substantially improve the patient outcomes and reduce the mortality rate. In this paper we propose a machine learning approach for anomaly detection to aid the early detection of sepsis. Using the medical data of over 40,000 patients [1], we use both unsupervised and supervised methods to extract relevant features from the data, and then use standard classification approaches to predict sepsis six hours before clinical diagnosis occurs. To extract features, we used the reconstruction error of an auto-encoding neural network trained on control patients free of sepsis, and used random forest classifiers to learn the most important features for the classification of patients. We then combined the features from both of these approaches with a variety of standard classification models. Cross-validation as well as the asymmetric utility function designed for this challenge are used to evaluate the resulting models. We obtained a utility function score for the full unseen dataset of 0.177 (Team Kriss); achieved with a logistic regression classifier. All the implementation is publicly available at https://github.com/ineskris/SepsisChallenge-Cinc2019.

# Summary. An optional shortened abstract.
summary: Sepsis is one of the leading causes of morbidity and mortality in hospitals. Early diagnosis could substantially improve the patient outcomes and reduce the mortality rate. In this paper we propose a machine learning approach for anomaly detection to aid the early detection of sepsis.

tags:
- Publications
featured: false

links:
#- name: Custom Link
  #url: http://example.org
#url_pdf:  'files/Presentation_stage.pdf'
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: 
#url_slides: '#Presentation_stage.pdf'
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
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
#slides: Presentation_stage
---


