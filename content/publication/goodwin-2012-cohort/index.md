---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Cohort Shepherd II: Verifying Cohort Constraints from Hospital Visits'
subtitle: ''
summary: ''
authors:
- Travis Goodwin
- Kirk Roberts
- Bryan Rink
- Sanda M Harabagiu
tags: []
categories: []
date: '2012-11-01'
lastmod: 2021-01-28T11:09:35-05:00
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
publishDate: '2021-01-28T17:24:30.922954Z'
publication_types:
- '1'
abstract: This paper describes the updated system created by the University of Texas
  at Dallas for content-based medical record retrieval submitted to the TREC 2012
  Medical Records Track. Our system updates our work from the previous year by building
  a structured query for each cohort that captures the patient’s age, gender, hospital
  status, and medical assertion information. Further, all keywords that encode any
  medical phenomena from the query are recursively decomposed before being expanded
  using knowledge from UMLS, SNOMED, Wikipedia, and PubMed co-occurrences. An initial
  ranking of hospital visits is then obtained using BM25 relevance on an interpolation
  of these decomposed keywords. Finally, hospital visits are re-ranked according to
  the constraints extracted in the structured query. Four runs were submitted, comparing
  pair-wise combinations of complete vs. shallow keyword decomposition and full vs.
  negation-only assertion processing. Our highest scoring submission achieved an infNDCG
  score of 0.426.
publication: '*Proceedings of the Twenty-first Text REtrieval Conference (TREC 2012)*'
url_pdf: https://trec.nist.gov/pubs/trec21/papers/UTDHLT.medical.nb.pdf
---
