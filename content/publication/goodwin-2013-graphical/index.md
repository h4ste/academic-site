---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Graphical Induction of Qualified Medical Knowledge
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2013-01-01'
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
projects: ["medical-qa", "medical-ir"]
publishDate: '2021-01-28T17:47:28.991158Z'
publication_types:
- '2'
abstract: The introduction of electronic medical records (EMRs) enabled the access
  of unprecedented volumes of clinical data, both in structured and unstructured formats.
  A significant amount of this clinical data is expressed within the narrative  portion
  of the EMRs, requiring natural language processing techniques to unlock the medical
  knowledge referred to by physicians. This knowledge, derived from the practice of
  medical care, complements medical knowledge already encoded in  various structured
  biomedical ontologies. Moreover, the clinical knowledge derived from EMRs also exhibits
  relational information between medical concepts, derived from the cohesion property
  of clinical text, which is an attractive attribute that is currently missing from
  the vast biomedical knowledge bases. In this paper, we describe an automatic method
  of generating a graph of clinically related medical concepts by considering the
  belief values associated with those concepts. The belief value is an expression
  of the clinician’s assertion that the concept is qualified as present, absent, suggested,
  hypothetical, ongoing, etc. Because the method detailed in this paper takes into
  account the hedging used by physicians when authoring EMRs, the resulting graph
  encodes qualified medical knowledge wherein each medical concept has an associated
  assertion (or belief value) and such qualified medical concepts are spanned by relations
  of different strengths, derived from the clinical contexts in which concepts are
  used. In this paper, we discuss the construction of a qualified medical knowledge
  graph (QMKG) and treat it as a BigData problem addressed by using MapReduce for
  deriving the weighted edges of the graph. To be able to assess the value of the
  QMKG, we demonstrate its usage for retrieving patient cohorts by enabling query
  expansion that produces greatly enhanced results against state-of-the-art methods.
publication: '*International Journal of Semantic Computing*'
doi: 10.1142/S1793351X13400126
---
