# survival_analysis

This Rmarkdown file is used for survival anlaysis of gene expression and cell-type proporations in head and neack cancer in TCGA.
THis script is used for paper at https://www.mdpi.com/2072-6694/13/6/1230
Method section: Survival analysis and hazard ratio measurement
Patients were split at the median for each estimated cell type. The prognosis of each group of patients was examined by Kaplan–Meier survival, and log-rank tests compared the survival outcomes. Kaplan–Meier plots are presented for all the cell-type proportions, and the cell types with log-rank p-values less than 0.05 were defined as a prognostic cell type. Hazard ratios (HRs) and corresponding 95% confidence intervals (CIs) for risk of disease progression and mortality associated with high and low percentage of cell types were estimated using the Cox proportional-hazards model. Multivariable Cox model was adjusted for tumor stage, race, smoking status, and age. All statistical analyses were performed using R version 3.6.
