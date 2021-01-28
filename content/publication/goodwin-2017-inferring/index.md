---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Inferring Clinical Correlations from EEG Reports with Deep Neural Learning
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2017-11-01'
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
publishDate: '2021-01-28T17:47:32.097382Z'
publication_types:
- '1'
abstract: Successful diagnosis and management of neurological dysfunction relies on
  proper communication between the neurologist and the primary physician (or other
  specialists). Because this communication is documented within medical records, the
  ability to automatically infer the clinical correlations for a patient from his
  or her medical records would provide an important step towards enabling health care
  systems to automatically identify patients requiring additional follow-up as well
  as flagging any unexpected clinical correlations for review. In this paper, we present
  a Deep Section Recovery Model (DSRM) which applies deep neural learning on a large
  body of EEG reports in order to infer the expected clinical correlations for a patient
  from the information in a given EEG report by (1) automatically extracting word-
  and report- level features from the report and (2) inferring the most likely clinical
  correlations and expressing those clinical correlations in natural language. We
  evaluated the performance of the DSRM by removing the clinical correlation sections
  from EEG reports and measuring how well the model could recover that information
  from the remainder of the report. The DSRM obtained a 17% improvement over the top-performing
  baseline, highlighting not only the power of the DSRM but also the promise of automatically
  recognizing unexpected clinical correlations in the future.
publication: '*Proceedings of the 2017 American Medical Informatics Association (AMIA)
  Annual Symposium*'
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5977577/
---
