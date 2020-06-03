Welcome.

This is a survival analysis from the TCGA database examining copy number variation in ovarian neoplasms with regards to collagen genes.

This study was cleaned in Alteryx Designer and analysis performed in R.

Three new findings were found to be statistically significant.

This study is my thesis for my Master's in Data Science degree.

1. Unzip all-threasholded.by_genes.rar.

2. Open Alteryx designer and open OVStudy.yxmd.

3. In Alteryx designer load all_threashold.by_genes.CSV and nationwidechildrens.org_clinical_patient_ov.CSV then run workflow.

4. After running workflow, it will create CleanedOVData.csv.

5. If you don't have Alteryx Designer you can see the cleaned dataset, CleanedOVData.CSV.

6. Load Pan-Collagen Gene Survival Analysis in Ovarian Cancer.RMD in R and load CleanedOVData.CSV and run.

7. If you would like to see the HTML file for finished analysis then open the HTML file.

NOTE: Packages Required in R for viewing.

library(ggplot2)
library(survival)
library(survminer)
library(dplyr)
library(tidyverse)
library(funModeling) 
library(Hmisc)
library(DataExplorer)
library(splines)
library(lattice)
