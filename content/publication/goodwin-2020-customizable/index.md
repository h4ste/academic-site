---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Customizable Deep Learning Model for Nosocomial Risk Prediction from Critical
  Care Notes with Indirect Supervision
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Dina Demner-Fushman
tags: []
categories: []
date: '2020-02-01'
lastmod: 2021-01-27T16:23:27-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-01-28T17:24:29.250559Z'
publication_types:
- '2'
abstract: Reliable longitudinal risk prediction for hospitalized patients is needed
  to provide quality care. Our goal is to develop a generalizable model capable of
  leveraging clinical notes to predict healthcare-associated diseases 24–96 hours
  in advance.We developed a reCurrent Additive Network for Temporal RIsk Prediction
  (CANTRIP) to predict the risk of hospital acquired (occurring ≥ 48 hours after admission)
  acute kidney injury, pressure injury, or anemia ≥ 24 hours before it is implicated
  by the patient’s chart, labs, or notes. We rely on the MIMIC III critical care database
  and extract distinct positive and negative cohorts for each disease. We retrospectively
  determine the date-of-event using structured and unstructured criteria and use it
  as a form of indirect supervision to train and evaluate CANTRIP to predict disease
  risk using clinical notes.Our experiments indicate that CANTRIP, operating on text
  alone, obtains 74%–87% area under the curve and 77%–85% Specificity. Baseline shallow
  models showed lower performance on all metrics, while bidirectional long short-term
  memory obtained the highest Sensitivity at the cost of significantly lower Specificity
  and Precision.Proper model architecture allows clinical text to be successfully
  harnessed to predict nosocomial disease, outperforming shallow models and obtaining
  similar performance to disease-specific models reported in the literature.Clinical
  text on its own can provide a competitive alternative to traditional structured
  features (eg, lab values, vital signs). CANTRIP is able to generalize across nosocomial
  diseases without disease-specific feature extraction and is available at https://github.com/h4ste/cantrip.
publication: '*Journal of the American Medical Informatics Association*'
url_pdf: https://doi.org/10.1093/jamia/ocaa004
doi: 10.1093/jamia/ocaa004
---
