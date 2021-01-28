---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Inferring the Interactions of Risk Factors from EHRs
subtitle: ''
summary: ''
authors:
- Travis Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2016-03-01'
lastmod: 2021-01-28T11:41:48-05:00
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
projects: ["eeg-processing"]
publishDate: '2021-01-28T17:47:32.753568Z'
publication_types:
- '1'
abstract: The wealth of clinical information provided by the advent of electronic
  health records offers an exciting opportunity to improve the quality of patient
  care. Of particular importance are the risk factors, which indicate possible diagnoses,
  and the medications which treat them. By analysing which risk factors and medications
  were mentioned at different times in patients’ EHRs, we are able to construct a
  patient’s clinical chronology. This chronology enables us to not only predict how
  new patient’s risk factors may progress, but also to discover patterns of interactions
  between risk factors and medications. We present a novel probabilistic model of
  patients’ clinical chronologies and demonstrate how this model can be used to (1)
  predict the way a new patient’s risk factors may evolve over time, (2) identify
  patients with irregular chronologies, and (3) discovering the interactions between
  pairs of risk factors, and between risk factors and medications over time. Moreover,
  the model proposed in this paper does not rely on (nor specify) any prior knowledge
  about any interactions between the risk factors and medications it represents. Thus,
  our model can be easily applied to any arbitrary set of risk factors and medications
  derived from a new dataset.
publication: '*Proceedings of the 2016 American Medical Informatics Association (AMIA)
  Summit on Clinical Research Informatics*'
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5001781/
---
