# Thesis: Topic Modeling of Sustainable Development Goal (SDG) Research in Nepal (2015–2024)

This repository contains all the source code, outputs, and documentation related to the thesis:  
**"Analyzing Trends in SDG Research in Nepal Using Topic Modeling (2015–2024)"**

The study applies LDA and BERTopic to extract thematic patterns from research article metadata aligned with the 17 Sustainable Development Goals (SDGs).

**Repository Structure**

├── thesis_code.ipynb # Main Jupyter Notebook for BERTopic modeling

├── bertopic_keywords_all_topics.csv # All 240 topics extracted from the model

├── data/ # (Optional) Folder for input metadata/datasets

├── output_topics/ # Folder for exported topic summaries


## 🧠 Methodology Summary

**Preprocessing**: Title + Abstracts of research articles were cleaned, normalized, and embedded.
**Model**: BERTopic with default settings (UMAP + HDBSCAN + TF-IDF).

**Clustering**: Extracted and summarized over 200 latent topics.

**Evaluation**: Manually inspected top keywords and topic distributions across SDGs.



## 🧪 Requirements

This project runs on Python 3.8+ and requires the following packages:

bash
pip install bertopic pandas scikit-learn umap-learn hdbscan
