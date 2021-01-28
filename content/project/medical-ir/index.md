---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Medical Information Retrieval"
summary: "Exploring the role of relevance for patient cohort retrieval and biomedical literature search"
authors: []
tags: []
categories: []
date: 2021-01-28T13:18:37-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Information retrieval is highly related to question answering. In fact, many question answering systems include an information retrieval component. The goal of _information retrieval_ is to identify relevant _information_ from an information source given a (typically natural language) _query_. Unlike question answering, which requires a specific answer be returned in response to a question, information retrieval typically considers only document collections as the information source; thus, information retrieval systems return a _ranked_ list of documents. The notion of ranking is important to information retrieval, with the idea that the _rank_ or position of a document in the ranked list should correspond to the _relevance_ between the document and the query provided by the user. Thus, the ability to accurately estimate the relevance between a document and a query is the central problem addressed by information retrieval, with every component of an information retrieval system contributing, in some way, to improving the ability to estimate relevance. It should be noted that, while question answering systems consider natural language questions, the _query_ processed by information retrieval systems may range from natural language sentences, e.g., "Show me hotels in Lesbon.", to sentence fragments, e.g., "places to eat near Frisco", or just combinations of important words and phrases, e.g., "Mexican restaurants no seafood".

In this project, we focus on a specific application of information retrieval, namely, _patient cohort retrieval_.
Patient cohort retrieval is an important problem in medical research in which a _patient cohort_ is identified from a set of electronic health records given a natural language description of a patient cohort. A patient cohort corresponds to a group of patients who satisfy specific exclusion or inclusion criteria, e.g., "Pregnant women over 30 who are not on insulin" and typically describe candidates for a medical research study or clinical trial. It should be noted that patient cohort retrieval systems are responsible for ranking patients, and that each patient may correspond to multiple documents or EHRs. In this setting, patient cohorts are represented by ranked list of patients where-in the rank or relevance of each patient indicates the degree that the patient satisfies the criteria associated with the cohort.