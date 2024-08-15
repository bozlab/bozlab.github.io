---
title: "Phenotyping severity of patient-centered outcomes using clinical notes: A prostate cancer use case."
date: 2019-06-18T12:33:46+10:00
weight: 35
---

**Selen Bozkurt**, Rohan Paul, Jean Coquet, Ran Sun, Imon Banerjee, James D Brooks, and Tina Hernandez-Boussard.

# Introduction
A learning health system (LHS) must improve care in ways that are meaningful to patients, integrating patient-centered outcomes (PCOs) into core infrastructure. PCOs are common following cancer treatment, such as urinary incontinence (UI) following prostatectomy. However, PCOs are not systematically recorded because they can only be described by the patient, are subjective and captured as unstructured text in the electronic health record (EHR). Therefore, PCOs pose significant challenges for phenotyping patients. Here, we present a natural language processing (NLP) approach for phenotyping patients with UI to classify their disease into severity subtypes, which can increase opportunities to provide precision-based therapy and promote a value-based delivery system.

# Methods
Patients undergoing prostate cancer treatment from 2008 to 2018 were identified at an academic medical center. Using a hybrid NLP pipeline that combines rule-based and deep learning methodologies, we classified positive UI cases as mild, moderate, and severe by mining clinical notes.

# Results
The rule-based model accurately classified UI into disease severity categories (accuracy: 0.86), which outperformed the deep learning model (accuracy: 0.73). In the deep learning model, the recall rates for mild and moderate group were higher than the precision rate (0.78 and 0.79, respectively). A hybrid model that combined both methods did not improve the accuracy of the rule-based model but did outperform the deep learning model (accuracy: 0.75).

# Conclusion
Phenotyping patients based on indication and severity of PCOs is essential to advance a patient centered LHS. EHRs contain valuable information on PCOs and by using NLP methods, it is feasible to accurately and efficiently phenotype PCO severity. Phenotyping must extend beyond the identification of disease to provide classification of disease severity that can be used to guide treatment and inform shared decision-making. Our methods demonstrate a path to a patient centered LHS that could advance precision medicine.