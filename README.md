# human_responce_matcing_app
This repository contains an advanced, NLP-powered algorithm designed to match human to human pair based on their ovarall life experience. Instead of relying on rigid, rule-based text matching, this system uses
1.  A Weighted Matrix Algorithm included TF-IDF , Cosine Similarity, Min-Max Normalization.
2.  Advanced Semantic Context based Technique: Semantic embedding (using Sentence Transformer: all-miniLM-L6-v2) for context and synonym understanding. It also features Dynamic Weighting (redistributing score weights if a coachee leaves a text field blank) and Global Capacity Optimization (globally limiting a single mentor to a maximum of 3 top-choice assignments).
