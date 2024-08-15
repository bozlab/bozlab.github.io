---
title: "Expanding a radiology lexicon using contextual patterns in radiology reports."
date: 2019-06-18T12:33:46+10:00
weight: 20
---

Bethany Percha, Yuhao Zhang, **Selen Bozkurt**, Daniel Rubin, Russ B Altman, and Curtis P Langlotz. 

# Objective
Distributional semantics algorithms, which learn vector space representations of words and phrases from large corpora, identify related terms based on contextual usage patterns. We hypothesize that distributional semantics can speed up lexicon expansion in a clinical domain, radiology, by unearthing synonyms from the corpus.

# Materials and methods
We apply word2vec, a distributional semantics software package, to the text of radiology notes to identify synonyms for RadLex, a structured lexicon of radiology terms. We stratify performance by term category, term frequency, number of tokens in the term, vector magnitude, and the context window used in vector building.

# Results
Ranking candidates based on distributional similarity to a target term results in high curation efficiency: on a ranked list of 775 249 terms, >50% of synonyms occurred within the first 25 terms. Synonyms are easier to find if the target term is a phrase rather than a single word, if it occurs at least 100× in the corpus, and if its vector magnitude is between 4 and 5. Some RadLex categories, such as anatomical substances, are easier to identify synonyms for than others.

# Discussion
The unstructured text of clinical notes contains a wealth of information about human diseases and treatment patterns. However, searching and retrieving information from clinical notes often suffer due to variations in how similar concepts are described in the text. Biomedical lexicons address this challenge, but are expensive to produce and maintain. Distributional semantics algorithms can assist lexicon curation, saving researchers time and money.
 