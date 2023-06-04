---
title: "Changes in Plasma Extracellular RNAs: Independent Associations with Left and Right Ventricular Reverse Remodeling"
authors: ["Dimitrios Varrias", "arisp99", "Sam Michelhaugh", "Avash Das", "Ashish Yeri", "Aferdita Spahillari", "James Januzzi", "Ravi Shah", "Mike Silverman", "Saumya Das"]
date: 2019-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-21T01:01:19.359832Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Journal article; 2 = Preprint;
# 3 = Working Paper; 4 = Conference paper; 5 = Oral presentation; 
# 6 = Poster presentation; 7 = Thesis; 8 = Book; 9 = Book Section
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: "Presented at: Cardiovascular Research Center Retreat"
publication_short: ""

# Abstract and optional shortened version
abstract: ""
summary: ""

tags: ["heart failure", "HF", "ventricular remodeling", "exRNA"]
featured: false

# Links
# links:
#  - name: ""
#    url: ""
url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: "exRNA_LV_RV_poster.pdf"
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

## Introduction

Right ventricular (RV) systolic dysfunction is a prognostic marker in chronic
heart failure (HF). However, reliable assessment of RV function remains a
challenge. We examined the correlation of commonly used RV function  parameters
with i) markers of left ventricular (LV) remodeling and ii) dynamic changes in
levels of plasma extracellular RNAs (exRNAs) in patients with chronic HF. We
then created models using linear regression, regression trees and random forests
in order to investigate the association between changes of exRNAs with the
dynamic process of cardiac remodeling.

## Sample

For PEARL–HF, we recruited 153 patients with chronic heart failure. The mean age
of our sample was 66 years of age and 77\% of the population were men. Heart
failure was due to ischemic causes in 53\% of our population.

## Methodology

RV function was assessed at 2 sequential time points using standard and tissue
Doppler echocardiography by measuring RV fractional area change (RVFAC),
tricuspid annular plane systolic excursion (TAPSE), right ventricle systolic
pressure (RVSP)and S prime. LV function was assessed by measuring ejection
fraction (EF), left ventricle end systolic diameter (LVESD) and left ventricle
end diastolic diameter(LVEDD). ExRNAs previously identified as associated with
LV remodeling were assessed by a microfluidics-based PCR assay on plasma from 2
sequential visits.

We utilized Pearson correlation to discover our strongest candidates for
associating exRNAs with right and left ventricular reverse remodeling. We then
employed multivariate linear regressions to understand the miRNA’s predictive
strength. A LASSO linear regression was performed, and the most important miRNA
were kept in the model. Using the selected miRNAs, three models were created i)
Linear regression, ii) Cart (Regression trees), iii) Random forests. Regression
Trees (CART) and Random Forests were used to understand any non-linear
relations. We then proceeded to an internal validation of our models,
bootstrapping with 90\% training sets and 10\% testing sets, running loops of
1000, 5000, and 10000 times, every time with a different random split.

## Results

Among the RV function assessment modalities in the context of cardiac reverse
remodeling, we found that an improvement in RVFAC was most strongly associated
with an increase in LVEF. We created a linear regression model predicting delta
in RVFAC using miR.1228.5p, miR.144.3p, miR.144.3p, miR.185.3p, and miR.499a.5p
with adj R2 = 0.2037, p < 0.02. These findings were independent of delta LVEF. We
then created a similar regression model predicting delta LVEF using miR.122.5p,
miR.1228.5p, miR.185.3p, miR.193a.5p, and pir.57322 with adj R2 = 0.5015 p <
0.001. When we performed our internal validation using the 90/10 splits we
observed similar results in the predictive power of our models.

## Conclusions

Changes in RVFAC better reflect changes in left ventricular remodeling. Changes
in RVFAC were associated with changes in plasma levels of miR.1228.5p,
miR.144.3p, miR.144.3p, miR.185.3p, and miR.499a.5p. Changes in LVEF were
associated with changes in miR.122.5p,  miR.1228.5p, miR.185.3p, miR.193a.5p,
and pir.57322. ExRNAs could be used for the creation of models that could
independently “predict” a change in right and left ventricular function. Further
validation in complimentary datasets is needed.
