---
title: "Assessment of a clinical trial–derived survival model in patients with metastatic castration-resistant prostate cancer"
date: 2019-04-18T12:33:46+10:00
weight: 37
---


Jean Coquet, Nicolas Bievre, Vincent Billaut, Martin Seneviratne, Christopher J Magnani, **Selen Bozkurt**, James D Brooks, and Tina HernandezBoussard. 


# Importance  
Randomized clinical trials (RCTs) are considered the criterion standard for clinical evidence. Despite their many benefits, RCTs have limitations, such as costliness, that may reduce the generalizability of their findings among diverse populations and routine care settings.

# Objective  
To assess the performance of an RCT-derived prognostic model that predicts survival among patients with metastatic castration-resistant prostate cancer (CRPC) when the model is applied to real-world data from electronic health records (EHRs).

# Design, Setting, and Participants  
The RCT-trained model and patient data from the RCTs were obtained from the Dialogue for Reverse Engineering Assessments and Methods (DREAM) challenge for prostate cancer, which occurred from March 16 to July 27, 2015. This challenge included 4 phase 3 clinical trials of patients with metastatic CRPC. Real-world data were obtained from the EHRs of a tertiary care academic medical center that includes a comprehensive cancer center. In this study, the DREAM challenge RCT-trained model was applied to real-world data from January 1, 2008, to December 31, 2019; the model was then retrained using EHR data with optimized feature selection. Patients with metastatic CRPC were divided into RCT and EHR cohorts based on data source. Data were analyzed from March 23, 2018, to October 22, 2020.

# Exposures  
Patients who received treatment for metastatic CRPC.

# Main Outcomes and Measures
The primary outcome was the performance of an RCT-derived prognostic model that predicts survival among patients with metastatic CRPC when the model is applied to real-world data. Model performance was compared using 10-fold cross-validation according to time-dependent integrated area under the curve (iAUC) statistics.

# Results  
Among 2113 participants with metastatic CRPC, 1600 participants were included in the RCT cohort, and 513 participants were included in the EHR cohort. The RCT cohort comprised a larger proportion of White participants (1390 patients [86.9%] vs 337 patients [65.7%]) and a smaller proportion of Hispanic participants (14 patients [0.9%] vs 42 patients [8.2%]), Asian participants (41 patients [2.6%] vs 88 patients [17.2%]), and participants older than 75 years (388 patients [24.3%] vs 191 patients [37.2%]) compared with the EHR cohort. Participants in the RCT cohort also had fewer comorbidities (mean [SD], 1.6 [1.8] comorbidities vs 2.5 [2.6] comorbidities, respectively) compared with those in the EHR cohort. Of the 101 variables used in the RCT-derived model, 10 were not available in the EHR data set, 3 of which were among the top 10 features in the DREAM challenge RCT model. The best-performing EHR-trained model included only 25 of the 101 variables included in the RCT-trained model. The performance of the RCT-trained and EHR-trained models was adequate in the EHR cohort (mean [SD] iAUC, 0.722 [0.118] and 0.762 [0.106], respectively); model optimization was associated with improved performance of the best-performing EHR model (mean [SD] iAUC, 0.792 [0.097]). The EHR-trained model classified 256 patients as having a high risk of mortality and 256 patients as having a low risk of mortality (hazard ratio, 2.7; 95% CI, 2.0-3.7; log-rank P < .001).

# Conclusions and Relevance 
In this study, although the RCT-trained models did not perform well when applied to real-world EHR data, retraining the models using real-world EHR data and optimizing variable selection was beneficial for model performance. As clinical evidence evolves to include more real-world data, both industry and academia will likely search for ways to balance model optimization with generalizability. This study provides a pragmatic approach to applying RCT-trained models to real-world data.