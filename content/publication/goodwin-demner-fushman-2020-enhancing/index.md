---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Enhancing Question Answering by Injecting Ontological Knowledge through Regularization
subtitle: ''
summary: ''
authors:
- Travis Goodwin
- Dina Demner-Fushman
tags: []
categories: []
date: '2020-11-01'
lastmod: 2021-01-27T18:35:24-05:00
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
publishDate: '2021-01-28T17:47:29.827973Z'
publication_types:
- '1'
abstract: Deep neural networks have demonstrated high performance on many natural
  language processing (NLP) tasks that can be answered directly from text, and have
  struggled to solve NLP tasks requiring external (e.g., world) knowledge. In this
  paper, we present OSCR (Ontology-based Semantic Composition Regularization), a method
  for injecting task-agnostic knowledge from an Ontology or knowledge graph into a
  neural network during pre-training. We evaluated the performance of BERT pre-trained
  on Wikipedia with and without OSCR by measuring the performance when fine-tuning
  on two question answering tasks involving world knowledge and causal reasoning and
  one requiring domain (healthcare) knowledge and obtained 33.3%, 18.6%, and 4% improved
  accuracy compared to pre-training BERT without OSCR.
publication: '*Proceedings of Deep Learning Inside Out (DeeLIO): The First Workshop
  on Knowledge Extraction and Integration for Deep Learning Architectures*'
url_pdf: https://www.aclweb.org/anthology/2020.deelio-1.7
doi: 10.18653/v1/2020.deelio-1.7
---
