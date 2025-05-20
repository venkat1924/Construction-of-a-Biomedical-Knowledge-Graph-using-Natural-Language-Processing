# Construction of a Biomedical Knowledge Graph using Natural Language Processing
 
This repository contains code and resources for constructing a **Biomedical Knowledge Graph** (BKG) from scientific literature using Natural Language Processing (NLP). It implements an end-to-end pipeline—from PDF text extraction and preprocessing, through Named Entity Recognition (NER) and co-occurrence analysis, to graph storage and querying in Neo4j. The corresponding paper describes the methodology, experiments, and results in detail.

---

## Features

* **OCR-based PDF extraction** using `pdf2image` and `pytesseract` to convert research articles into raw text.
* **Text cleaning** with NLTK to remove headers, figure captions, and normalize content.
* **Biomedical NER** leveraging the BERN2 API for multi-type entity recognition and linking.
* **Co-occurrence analysis** to identify relationships between entities within a sliding window.
* **Graph construction** in Neo4j, including nodes for authors, articles, sentences, and entities, and relationships for mentions and co-occurrence.
* **Graph-powered applications** such as search engine queries, author expertise inspection, and potential integration with machine learning via node embeddings.


---

## Citation

If you use this code in your work, please cite:

```bibtex
@INPROCEEDINGS{10543900,
  author={Balachandra, Anumaneni Venkat and Deepamala, N and Shobha, G},
  booktitle={2024 International Conference on Emerging Technologies in Computer Science for Interdisciplinary Applications (ICETCS)}, 
  title={Construction of a Biomedical Knowledge Graph using Natural Language Processing}, 
  year={2024},
  pages={1-6},
  doi={10.1109/ICETCS61022.2024.10543900}}

```
