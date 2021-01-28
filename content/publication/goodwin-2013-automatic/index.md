---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Automatic Generation of a Qualified Medical Knowledge Graph and ts Usage for
  Retrieving Patient Cohorts from Electronic Medical Records
subtitle: ''
summary: ''
authors:
- Travis Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2013-09-01'
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
publishDate: '2021-01-28T17:47:33.571010Z'
publication_types:
- '1'
abstract: An extraordinary amount of clinical information is available within Electronic
  Medical Records. However, interpreting this knowledge typically demands a significant
  level of clinical understanding. This can facilitated by access to structured knowledge
  bases. However, even if vast, biomedical knowledge bases have very limited relational
  information available. In contrast, clinical text expresses many relations between
  concepts using an extraordinary amount of variation regarding the author's belief
  state - whether a medical concept is present, uncertain, or absent. In this paper,
  we propose a method for automatically constructing a graph of clinically related
  concepts based on their belief state. For this purpose, we first devise a method
  for classifying the belief state of certain medical concepts. Second, we designed
  a technique for constructing a graph of related medical concepts qualified by the
  physician's belief value. Thirdly, we demonstrate several techniques for inferring
  the similarity between qualified medical concepts, and present a generalized algorithm
  for determining the second-order similarity between qualified medical concepts.
  Finally, we show that incorporating the knowledge encoded from this graph yield
  competitive results when applied to query expansion for the retrieval of hospital
  patient cohorts.
publication: '*2013 IEEE Seventh International Conference on Semantic Computing*'
doi: 10.1109/ICSC.2013.68
---
