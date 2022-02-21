---
title: Regression and classification using optimal decision trees
author: Bertsimas D., Dunn J., Paschalidis A.
date: 2017-11-03
slug: optimal-decision-trees

categories:
  - Conference Proceedings
  - Research
tags:
  - Classification
  - Regression
  - Decision Trees
  - Integer Optimization

summary: 'A study investigating the benefits of an optimal decision tree
approach, which creates the entire decision tree at once using Mixed Integer
Optimization (MIO). We apply these trees on a novel application concerning the
usage of CT imagining to diagnose head injuries in children.'

links:
- icon: doi
  icon_pack: ai
  name: Publication
  url: https://doi.org/10.1109/URTC.2017.8284195
---

## Abstract

Current state-of-the-art decision tree algorithms, such as Classification and
Regression Trees (CART), build the decision tree using a recursive approach
based on a greedy heuristic. We study the benefits of an optimal decision tree
approach, which creates the entire decision tree at once using Mixed Integer
Optimization (MIO). While such problems are known to be hard to solve for large
instances, we leverage modern solver techniques that are able to obtain
near-optimal solutions in a reasonable amount of time. The methodology is able
to handle both single-feature splits, as in CART, and also hyperplane splits
that use multiple features. We test optimal regression trees on a host of
synthetic datasets and optimal classification tress on a novel application
concerning the usage of CT imagining to diagnose head injuries in children. Our
results demonstrate that optimal trees lead to a significantly greater accuracy
than CART.

## Citation

Bertsimas D, Dunn J, **Paschalidis A**. Regression and classification using
optimal decision trees. In: _2017 IEEE MIT Undergraduate Research Technology_
_Conference (URTC)_. ; 2017:1-4.
doi:[10.1109/URTC.2017.8284195](https://doi.org/10.1109/URTC.2017.8284195)

<!---
```bibtex
@inproceedings{bertsimas_regression_2017,
	title = {Regression and classification using optimal decision trees},
	doi = {10.1109/URTC.2017.8284195},
	booktitle = {2017 {IEEE} {MIT} {Undergraduate} {Research} {Technology} {Conference} ({URTC})},
	author = {Bertsimas, Dimitris and Dunn, Jack and Paschalidis, Aris},
	month = nov,
	year = {2017},
	pages = {1--4},
}
```
--->