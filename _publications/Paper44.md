---
title: "RWD112 Can ML-Extracted Variables Reproduce Real World Comparative Effectiveness Results From Expert-Abstracted Data? A Case Study in Metastatic Non-Small Cell Lung Cancer Treatment."
date: 2018-11-18T12:33:46+10:00
weight: 44
---

A Sondhi, C Benedum, AB Cohen, S Nemeth, **S Bozkurt**.

<!--more-->

# Objectives
In generating real world data (RWD), machine learning (ML) extraction of clinical characteristics from unstructured text (e.g. clinical notes) in electronic health records (EHRs) is more cost-effective and scalable than manual abstraction. Proper evaluation that goes beyond standard ML metrics is needed to determine whether ML-extracted variables are fit for research use [1]. This study evaluates reproducibility of scientific conclusions when using expert-abstracted versus ML-extracted data in comparing the effectiveness on real-world overall survival (rwOS) of bevacizumab-carboplatin-paclitaxel (BCP) versus carboplatin-paclitaxel (CP) for first-line treatment of non-squamous metastatic non-small cell lung cancer (mNSCLC).
# Methods
Using a sample of 159,000 patients with a lung cancer ICD code from Flatiron Health’s nationwide (US-based) EHR-derived de-identified database, we obtained diagnosis dates, group stage, histology, PD-L1/ALK/EGFR/ROS1/KRAS/BRAF biomarker status, and smoking status using ML-extraction models trained with expert-abstracted data. Two cohorts with a non-squamous mNSCLC diagnosis (2011-2021) receiving first-line treatment with BCP or CP were identified using either expert-abstracted or ML-extracted variables, along with additional structured variables (e.g. treatments). We compared patient characteristics between these cohorts using standardized mean differences (SMD). After applying inverse propensity weighting to adjust for confounders, the hazard ratio (HR) of rwOS between treatment groups was estimated in both cohorts.
# Results
The cohort selected using ML-extracted variables (n=676) largely overlapped with the expert-abstracted cohort (n=676) with overall sensitivity and PPV of 84%. The cohorts showed similar distributions (SMD<0.1) across all baseline characteristics. The estimated HR for the abstracted cohort was 0.90 (95% CI: 0.75-1.08), and 0.87 (95% CI: 0.73-1.04) for the ML-extracted cohort, in favour of BCP.
# Conclusions
Identical comparative effectiveness analyses for both cohorts resulted in similar effect estimates and the same analytical conclusions. Our study demonstrates that oncology RWD extracted using high-performing ML models may be used as an alternative to expert-abstraction.