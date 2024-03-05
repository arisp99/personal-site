---
title: "coiaf: Directly Estimating Complexity of Infection with Allele Frequencies"
authors: 
- arisp99
- Oliver J. Watson
- Ozkan Aydemir
- Robert J. Verity
- Jeffrey A. Bailey
author_notes:
- "These authors contributed equally to this work."
- "These authors contributed equally to this work."
date: 2023-06-09
doi: "10.1371/journal.pcbi.1010247"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-10

# Publication type.
# Legend: 0 = Uncategorized; 1 = Journal article; 2 = Preprint;
# 3 = Working Paper; 4 = Conference paper; 5 = Oral presentation; 
# 6 = Poster presentation; 7 = Thesis; 8 = Book; 9 = Book Section
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*PLOS Computational Biology*"
publication_short: ""

# Abstract and optional shortened version
abstract: "In malaria, individuals are often infected with different parasite
strains. The complexity of infection (COI) is defined as the number of
genetically distinct parasite strains in an individual. Changes in the mean COI
in a population have been shown to be informative of changes in transmission
intensity with a number of probabilistic likelihood and Bayesian models now
developed to estimate the COI. However, rapid, direct measures based on
heterozygosity or *FwS* do not properly represent the COI. In this work, we
present two new methods that use easily calculated measures to directly estimate
the COI from allele frequency data. Using a simulation framework, we show that
our methods are computationally efficient and comparably accurate to current
approaches in the literature. Through a sensitivity analysis, we characterize
how the distribution of parasite densities, the assumed sequencing depth, and
the number of sampled loci impact the bias and accuracy of our two methods.
Using our developed methods, we further estimate the COI globally from
*Plasmodium falciparum* sequencing data and compare the results against the
literature. We show significant differences in the estimated COI globally
between continents and a weak relationship between malaria prevalence and COI."
summary: ""

tags: ["complexity of infection", "COI", "malaria", "estimation", "optimization", "allele frequencies"]
featured: false

# Links
links:
  - icon: biorxiv
    icon_pack: ai
    name: Preprint
    url: "https://www.biorxiv.org/node/2568465.abstract"
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/bailey-lab/coiaf
  - name: "Package"
    url: "../../project/coiaf"
  - name: "Data Analysis"
    url: "../../project/coiaf-real-data"
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
