---
title: "Predictive Models of Mortality for Hospitalized Patients With COVID-19: Retrospective Cohort Study"
authors: ["Taiyao Wang", "arisp99", "Quanying Liu", "Yingxia Liu", "Ye Yuan", "Ioannis Ch Paschalidis"]
date: "2020-10-01"
doi: "10.2196/21788"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-21T01:01:19.360866Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Journal article; 2 = Preprint;
# 3 = Working Paper; 4 = Conference paper; 5 = Oral presentation; 
# 6 = Poster presentation; 7 = Thesis; 8 = Book; 9 = Book Section
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Medical Internet Research Medical Informatics*"
publication_short: ""

# Abstract and optional shortened version
abstract: "
**Background:** The novel coronavirus SARS-CoV-2 and its associated disease,
COVID-19, have caused worldwide disruption, leading countries to take drastic
measures to address the progression of the disease. As SARS-CoV-2 continues to
spread, hospitals are struggling to allocate resources to patients who are most
at risk. In this context, it has become important to develop models that can
accurately predict the severity of infection of hospitalized patients to help
guide triage, planning, and resource allocation.\n\n
**Objective:** The aim of this study was to develop accurate models to predict
the mortality of hospitalized patients with COVID-19 using basic demographics
and easily obtainable laboratory data.\n\n
**Methods:** We performed a retrospective study of 375 hospitalized patients
with COVID-19 in Wuhan, China. The patients were randomly split into derivation
and validation cohorts. Regularized logistic regression and support vector
machine classifiers were trained on the derivation cohort, and accuracy metrics
(F1 scores) were computed on the validation cohort. Two types of models were
developed: the first type used laboratory findings from the entire length of the
patient's hospital stay, and the second type used laboratory findings that were
obtained no later than 12 hours after admission. The models were further
validated on a multicenter external cohort of 542 patients.\n\n
**Results:** Of the 375 patients with COVID-19, 174 (46.4%) died of the
infection. The study cohort was composed of 224/375 men (59.7%) and 151/375
women (40.3%), with a mean age of 58.83 years (SD 16.46). The models developed
using data from throughout the patients' length of stay demonstrated accuracies
as high as 97%, whereas the models with admission laboratory variables possessed
accuracies of up to 93%. The latter models predicted patient outcomes an average
of 11.5 days in advance. Key variables such as lactate dehydrogenase,
high-sensitivity C-reactive protein, and percentage of lymphocytes in the blood
were indicated by the models. In line with previous studies, age was also found
to be an important variable in predicting mortality. In particular, the mean age
of patients who survived COVID-19 infection (50.23 years, SD 15.02) was
significantly lower than the mean age of patients who died of the infection
(68.75 years, SD 11.83; P$<$.001).\n\n
**Conclusions:** Machine learning models can be successfully employed to
accurately predict outcomes of patients with COVID-19. Our models achieved high
accuracies and could predict outcomes more than one week in advance; this
promising result suggests that these models can be highly useful for resource
allocation in hospitals."
summary: ""

tags: ["coronavirus", "COVID-19", "mortality", "machine learning", "predictive modeling", "regression", "logistic regression", "support vector machine"]
featured: false

# Links
# links:
#  - name: ""
#    url: ""
url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
