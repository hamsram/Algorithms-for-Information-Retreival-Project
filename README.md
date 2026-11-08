# Law Information Retrieval System

##  Overview
A Python-based information retrieval system designed to search and retrieve relevant legal documents using Natural Language Processing (NLP), TF-IDF vectorization, and Cosine Similarity.

The system processes legal case documents and ranks search results based on their relevance to user queries.

##  Repository Contents

| File | Description |
|---|---|
| `case_retrieve.ipynb` | Jupyter Notebook containing the implementation of the legal document retrieval system. |
| `output.csv` | Dataset containing legal case information. |


##  Key Features
- **Keyword Search:** Retrieves cases based on keywords.
- **Phrase Search:** Searches for specific phrases within legal documents.
- **Boolean Search:** Supports AND, OR, and NOT operators.
- **Case Title Search:** Finds cases using their titles.
- **Wildcard Search:** Supports prefix and suffix-based searches.
- **TF-IDF & Cosine Similarity:** Measures document relevance and ranks search results.
- **Text Processing:** Implements tokenization, stemming, and lemmatization.

##  Technologies Used
- Python
- Pandas & NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity

##  Objective
To simplify legal research by enabling efficient, relevant, and query-based retrieval of legal case documents using NLP and information retrieval techniques.
