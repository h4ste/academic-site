---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Flight of the PEGASUS? Comparing Transformers on Few-shot and Zero-shot Multi-document
  Abstractive Summarization
subtitle: ''
summary: ''
authors:
- Travis Goodwin
- Max Savery
- Dina Demner-Fushman
tags: []
categories: []
date: '2020-12-01'
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
projects: []
publishDate: '2021-01-28T17:47:29.663244Z'
publication_types:
- '1'
abstract: 'Recent work has shown that pre-trained Transformers obtain remarkable performance
  on many natural language processing tasks including automatic summarization. However,
  most work has focused on (relatively) data-rich single-document summarization settings.
  In this paper, we explore highly-abstractive multi-document summarization where
  the summary is explicitly conditioned on a user-given topic statement or question.
  We compare the summarization quality produced by three state-of-the-art transformer-based
  models: BART, T5, and PEGASUS. We report the performance on four challenging summarization
  datasets: three from the general domain and one from consumer health in both zero-shot
  and few-shot learning settings. While prior work has shown significant differences
  in performance for these models on standard summarization tasks, our results indicate
  that with as few as 10 labeled examples there is no statistically significant difference
  in summary quality, suggesting the need for more abstractive benchmark collections
  when determining state-of-the-art.'
publication: '*Proceedings of the 28th International Conference on Computational Linguistics*'
url_pdf: https://www.aclweb.org/anthology/2020.coling-main.494
doi: 10.18653/v1/2020.coling-main.494
---
