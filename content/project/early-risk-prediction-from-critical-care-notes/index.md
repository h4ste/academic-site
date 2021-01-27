---
title: Early Risk Prediction from Critical Care Notes
subtitle: ""
date: 2021-01-27T18:48:17.424Z
summary: Developing data-driven approaches for modeling disease processes from
  longitudinal clinical data to enable robust prognostication without
  disease-specific feature engineering.
draft: false
featured: true
tags:
  - Deep Learning
categories: []
external_link: "#"
links: []
image:
  filename: cantrip.png
  focal_point: Smart
  preview_only: false
  caption: A reCurrent Additive Network for Temporal RIsk Prediction (CANTRIP)
---
The Centers for Disease Control (CDC) estimates that one in every twenty-five acute care hospitalizations results in a healthcare-associated infection (HAI) and that at least 50% of HAIs are preventable.9,10 Other types of preventable hospital acquired or associated disease have been reported with high prevalence.11–13 Modeling such nosocomial (i.e., healthcare-associated) diseases has the potential to reduce costs and lead to improved patient outcomes by enabling early risk prediction.

Predictive modeling has been an active area of medical informatics research over the last decade, with more than 107 studies published between 2011 and 2017.14 However, most risk prediction frameworks used today were developed before the adoption of the electronic health record (EHR), and typically rely on a small number of features (e.g., signs, social factors, basic measurements) easily assessable by the physician.15 In a similar vein, automatic approaches typically rely on hand-chosen disease-specific features easily extracted from the structured portions of the EHR (e.g., laboratory results, vital signs, and chart information). By contrast, we are interested in discovering whether the information documented in unstructured clinical narratives could supplement or exceed the traditional information contained in structured (i.e., tabular) parts of the EHR by enabling more robust prognostication of disease.

The goal of this project is to develop novel computational approaches for predicting healthcare-associated diseases from longitudinal clinical notes. In this project, we rely on the MIMIC-III Critical Care Database.1 MIMIC is an openly-available database developed by the Massachusetts Institute of Technology (MIT) Lab for Computation Physiology to support research in intelligent patient monitoring containing de-identified health data associated with 40,000 ICU patients. While MIMIC provides structured information (e.g., demographics, charts, laboratory tests, medications, and diagnoses), in this project, to evaluate the impact of clinical notes for predicting disease risk, we only considered the information contained in clinical notes. MIMIC has a variety of unstructured clinical notes including progress reports, radiology reports, nursing notes, etc.