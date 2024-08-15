---
title: "Expanding the secondary use of prostate cancer real world data: Automated classifiers for clinical and pathological stage"
date: 2018-11-18T12:33:46+10:00
weight: 42
---

**Selen Bozkurt**, Christopher J Magnani, Martin G Seneviratne, James D Brooks, and Tina Hernandez-Boussard.

<!--more-->

# Background
Explicit documentation of stage is an endorsed quality metric by the National Quality Forum. Clinical and pathological cancer staging is inconsistently recorded within clinical narratives but can be derived from text in the Electronic Health Record. To address this need, we developed a Natural Language Processing (NLP) solution for extraction of clinical and pathological TNM stages from the clinical notes in prostate cancer patients.

# Methods
Data for patients diagnosed with prostate cancer between 2010 and 2018 were collected from a tertiary care academic healthcare systems EHR records in the United States. This system is linked to the California Cancer Registry, and contains data on diagnosis, histology, cancer stage, treatment and outcomes. A randomly selected sample of patients were manually annotated for stage to establish the ground truth for training and validating the NLP methods. For each patient, a vector representation of clinical text (written in English) was used to train a machine learning model alongside a rule-based model and compared with the ground truth.

# Results
A total of 5,461 prostate cancer patients were identified in the clinical data warehouse and over 30% were missing stage information. Thirty-three to thirty-six percent of patients were missing a clinical stage and the models accurately imputed the stage in 21–32% of cases. Twenty-one percent had a missing pathological stage and using NLP 71% of missing T stages and 56% of missing N stages were imputed. For both clinical and pathological T and N stages, the rule-based NLP approach out-performed the ML approach with a minimum F1 score of 0.71 and 0.40, respectively. For clinical M stage the ML approach out-performed the rule-based model with a minimum F1 score of 0.79 and 0.88, respectively.

# Conclusions
We developed an NLP pipeline to successfully extract clinical and pathological staging information from clinical narratives. Our results can serve as a proof of concept for using NLP to augment clinical and pathological stage reporting in cancer registries and EHRs to enhance the secondary use of these data.
