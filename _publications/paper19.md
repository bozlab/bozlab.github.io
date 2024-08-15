---
title: "Comparison of orthogonal nlp methods for clinical phenotyping and assessment of bone scan utilization among prostate cancer patients."
date: 2019-06-18T12:33:46+10:00
weight: 24
---

**Selen Bozkurt**, Jean Coquet, Selen Bozkurt, Kathleen M Kan, Michelle K Ferrari, Douglas W
Blayney, James D Brooks, and Tina Hernandez-Boussard.

# Objective
Clinical care guidelines recommend that newly diagnosed prostate cancer patients at high risk for metastatic spread receive a bone scan prior to treatment and that low risk patients not receive it. The objective was to develop an automated pipeline to interrogate heterogeneous data to evaluate the use of bone scans using a two different Natural Language Processing (NLP) approaches.

# Materials and methods
Our cohort was divided into risk groups based on Electronic Health Records (EHR). Information on bone scan utilization was identified in both structured data and free text from clinical notes. Our pipeline annotated sentences with a combination of a rule-based method using the ConText algorithm (a generalization of NegEx) and a Convolutional Neural Network (CNN) method using word2vec to produce word embeddings.

# Results
A total of 5500 patients and 369,764 notes were included in the study. A total of 39% of patients were high-risk and 73% of these received a bone scan; of the 18% low risk patients, 10% received one. The accuracy of CNN model outperformed the rule-based model one (F-measure = 0.918 and 0.897 respectively). We demonstrate a combination of both models could maximize precision or recall, based on the study question.

# Conclusion
Using structured data, we accurately classified patients' cancer risk group, identified bone scan documentation with two NLP methods, and evaluated guideline adherence. Our pipeline can be used to provide concrete feedback to clinicians and guide treatment decisions.
