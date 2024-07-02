# carlson-2024-JNP-plx-ethanol

## Overview 
This repository contains data and code used for the analyses presented in the manuscript titled "Pharmacological depletion of microglia protects from alcohol-induced corticolimbic neurodegeneration in male rats" (Carlson, Melbourne, and Nixon, in submission, *Journal of Neuroimmune Pharmacology*).

The RMarkdown document titled "MGD_Analyses.Rmd" includes R code to:
- Read cell count (Iba1+ for microglia or FJB+ for dying neurons) data
- Conduct two-way ANOVA on cell count data with drug (PLX5622 vs vehicle) and diet (ethanol vs control) as between-subjects factors along with pairwise comparisons of simple effects with Bonferroni correction when appropriate.
- Read data related to intoxication behavior, ethanol dose, and blood ethanol concentrations and conduct Welch t-tests.

## ***data*** Directory
The ***data*** directory includes the following files:
- 

NOTES:
- All data files are in comma separated value (".csv") format.

## ***data/results*** Directory
The ***data/results*** directory includes the results of the statistical analyses. These files have the following names:
- 

## References
Data analysis was conducted in RStudio v2023.12.1.402 (Posit team, 2024) with R v4.2.2 (R Core Team, 2022) using rstatix (Kassambara, 2022), afex (Singmann et al., 2023), and emmeans (Lenth, 2022) packages with visualization in Prism v10.0.3 (GraphPad).
- Kassambara A (2022). _rstatix: Pipe-Friendly Framework for Basic
  Statistical Tests_. R package version 0.7.1,
  <https://CRAN.R-project.org/package=rstatix>.
- Lenth R (2022). _emmeans: Estimated Marginal Means, aka Least-Squares
  Means_. R package version 1.8.3,
  <https://CRAN.R-project.org/package=emmeans>.
- Posit team (2024). RStudio: Integrated Development Environment for R.
  Posit Software, PBC, Boston, MA. URL http://www.posit.co/.
- R Core Team (2022). R: A language and environment for statistical
  computing. R Foundation for Statistical Computing, Vienna, Austria. URL
  https://www.R-project.org/.
- Singmann H, Bolker B, Westfall J, Aust F, Ben-Shachar M (2023). _afex:
  Analysis of Factorial Experiments_. R package version 1.3-0,
  <https://CRAN.R-project.org/package=afex>.
  
