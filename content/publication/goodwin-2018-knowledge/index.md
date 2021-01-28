---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Knowledge Representations and Inference Techniques for Medical Question Answering
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Sanda M Harabagiu
tags:
- '"clinical decision support"'
- '"medical information retrieval"'
- '"medical knowledge representation"'
- '"medical question answering"'
- '"probabilistic inference"'
categories: []
date: '2017-10-01'
lastmod: 2021-01-27T18:36:04-05:00
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
publishDate: '2021-01-28T17:47:28.820015Z'
publication_types:
- '2'
abstract: Answering medical question related to complex medical cases, as required
  in modern Clinical Decision Support (CDS) systems, imposes (1) access to vast medical
  knowledge and (2) sophisticated inference techniques. In this paper, we examine
  the representation and role of combining medical knowledge automatically derived
  from (a) clinical practice and (b) research findings for inferring answers to medical
  questions. Knowledge from medical practice was distilled from a vast Electronic
  Medical Record (EMR) system, while research knowledge was processed from biomedical
  articles available in PubMed Central. The knowledge automatically acquired from
  the EMR system took into account the clinical picture and therapy recognized from
  each medical record to generate a probabilistic Markov network denoted as a Clinical
  Picture and Therapy Graph (CPTG). Moreover, we represented the background of medical
  questions available from the description of each complex medical case as a medical
  knowledge sketch. We considered three possible representations of medical knowledge
  sketches that were used by four different probabilistic inference methods to pinpoint
  the answers from the CPTG. In addition, several answer-informed relevance models
  were developed to provide a ranked list of biomedical articles containing the answers.
  Evaluations on the TREC-CDS data show which of the medical knowledge representations
  and inference methods perform optimally. The experiments indicate an improvement
  of biomedical article ranking by 49% over state-of-the-art results.
publication: '*ACM Transactions on Intelligent Systems and Technology (TIST)*'
url_pdf: http://doi.acm.org/10.1145/3106745
doi: 10.1145/3106745
---
