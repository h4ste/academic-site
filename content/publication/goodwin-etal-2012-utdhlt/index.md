---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'UTDHLT: COPACETIC System for Choosing Plausible Alternatives'
subtitle: ''
summary: ''
authors:
- Travis Goodwin
- Bryan Rink
- Kirk Roberts
- Sanda Harabagiu
tags: []
categories: []
date: '2012-06-01'
lastmod: 2021-01-27T18:35:25-05:00
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
publishDate: '2021-01-28T17:24:30.581855Z'
publication_types:
- '1'
abstract: The Choice of Plausible Alternatives (COPA) task in SemEval-2012 presents
  a series of forced-choice questions wherein each question provides a premise and
  two viable cause or effect scenarios. The correct answer is the cause or effect
  that is the most plausible. This paper describes the COPACETIC system developed
  by the University of Texas at Dallas (UTD) for this task. We approach this task
  by casting it as a classification problem and using features derived from bigram
  co-occurrences, TimeML temporal links between events, single-word polarities from
  the Harvard General Inquirer, and causal syntactic dependency structures within
  the gigaword corpus. Additionally, we show that although each of these components
  improves our score for this evaluation, the difference in accuracy between using
  all of these features and using bigram co-occurrence information alone is not statistically
  significant.
publication: '**SEM 2012: The First Joint Conference on Lexical and Computational
  Semantics -- Volume 1: Proceedings of the main conference and the shared task, and
  Volume 2: Proceedings of the Sixth International Workshop on Semantic Evaluation
  (SemEval 2012)*'
url_pdf: https://www.aclweb.org/anthology/S12-1063
---
