---
title: Power Analysis
authors: 
  - arisp99
date: "2023-07-27"
lastmod: "2023-07-27T11:37:30+03:00"
slug: power-analysis
featured: false
projects: []

summary: "A brief introduction to power analysis."
subtitle: "A brief introduction to power analysis."

categories:
- Blogs
tags:
  - power
  - effect size

image:
  caption: ''
  focal_point: ""
  placement: 1
  preview_only: true
---

We define **power** as: "the probability that, given a specified true difference
between two groups, the quantitative results of a study will be deemed
statistically significant." In mathematical terms, power is defined as
$1-\beta$, where $\beta$ is the type II error, i.e., failing to reject the null
when it should have been rejected.

The calculation for power involves four key variables, power being one of them:
1. Power
2. Alpha (significance level)
3. Sample size
4. Effect size

Power analyses are often conducted a priori, where a desired sample size can be
computed based on the other factors. In this case, a power of 0.8 is often
desirable, and the alpha value is set to 0.05. The effect size can be
interpreted as the "minimum clinically important difference." In other words,
the difference that an investigator wants to detect between study groups. The
effect size depends on the problem and the field being examined.

A power analysis can also be conducted after a study's completion. In this case,
the sample size and alpha will be fixed. Given that the study has already been
completed, there exists an _observed effect size_, which is calculated directly
from the data. If one were to compute the power using this observed effect size,
the power would yield little additional information to the already known
p-value. As a result, this post hoc power analysis would not be particularly
useful.

An alternative option is to conduct a power sensitivity analysis. We can
estimate various detectable effect sizes as we change the power. We define the
effect size at a power of 0.8 as the _minimum detectable effect size_ or MDES.
Note that this value depends on the known sample size and will decrease as the
sample size increases, i.e., a study with a larger sample size will have a
smaller MDES. If the MDES is small, it means our study can detect small
differences between study cohorts. We can additionally define a *theoretical
effect size of interest*. This effect size is problem specific and indicates the
effect size that we believe to be practically significant. Note that this is the
same effect size that would have been used in an a priori power analysis.

Given the observed p-value, observed effect size, the minimum detectable effect
size, and the theoretical effect size of interest, we can make additional
conclusions about our study. A comparison of the observed and minimum detectable
effect size suggests whether a result is significant. If the observed effect
size is greater than the minimum detectable effect size, it suggests that the
results are significant. The larger the observed effect size, the larger the
difference we found between the study cohorts. A comparison of the minimum
detectable effect size and the theoretical effect size of interest indicates
whether a study is over or underpowered. If the minimum detectable effect size
is smaller than the theoretical effect size of interest, our study is
appropriately powered. Otherwise, our study is underpowered. To think of this
differently, if the minimum detectable effect size is greater than the
theoretical effect size of interest, our study cannot ascertain differences that
we consider to be theoretically or practically relevant, i.e., it is
underpowered.

If no theoretical effect size of interest is known post-hoc, one cannot
definitively determine if a study is over or underpowered. However, it can be
concluded that the study is adequately powered to detect effect sizes greater
than the minimum detectable effect size. For example, consider the case where
the MDES was 0.3. The study would then be adequately powered for effect sizes
greater than 0.3 but would be unable to detect effect sizes less than 0.3. In
other words, the study cannot detect very small differences between cohorts.


## References
1. Campbell MJ, Julious SA, Altman DG. Estimating sample sizes for binary,
ordered categorical, and continuous outcomes in two group comparisons. _BMJ_.
1995;311(7013):1145-1148.
2. Champely S. _Pwr: Basic Functions for Power Analysis_.; 2020.
[https://CRAN.R-project.org/package=pwr](https://CRAN.R-project.org/package=pwr)
3. Copay AG, Subach BR, Glassman SD, Polly DW, Schuler TC. Understanding the
minimum clinically important difference: a review of concepts and methods. _The
Spine Journal_. 2007;7(5):541-546.
doi:[10.1016/j.spinee.2007.01.008](https://doi.org/10.1016/j.spinee.2007.01.008)
4. Goodman SN. The Use of Predicted Confidence Intervals When Planning
Experiments and the Misuse of Power When Interpreting Results. _Ann Intern Med_.
1994;121(3):200.
doi:[10.7326/0003-4819-121-3-199408010-00008](https://doi.org/10.7326/0003-4819-121-3-199408010-00008)
5. Greenland S. On sample-size and power calculations for studies using
confidence intervals. _Am J Epidemiol_. 1988;128(1):231-237.
doi:[10.1093/oxfordjournals.aje.a114945](https://doi.org/10.1093/oxfordjournals.aje.a114945)
6. Gupta K, Attri J, Singh A, Kaur H, Kaur G. Basic concepts for sample size
calculation: Critical step for any clinical trials! _Saudi J Anaesth_.
2016;10(3):328-331.
doi:[10.4103/1658-354X.174918](https://doi.org/10.4103/1658-354X.174918)
7. Hoenig JM, Heisey DM. The Abuse of Power. _The American Statistician_.
2001;55(1):19-24.
doi:[10.1198/000313001300339897](https://doi.org/10.1198/000313001300339897)
8. King MT. A point of minimal important difference (MID): a critique of
terminology and methods. _Expert Rev Pharmacoecon Outcomes Res_.
2011;11(2):171-184. doi:[10.1586/erp.11.9](https://doi.org/10.1586/erp.11.9)
9. Lakens D. Calculating and reporting effect sizes to facilitate cumulative
science: a practical primer for t-tests and ANOVAs. _Front Psychol_. 2013;4:863.
doi:[10.3389/fpsyg.2013.00863](https://doi.org/10.3389/fpsyg.2013.00863)
10. Lakens D. Sample Size Justification. _Collabra: Psychology_.
2022;8(1):33267.
doi:[10.1525/collabra.33267](https://doi.org/10.1525/collabra.33267)
11. Lakens D. The 20% Statistician: Observed power, and what to do if your
editor asks for post-hoc power analyses. The 20% Statistician. Published
December 19, 2014. Accessed April 29, 2023.
[https://daniellakens.blogspot.com/2014/12/observed-power-and-what-to-do-if-your.html](https://daniellakens.blogspot.com/2014/12/observed-power-and-what-to-do-if-your.html)
12. mzunhammer. Answer to “How to interpret sensitivity power analyses?” Cross
Validated. Published February 6, 2020. Accessed April 29, 2023.
[https://stats.stackexchange.com/a/448169](https://stats.stackexchange.com/a/448169)
13. Quertemont E. How to Statistically Show the Absence of an Effect.
2011;51(2):109. doi:[10.5334/pb-51-2-109](https://doi.org/10.5334/pb-51-2-109)
14. Raittio L, Reito A. Assessing variability and uncertainty in orthopedic
randomized controlled trials. _Acta Orthop_. 91(4):479-484.
doi:[10.1080/17453674.2020.1755932](https://doi.org/10.1080/17453674.2020.1755932)
15. RPubs - Sample size estimation and Power analysis in R. Accessed April 29, 2023. [https://rpubs.com/mbounthavong/sample_size_power_analysis_R](https://rpubs.com/mbounthavong/sample_size_power_analysis_R)
16. Williamson M. Sample Size Calculation with R.
