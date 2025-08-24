# NLP-Based Similarity Analysis: GSS 2025 (Climate Action Cluster) & T20 Communiqué

This project uses natural language processing (NLP) techniques to assess the thematic alignment between **sustainability-related action points** from the *Global Solutions Summit (GSS) 2025* and the **policy recommendations** from the *T20 Communiqué*. The analysis focuses on identifying overlapping themes and shared policy priorities by measuring **semantic similarity** between texts.

---

## Objective

To determine how closely the GSS 2025 sustainability sessions align with the T20’s formal policy recommendations by:
- Extracting and segmenting key texts
- Computing semantic similarity between action items and recommendations
- Presenting the top sentence matches and shared thematic areas

---
##  Repository Structure

├── Similarity analysis_code.ipynb # Jupyter Notebook with full analysis code

├── Methodology.pdf 

├── Summary action points- sustainability.docx # GSS 2025 action points document

├── T20 communique.docx # T20 policy recommendation document

├── top_13_similarity_results_with_shared_topics.html # HTML output: top thematic similarity results

├── top_sentence_matches_highlighted.html # HTML output: sentence-level similarity highlights


---

##  Results

- **Top 13 similarity results** :  
https://mariafernandaortega.github.io/NLP--similarity-matches/top_13_similarity_results_with_shared_topics.html

- **Identification of common terminology across Action Points and Recommendations** :  
https://mariafernandaortega.github.io/NLP--similarity-matches/top_sentence_matches_highlighted.html
---

##  Tools and Libraries

- **Text Processing**: `nltk`, `re`, `spacy`, `python-docx`
- **Embedding Model**: `sentence-transformers` (Sentence-BERT)
- **Similarity Scoring**: `scikit-learn`
- **Data Handling**: `pandas`, `numpy`




