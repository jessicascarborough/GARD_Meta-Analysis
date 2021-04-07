# GARD_Meta-Analysis
 
**Summary:**

Background: The Genomic Adjusted Radiation Dose (GARD) is a quantification of personalized RT dose effect. In order to evaluate the potential to improve outcomes compared to physical RT dose alone, a pan-cancer, pooled analysis was conducted.

Methods: The analysis was conducted using 9 previously-published datasets. Two clinical endpoints were defined: (i) time to first recurrence and (ii) overall survival, with 1,257 (972 +RT, 285 -RT) and 636 patients (414 +RT, 222 -RT), respectively. Cox regression stratified by disease site was done with the [rms](https://cran.r-project.org/web/packages/rms/index.html) package in R to test association between GARD and outcome, with separate models using RT dose and sham-GARD for comparison. 

Results:  Pooled analysis reveals GARD is a linear predictor of recurrence (HR = 0.984, CI [0.982,0.996], p=0.004) and survival (HR = 0.975, CI [0.958, 0.993], p=0.005). Interaction between GARD and Treatment (with or without radiotherapy) was significant for overall survival (p =0.026) and for recurrence in the subset of patients who achieved GARD>19.2 (p=0.04). Physical RT dose and sham-GARD were not significantly associated with either outcome.


**Files:**

The R code used to conduct the analysis is available in the '.RMD' file, with the output tables and figures shown in the '.PDF' file. Data for all cohorts is available in CSV and data frame format. 
