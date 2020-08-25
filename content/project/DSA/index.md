---
title: Data Science Africa 
summary: Image Processing for parasites detection in Uganda. 
tags:
- Machine Learning
date: "2019-07-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "Parasites detection with microscopic images."
  focal_point: Smartfe

links:
- name: Challenge
  url: https://codalab.lri.fr/competitions/
- name: More
  url: http://air.ug/microscopy/
 #url_pdf:  'files/Rapport_Data.pdf'
#url_code: 'https://github.com/ineskris/HH_model'
#url_dataset: '#'
#url_poster: '#'
url_project: http://www.datascienceafrica.org/
#url_slides: '#Presentation_stage.pdf'
#url_source: '#'
#url_video: '#'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Although microscopes are common in Uganda and other developing countries, a shortage of lab technicians to operate them means that access to quality diagnostic services is limited for much of the population. This leads to misdiagnoses of disease, which in turn causes life-threatening conditions to be incorrectly treated, drug resistance, and the economic burden of buying unnecessary drugs. Even where health facilities have lab technicians, they are often oversubscribed and have difficulty spending enough time on each sample to give a confident diagnosis. Given that smartphones are widely owned across the developing world, there is a technological opportunity to address this problem: phones can be used to capture and process microscopy images. This project aims to produce a functioning point-of-care diagnosis system on this principle, capable of running on multiple microscope and phone combinations. Our work exploits recent technological advances in 3D printing and deep learning to produce effective hardware and software respectively.

Step 1: Binary classification problem. You need to implement a machine learning model in order to classify whether a patch is positive or negative.
Step 2: Regression problem. You need to predict the number of parasites on each image (using model trained on Step 1).