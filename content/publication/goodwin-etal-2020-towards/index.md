---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Towards Zero-Shot Conditional Summarization with Adaptive Multi-Task Fine-Tuning
subtitle: ''
summary: ''
authors:
- Travis Goodwin
- Max Savery
- Dina Demner-Fushman
tags: []
categories: []
date: '2020-11-01'
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
projects: ["medical-qa"]
publishDate: '2021-01-28T17:47:29.991186Z'
publication_types:
- '1'
abstract: Automatic summarization research has traditionally focused on providing
  high quality general-purpose summaries of documents. However, there are many applications
  which require more specific summaries, such as supporting question answering or
  topic-based literature discovery. In this paper we study the problem of conditional
  summarization in which content selection and surface realization are explicitly
  conditioned on an ad-hoc natural language question or topic description. Because
  of the difficulty in obtaining sufficient reference summaries to support arbitrary
  conditional summarization, we explore the use of multi-task fine-tuning (MTFT) on
  twenty-one natural language tasks to enable zero-shot conditional summarization
  on five tasks. We present four new summarization datasets, two novel ``online″ or
  adaptive task-mixing strategies, and report zero-shot performance using T5 and BART,
  demonstrating that MTFT can improve zero-shot summarization quality.
publication: '*Findings of the Association for Computational Linguistics: EMNLP 2020*'
url_pdf: https://www.aclweb.org/anthology/2020.findings-emnlp.289
doi: 10.18653/v1/2020.findings-emnlp.289
---
