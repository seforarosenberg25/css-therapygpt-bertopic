# css-therapygpt-bertopic
Topic modelling (BERTopic) of r/TherapyGPT personal stories — project report, Computational Social Science, RPTU, SoSe 2026
# Analysing Reddit Discourse around Therapy and AI

Project report for the course Computational Social Science (RPTU, Summer Semester 2026).
Topic modelling of personal experience reports in the subreddit r/TherapyGPT,
interpreted with Sundar's (2020) HAII-TIME model.

## Contents
- `Final_TherapieGPT_bertopic_embeddings.ipynb` — main model (Personal Story sub-corpus)
- `...comparison.ipynb` — comparison run on the full corpus

## Method
BERTopic with sentence-transformers/all-mpnet-base-v2 embeddings, UMAP and HDBSCAN,
run in Google Colab (Python 3, T4 GPU).

## Data
Posts were collected via the Arctic Shift API. The dataset is not published here,
as the posts contain sensitive information about mental health. It is available on request.

## Authors
Isabelle Metz, Johannes Krämer, Mara Köbele, Sefora Rosenberg
