---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Relevance Models for Patient Cohort Retrieval
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2018-09-01'
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
publishDate: '2021-01-28T17:24:29.428046Z'
publication_types:
- '2'
abstract: We explored how judgements provided by physicians can be used to learn relevance
  models that enhance the quality of patient cohorts retrieved from Electronic Health
  Records (EHRs) collections.A very large number of features were extracted from patient
  cohort descriptions as well as EHR collections. The features were used to investigate
  retrieving (1) neurology-specific patient cohorts from the de-identified Temple
  University Hospital electroencephalography (EEG) Corpus as well as (2) the more
  general cohorts evaluated in the TREC Medical Records Track (TRECMed) from the de-identified
  hospital records provided by the University of Pittsburgh Medical Center. The features
  informed a learning relevance model (LRM) that took advantage of relevance judgements
  provided by physicians. The LRM implements a pairwise learning-to-rank framework,
  which enables our learning patient cohort retrieval (L-PCR) system to learn from
  physicians’ feedback.We evaluated the L-PCR system against state-of-the-art traditional
  patient cohort retrieval systems, and observed a 27% improvement when operating
  on EEGs and a 53% improvement when operating on TRECMed EHRs, showing the promise
  of the L-PCR system. We also performed extensive feature analyses to reveal the
  most effective strategies for representing cohort descriptions as queries, encoding
  EHRs, and measuring cohort relevance.The L-PCR system has significant promise for
  reliably retrieving patient cohorts from EHRs in multiple settings when trained
  with relevance judgments. When provided with additional cohort descriptions, the
  L-PCR system will continue to learn, thus offering a potential solution to the performance
  barriers of current cohort retrieval systems.
publication: '*JAMIA Open*'
url_pdf: https://doi.org/10.1093/jamiaopen/ooy010
doi: 10.1093/jamiaopen/ooy010
---
