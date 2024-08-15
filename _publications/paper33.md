---
title: "Automatic abstraction of imaging observations with their characteristics from mammography reports."
date: 2019-06-18T12:33:46+10:00
weight: 10
---

**Selen Bozkurt**, Jafi A Lipson, Utku Senol, and Daniel L Rubin. 

# Background 
Radiology reports are usually narrative, unstructured text, a format which hinders the ability to input report contents into decision support systems. In addition, reports often describe multiple lesions, and it is challenging to automatically extract information on each lesion and its relationships to characteristics, anatomic locations, and other information that describes it. The goal of our work is to develop natural language processing (NLP) methods to recognize each lesion in free-text mammography reports and to extract its corresponding relationships, producing a complete information frame for each lesion.

# Materials and methods 
We built an NLP information extraction pipeline in the General Architecture for Text Engineering (GATE) NLP toolkit. Sequential processing modules are executed, producing an output information frame required for a mammography decision support system. Each lesion described in the report is identified by linking it with its anatomic location in the breast. In order to evaluate our system, we selected 300 mammography reports from a hospital report database.

# Results 
The gold standard contained 797 lesions, and our system detected 815 lesions (780 true positives, 35 false positives, and 17 false negatives). The precision of detecting all the imaging observations with their modifiers was 94.9, recall was 90.9, and the F measure was 92.8.

# Conclusions 
Our NLP system extracts each imaging observation and its characteristics from mammography reports. Although our application focuses on the domain of mammography, we believe our approach can generalize to other domains and may narrow the gap between unstructured clinical report text and structured information extraction needed for data mining and decision support.