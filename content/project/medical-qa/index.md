---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Medical Question Answering"
summary: "Advancing automatic question answering to support different medical use cases including clinical decision support, consumer question answering, and literature review"
authors: []
tags: []
categories: []
date: 2021-01-28T13:18:34-05:00

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
At the intersection of natural language processing, information retrieval, and artificial intelligence, *question answering* (Q/A) has been a major focus of research for nearly six decades. The role of a question answering system is, given an _information need_ posed as a natural language _question_, to identify and present the best _answer_ from a pre-specified _information source_. An _information need_ is the real-world catalyst that leads the user to pose his or her question. For example, if a user were planning a trip to Italy to visit historic museums, it is likely that he or she may be interested in discovering the oldest museum in Italy. Thus, in this scenario, the user's information need would be to discover the oldest museum in Italy. In order to satisfy their information  need, the user would interact with the question answering system by providing a question as input to the system. Thus, the _question_ can be seen as the natural language realization of the user's information  need. For example, the user's information need may be expressed by the question "What is the oldest museum in Italy?". The role of the question answering system is to satisfy the user's information need by providing the best answer to the given question. The _answer_ is the entity, concept, or expression in the information source that is mostly likely to satisfy the user's information need as expressed by the question. In our example, the question answering system would identify the oldest museum in Italy -- _Musei Capitolini_ (established in 1471) -- and return that information to the user. In order to produce an answer, typical question answering system relies on a pre-specified _information source_, which is typically a knowledge base, database, or text collection from which all answers must be derived. Recently, however, many Q/A systems have considered a question answering scenario in which some aspect of the information source is _dynamic_ and may change with each question. Specifically, recent research considers an alternative question answering setting in which the question answering system is provided with both a question and a _background_ passage providing additional context used to produce an answer.

In this project, we focus on medical question answering problems with an emphasis on medical question answering for clinical decision support in which the background of a question corresponds to a description of a patient's medical case and the questions correspond to identifying the best medical treatment, medical test, or diagnosis for the patient. Consider the following medical case description:
> The patient is a 65 y/o male with no significant history of cardiovascular disease presents to the emergency room with acute onset of shortness of breath, tachypnea, and left-sided chest pain that worsens with inspiration. Of note, he underwent a right total hip replacement two weeks prior to presentation and  was unable to begin physical therapy and rehabilitation for several days following the surgery due to poor pain management. Relevant physical exam findings include a respiratory rate of 35 and right calf pain.

If this medical case were provided as the _background_ for the question, "What is the most likely Diagnosis?", we want to automatically discover and provide the answer _Pulmonary Embolism_. Clearly, answering this question requires accounting for the information in the question's background, as well as medical knowledge from an information source. Exploring this process is the goal of this project.