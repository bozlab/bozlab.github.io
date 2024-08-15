---
title: "P57 machine learning-accelerated outcomes research: A real-world case study of biomarker-associated overall survival in oncology."
date: 2018-11-18T12:33:46+10:00
weight: 45
---

C Benedum, B Adamson, AB Cohen, M Estevez, A Sondhi, E Fidyk, S Nemeth, **S Bozkurt**.

<!--more-->
# Objectives
Meaningful outcomes research requires unstructured data found in electronic health records (EHRs) which are often missing from administrative claims. Historically, clinical experts manually review charts, a resource intensive process. Researchers have developed machine learning (ML) models to recognize patterns in language documenting characteristics of interest and extract clinically relevant information. We explored the impact of data curation method (expert-abstraction vs ML-extraction) on the association between real-world overall survival (rwOS) and ROS1 rearrangement status in advanced non-small cell lung cancer (aNSCLC).
# Methods
Using a sample of 159,000 patients with a lung cancer ICD code from Flatiron Health’s nationwide (US-based) EHR-derived de-identified database, we extracted diagnosis dates, stage, histology, ROS1/ALK/EGFR/BRAF/PD-L1 status, and oral therapies from text documents using ML-models trained on expert-abstracted data. Two populations with an aNSCLC diagnosis (2011-May2021), ever-tested for ROS1 were defined using: 1) expert-abstracted variables 2) ML-extracted variables. Structured variables were used for both populations (e.g., age). Patients ever-positive for ROS1 were compared with ROS1-negative and ALK/BRAF/EGFR never-positive. We compared patient characteristics by data curation method using standardized mean differences (SMD). We evaluated the association between ROS1 status and rwOS using matched analysis and adjusted Cox regression.
# Results
Population selected using multiple ML-extracted variables achieved sensitivity and PPV of: 83% and 86% (ROS1-positive) and 82% and 90% (ROS1-negative). Abstracted (N=21,362) and ML-extracted (N=23,660) populations had similar ROS1 prevalence (1.2% and 1.1%) and didn’t differ (SMD<0.1) by gender, practice type, race, age, advanced diagnosis year, histology, ECOG Performance Status and PD-L1 status, but differed by stage and therapies received (SMDs=0.11-0.13). No association was found between ROS1 status and rwOS in expert-abstracted and ML-extracted populations (Hazard Ratio [95%CI]: 0.98[0.83-1.12] and 0.95[0.82-1.12], respectively).
# Conclusions
When using multiple, high-performance ML-extracted variables trained on expert-abstracted oncology data, similar results can be achieved as when using abstracted data, unlocking the ability to perform outcomes research at scale.