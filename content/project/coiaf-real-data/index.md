---
title: COI Around the World
author: the Bailey Lab
date: "2022-02-23"
show_date: false
external_link: ""
summary:  Complexity of infection (COI) in _Plasmodium falciparum_ around the
  world using coiaf.
image:  
  placement: 1
  caption: "Photo by [MalariaGEN](https://twitter.com/malariagenomics)."
  focal_point: "Smart"
  preview_only: false
tags:
- Malaria
- Genomics
- R
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/bailey-lab/coiaf-real-data
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
bibliography: references.bib
link-citations: true
csl: ../../../static/csl-files/plos-computational-biology.csl
---

Malaria remains a leading cause of death worldwide—in 2020, there were an
estimated 241 million cases and 627,000 deaths around the globe
\[[1](#ref-organization_world_2021)\]. Despite the considerable burden of malaria, these
numbers represent substantial progress that has been made globally to control
malaria in the last two decades. However, there is evidence that progress has
slowed and that there is a need for new approaches to capitalize on the gains
made \[[2](#ref-organization_world_2020)\].

One approach is the use of computational methods to help inform eradication
efforts, which often rely on recent advances in genetic sequencing and an
increased understanding of malaria biology \[[3](#ref-andrade_towards_2010)–[5](#ref-timmann_genome-wide_2012)\]. While determining the exact
metrics that are most informative is an active field of investigation
\[[6](#ref-watson_evaluating_2021)\], one important metric is the complexity of infection
(COI). The COI represents the number of genetically distinct malaria genomes or
strains that can be identified in a particular individual and has been
increasingly used for inferring malaria transmission intensity and evaluating
malaria control interventions \[[7](#ref-daniels_modeling_2015)\].

Using our newly developed software package,
[coiaf](https://arispas.com/project/coiaf/), we analysed samples from the
MalariaGEN *Plasmodium falciparum* Community Project \[[8](#ref-malariagen_open_2021)\].
The MalariaGEN *Plasmodium falciparum* Community Project provides genomic data
from over 7,000 *P. falciparum* samples from 28 malaria-endemic countries in
Africa, Asia, South America, and Oceania from 2002-2015. Detailed information
about the data release including brief descriptions of contributing partner
studies and study locations is available in the supplementary of MalariaGEN *et
al*.

## References

<div id="refs" class="references csl-bib-body">

<div id="ref-organization_world_2021" class="csl-entry">

<span class="csl-left-margin">1. </span><span class="csl-right-inline">Organization WH. World malaria report 2021. World Health Organization; 2021. </span>

</div>

<div id="ref-organization_world_2020" class="csl-entry">

<span class="csl-left-margin">2. </span><span class="csl-right-inline">Organization WH et al. World malaria report 2020: 20 years of global progress and challenges. 2020. </span>

</div>

<div id="ref-andrade_towards_2010" class="csl-entry">

<span class="csl-left-margin">3. </span><span class="csl-right-inline">Andrade BB, Reis-Filho A, Barros AM, Souza-Neto SM, Nogueira LL, Fukutani KF, et al. Towards a precise test for malaria diagnosis in the Brazilian Amazon: Comparison among field microscopy, a rapid diagnostic test, nested PCR, and a computational expert system based on artificial neural networks. Malaria Journal. 2010;9: 117. doi:[10.1186/1475-2875-9-117](https://doi.org/10.1186/1475-2875-9-117)</span>

</div>

<div id="ref-band_insights_2019" class="csl-entry">

<span class="csl-left-margin">4. </span><span class="csl-right-inline">Band G, Le QS, Clarke GM, Kivinen K, Hubbart C, Jeffreys AE, et al. Insights into malaria susceptibility using genome-wide data on 17,000 individuals from Africa, Asia and Oceania. Nature Communications. 2019;10: 5732. doi:[10.1038/s41467-019-13480-z](https://doi.org/10.1038/s41467-019-13480-z)</span>

</div>

<div id="ref-timmann_genome-wide_2012" class="csl-entry">

<span class="csl-left-margin">5. </span><span class="csl-right-inline">Timmann C, Thye T, Vens M, Evans J, May J, Ehmen C, et al. Genome-wide association study indicates two novel resistance loci for severe malaria. Nature. 2012;489: 443–446. doi:[10.1038/nature11334](https://doi.org/10.1038/nature11334)</span>

</div>

<div id="ref-watson_evaluating_2021" class="csl-entry">

<span class="csl-left-margin">6. </span><span class="csl-right-inline">Watson OJ, Okell LC, Hellewell J, Slater HC, Unwin HJT, Omedo I, et al. Evaluating the Performance of Malaria Genetics for Inferring Changes in Transmission Intensity Using Transmission Modeling. Molecular Biology and Evolution. 2021;38: 274–289. doi:[10.1093/molbev/msaa225](https://doi.org/10.1093/molbev/msaa225)</span>

</div>

<div id="ref-daniels_modeling_2015" class="csl-entry">

<span class="csl-left-margin">7. </span><span class="csl-right-inline">Daniels RF, Schaffner SF, Wenger EA, Proctor JL, Chang H-H, Wong W, et al. Modeling malaria genomics reveals transmission decline and rebound in Senegal. Proceedings of the National Academy of Sciences. 2015;112: 7067–7072. doi:[10.1073/pnas.1505691112](https://doi.org/10.1073/pnas.1505691112)</span>

</div>

<div id="ref-malariagen_open_2021" class="csl-entry">

<span class="csl-left-margin">8. </span><span class="csl-right-inline">MalariaGEN, Ahouidi A, Ali M, Almagro-Garcia J, Amambua-Ngwa A, Amaratunga C, et al. An open dataset of Plasmodium falciparum genome variation in 7,000 worldwide samples. Wellcome Open Research. 2021;6: 42. doi:[10.12688/wellcomeopenres.16168.1](https://doi.org/10.12688/wellcomeopenres.16168.1)</span>

</div>

</div>
