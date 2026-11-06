# CoverCrop-SoilHealth

Data and R code for "Effects of cover crops on soil health: A global meta-analysis".

The analysis uses 8,898 paired observations from 477 studies and 22 soil health indicators. It covers log response ratios (lnRR), multilevel random-effects models (`metafor`), subgroup analysis, a study-level correlation network and an AHP-weighted soil health index.

All analyses were performed in R version 4.5.1. The code (`SoilHealthDB_V2_CC.Rmd`) can be run by loading the required packages and reading the data file in `data/`. Figures are written to `outputs/`. Gridded covariates (SoilGrids, Global Aridity Index) are already included in the data file; download links are given in the code. The average running time is about 5 minutes.

Contact: xpd@nwafu.edu.cn, jinshi@nwafu.edu.cn
