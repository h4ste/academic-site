---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Deep Learning from EEG Reports for Inferring Underspecified Information
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2017-03-01'
lastmod: 2021-01-28T11:41:47-05:00
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
publishDate: '2021-01-28T16:41:47.783172Z'
publication_types:
- '1'
abstract: Secondary use of electronic health records (EHRs) often relies on the ability
  to automatically identify and extract information from EHRs. Unfortunately, EHRs
  are known to suffer from a variety of idiosyncrasies – most prevalently, they have
  been shown to often omit or underspecify information. Adapting traditional machine
  learning methods for inferring underspecified information relies on manually specifying
  features characterizing the specific information to recover (e.g. particular findings,
  test results, or physician’s impressions). By contrast, in this paper, we present
  a method for jointly (1) automatically extracting word- and report-level features
  and (2) inferring underspecified information from EHRs. Our approach accomplishes
  these two tasks jointly by combining recent advances in deep neural learning with
  access to textual data in electroencephalogram (EEG) reports. We evaluate the performance
  of our model on the problem of inferring the neurologist’s over-all impression (normal
  or abnormal) from electroencephalogram (EEG) reports and report an accuracy of 91.4%
  precision of 94.4% recall of 91.2% and F1 measure of 92.8% (a 40% improvement over
  the performance obtained using Doc2Vec). These promising results demonstrate the
  power of our approach, while error analysis reveals remaining obstacles as well
  as areas for future improvement.
publication: '*Proceedings of the 2017 American Medical Informatics Association (AMIA)
  Summit on Clinical Research Informatics*'
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5543361/
---
