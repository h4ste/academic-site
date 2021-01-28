---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Medical Question Answering for Clinical Decision Support
subtitle: ''
summary: ''
authors:
- Travis R. Goodwin
- Sanda M. Harabagiu
tags:
- '"medical information retrieval"'
- '"question answering"'
- '"clinical decision support"'
categories: []
date: '2016-01-01'
lastmod: 2021-01-28T12:10:18-05:00
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
publishDate: '2021-01-28T17:47:33.079047Z'
publication_types:
- '1'
abstract: The goal of modern Clinical Decision Support (CDS) systems is to provide
  physicians with information relevant to their management of patient care. When faced
  with a medical case, a physician asks questions about the diagnosis, the tests,
  or treatments that should be administered. Recently, the TREC-CDS track has addressed
  this challenge by evaluating results of retrieving relevant scientific articles
  where the answers of medical questions in support of CDS can be found. Although
  retrieving relevant medical articles instead of identifying the answers was believed
  to be an easier task, state-of-the-art results are not yet sufficiently promising.
  In this paper, we present a novel framework for answering medical questions in the
  spirit of TREC-CDS by first discovering the answer and then selecting and ranking
  scientific articles that contain the answer. Answer discovery is the result of probabilistic
  inference which operates on a probabilistic knowledge graph, automatically generated
  by processing the medical language of large collections of electronic medical records
  (EMRs). The probabilistic inference of answers combines knowledge from medical practice
  (EMRs) with knowledge from medical research (scientific articles). It also takes
  into account the medical knowledge automatically discerned from the medical case
  description. We show that this novel form of medical question answering (Q/A) produces
  very promising results in (a) identifying accurately the answers and (b) it improves
  medical article ranking by 40%.
publication: '*Proceedings of the 25th ACM International on Conference on Information
  and Knowledge Management*'
url_pdf: https://doi.org/10.1145/2983323.2983819
doi: 10.1145/2983323.2983819
---
