---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "CHF Progression"
summary: "Develop models of CHF progression from longitudinal sequences of medical notes."
authors: []
tags: []
categories: []
date: 2021-01-28T13:23:05-05:00

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
One of the most significant differences between information retrieval and question answering systems operating on general domain text and medical texts is the role of _longitudinal_ information -- that is, accounting for the fact that the information recorded in EHRs changes over time for each patient. There are an estimated 136.3 million emergency department visits each year in the United States. Of these emergency department visits, 12% (16.4 million) result in hospital admissions, generating in an average hospital stay of 4.8 days. In each of these hospitalizations, clinicians generate multiple electronic health records (EHRs) which document a wide variety of clinical observations, such as the patient's diagnoses, risk factors, medications, and test results. This explosion of rich clinical information offers an exciting opportunity to substantially improve the quality of health care. Specifically, the United States government has outlined four major goals for widespread EHR adoption:
1. _Track_ data over time;
2. _Identify_ patients who are due for preventive visits and screenings;
3. _Monitor_ how patients measure up to certain parameters, such as vaccinations and blood pressure readings; and
4. _Improve_ overall quality of care in a practice 

This project aims to explore the progression of heart failure for a cohort of diabetic patients as evidenced by implicit and explicit mentions of risk factors and relevant medications in longitudinal medical records.