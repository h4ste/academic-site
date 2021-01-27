---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Automatic Recognition of Symptom Severity from Psychiatric Evaluation Records
subtitle: ''
summary: ''
authors:
- Travis R Goodwin
- Ramon Maldonado
- Sanda M Harabagiu
tags:
- '"symptom severity"'
- '"ridge regression"'
- '"pairwise transform"'
- '"random forest"'
- '"support vector machine"'
- '"healthcare informatics"'
categories: []
date: '2017-01-01'
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
projects: []
publishDate: '2021-01-27T23:37:25.077137Z'
publication_types:
- '2'
abstract: "This paper presents a novel method for automatically recognizing symptom\
  \ severity by using natural language processing of psychiatric evaluation records\
  \ to extract features that are processed by machine learning techniques to assign\
  \ a severity score to each record evaluated in the 2016 RDoC for Psychiatry Challenge\
  \ from CEGS/N-GRID. The natural language processing techniques focused on (a) discerning\
  \ the discourse information expressed in questions and answers;  (b) identifying\
  \ medical concepts that relate to mental disorders; and (c) accounting for the role\
  \ of negation. The machine learning techniques rely on the assumptions that (1)\
  \ the severity of a patient's positive valence symptoms exists on a latent continuous\
  \ spectrum; and (2) all the patient's answers and narratives documented in the psychological\
  \ evaluation records are informed by the patient's latent severity score along this\
  \ spectrum. These assumptions motivated our two-step machine learning framework\
  \ for automatically recognizing psychological symptom severity. In the first step,\
  \ the latent continuous severity score is inferred from each record; in the second\
  \ step, the severity score is mapped to one of the four discrete severity levels\
  \ used in the CEGS/N-GRID challenge. We evaluated three methods for inferring the\
  \ latent severity score associated with each record: (i) pointwise ridge regression;\
  \ (ii) pairwise comparison-based classification; and (iii) a hybrid approach combining\
  \ pointwise regression and the pairwise classifier. The second step was implemented\
  \ using a tree of cascading support vector machine (SVM) classifiers. These evaluation\
  \ results enabled us to observe that, for this task, considering pairwise information\
  \ can produce more accurate severity scores than pointwise regression -- an approach\
  \ widely used in other systems for assigning severity scores. Moreover, our analysis\
  \ indicates that using a cascading SVM tree outperforms traditional SVM classification\
  \ methods for the purpose of determining discrete severity levels."
publication: '*Journal of Biomedical Informatics*'
url_pdf: https://doi.org/10.1016/j.jbi.2017.05.020
doi: 'DOI: 10.1016/j.jbi.2017.05.020'
---
