---
title: "Natural language processing approaches to detect the timeline of metastatic recurrence of breast cancer."
date: 2019-06-18T12:33:46+10:00
weight: 23
---

Imon Banerjee, **Selen Bozkurt**, Jennifer Lee Caswell-Jin, Allison W Kurian, and Daniel L Rubin. 

# Purpose
Electronic medical records (EMRs) and population-based cancer registries contain information on cancer outcomes and treatment, yet rarely capture information on the timing of metastatic cancer recurrence, which is essential to understand cancer survival outcomes. We developed a natural language processing (NLP) system to identify patient-specific timelines of metastatic breast cancer recurrence.

# Patients and methods
We used the OncoSHARE database, which includes merged data from the California Cancer Registry and EMRs of 8,956 women diagnosed with breast cancer in 2000 to 2018. We curated a comprehensive vocabulary by interviewing expert clinicians and processing radiology and pathology reports and progress notes. We developed and evaluated the following two distinct NLP approaches to analyze free-text notes: a traditional rule-based model, using rules for metastatic detection from the literature and curated by domain experts; and a contemporary neural network model. For each 3-month period (quarter) from 2000 to 2018, we applied both models to infer recurrence status for that quarter. We trained the NLP models using 894 randomly selected patient records that were manually reviewed by clinical experts and evaluated model performance using 179 hold-out patients (20%) as a test set.

# Results
The median follow-up time was 19 quarters (5 years) for the training set and 15 quarters (4 years) for the test set. The neural network model predicted the timing of distant metastatic recurrence with a sensitivity of 0.83 and specificity of 0.73, outperforming the rule-based model, which had a specificity of 0.35 and sensitivity of 0.88 (P < .001).

# Conclusion
We developed an NLP method that enables identification of the occurrence and timing of metastatic breast cancer recurrence from EMRs. This approach may be adaptable to other cancer sites and could help to unlock the potential of EMRs for research on real-world cancer outcomes.

