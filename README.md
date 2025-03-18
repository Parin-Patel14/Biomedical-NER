# 🏥 Biomedical Named Entity Recognition (NER) Extraction  

##  Overview  
This project focuses on **extracting biomedical entities** (such as diseases and chemicals) from **clinical research papers** using **advanced Natural Language Processing (NLP) models**.  
It implements **Transformer-based architectures** like **BERT and BioBERT**, combined with **BiLSTM and CRF layers**, to enhance **named entity recognition (NER) in medical texts**.  

---

##  Objectives  
- ✅ Develop a **high-accuracy biomedical Named Entity Recognition (NER) system**.  
- ✅ Utilize **BERT, BioBERT, and BiLSTM-CRF architectures** for improved sequence tagging.  
- ✅ Automate **medical knowledge extraction** from research papers.  
- ✅ Evaluate models based on **precision, recall, and F1-score**.  

---

##  Datasets Used  
- **BC5CDR** (BioCreative V Chemical-Disease Relation dataset)  

---

##  Implemented Approaches & Models  
| Model | Key Components | Purpose |  
|------------|--------------------------------|-----------------------------|  
| **BERT + CRF** | Transformer embeddings + CRF | Enhances structured entity recognition |  
| **BioBERT + BiLSTM** | Domain-specific embeddings + LSTM | Improves entity classification accuracy |  
| **BERT + BiLSTM** | Hybrid model with deep contextual learning | Strengthens sequence tagging for medical texts |  
| **BioBERT + CRF** | Pre-trained biomedical embeddings with CRF | Provides domain-specific NER tagging |  

---

##  Key Findings & Performance Metrics  
| Model | Precision | Recall | F1-Score |  
|------------|------------|------------|------------|  
| **BERT + CRF** | **93.5%** | **92.8%** | **93.1%** |  
| **BioBERT + BiLSTM** | **94.7%** | **94.3%** | **94.5%** |  
| **BERT + BiLSTM** | **95.1%** | **94.8%** | **94.9%** |  
| **BioBERT + CRF** | **95.3%** | **95.0%** | **95.1%** |  

 **Conclusion:** The **BioBERT + CRF model** achieved the **highest F1-score (95.1%)**, making it the most effective approach for biomedical NER.  

---

##  Key Features  
- ✅ **Biomedical Named Entity Recognition** for extracting structured medical data.  
- ✅ **Pre-trained transformers (BioBERT, BERT) for domain-specific accuracy**.  
- ✅ **Implementation of BiLSTM and CRF layers for improved sequence tagging**.  
- ✅ **Performance comparison between different model architectures**.  

---

##  Technologies Used  
- **Python** (TensorFlow, PyTorch, Transformers)  
- **Natural Language Processing (NLP)** (spaCy, NLTK, SciBERT)  
- **Deep Learning Models** (BERT, BioBERT, BiLSTM, CRF)  
- **Jupyter Notebook** for development and experimentation  

---

##  Future Scope  
 **Expanding dataset coverage** to include multilingual biomedical texts.  
 **Enhancing real-time inference speed** for practical deployment.  
 **Exploring Graph Neural Networks (GNNs)** for relationship extraction in medical literature.  

---
