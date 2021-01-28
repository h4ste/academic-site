---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multi-modal Patient Cohort Identification from EEG Report and Signal Data
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2016-11-01'
lastmod: 2021-01-28T11:41:47-05:00
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
publishDate: '2021-01-28T17:47:32.264857Z'
publication_types:
- '1'
abstract: Clinical electroencephalography (EEG) is the most important investigation
  in the diagnosis and management of epilepsies. An EEG records the electrical activity
  along the scalp and measures spontaneous electrical activity of the brain. Because
  the EEG signal is complex, its interpretation is known to produce moderate inter-observer
  agreement among neurologists. This problem can be addressed by providing clinical
  experts with the ability to automatically retrieve similar EEG signals and EEG reports
  through a patient cohort retrieval system operating on a vast archive of EEG data.
  In this paper, we present a multi-modal EEG patient cohort retrieval system called
  MERCuRY which leverages the heterogeneous nature of EEG data by processing both
  the clinical narratives from EEG reports as well as the raw electrode potentials
  derived from the recorded EEG signal data. At the core of MERCuRY is a novel multimodal
  clinical indexing scheme which relies on EEG data representations obtained through
  deep learning. The index is used by two clinical relevance models that we have generated
  for identifying patient cohorts satisfying the inclusion and exclusion criteria
  expressed in natural language queries. Evaluations of the MERCuRY system measured
  the relevance of the patient cohorts, obtaining MAP scores of 69.87% and a NDCG
  of 83.21%.
publication: '*Proceedings of the 2016 American Medical Informatics Association (AMIA)
  Annual Symposium*'
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5333290/
---
