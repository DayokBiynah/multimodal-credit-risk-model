<div align="center">

# 🏦 Multimodal Deep Learning for Credit Scoring

### Predicting Credit Default Risk Using Deep Learning and Multimodal Data Fusion

**Python • PyTorch • Transformers • DistilBERT • Computer Vision • Time Series • Deep Learning**

</div>

---

## 📖 Overview

This project explores how **multimodal deep learning** can improve traditional credit scoring by combining multiple sources of customer information into a single predictive model.

The project is based on the **Home Credit Default Risk** dataset and demonstrates how multimodal learning can be applied to credit risk prediction by combining multiple sources of customer information into a unified deep learning model.

Unlike conventional credit scoring models that rely solely on structured financial data, this project integrates:

- 📊 Static (tabular) customer information
- 📈 Time-series financial history
- 📝 Textual information using Transformer models
- 🖼️ Image data

By learning from these complementary data sources simultaneously, the model captures richer customer representations and improves the assessment of credit risk.

The objective is to predict whether a loan applicant is likely to default by learning from structured financial data, historical behavioral data, natural language, and visual information simultaneously.

---

# 🚀 Features

- Multimodal credit risk prediction
- Deep neural network implementation
- Intermediate Fusion architecture
- Cross-Attention architecture
- Transformer-based NLP with DistilBERT
- Time-series preprocessing
- Image preprocessing pipeline
- Tabular feature engineering
- PyTorch Dataset & DataLoader implementation
- Model evaluation and visualization

---

# 📂 Data Modalities

The project combines four different data sources into a single learning pipeline.

### 📊 Static (Tabular) Data

Customer demographic and financial information, including:

- Income
- Employment information
- Loan characteristics
- Credit history
- Customer profile features

---

### 📈 Time-Series Data

Historical financial behavior over time, such as:

- Payment history
- Transaction history
- Monthly account activity
- Previous financial records

---

### 📝 Text Data

Natural language information processed using **DistilBERT**, including textual customer information that is converted into contextual embeddings for the model.

The preprocessing pipeline includes:

- Tokenization
- Lowercasing
- Stop-word removal
- Text encoding
- Transformer embeddings

---

### 🖼️ Image Data

Visual information incorporated into the multimodal learning pipeline and transformed into feature representations before being fused with the remaining modalities.

---

# 🧠 Models Implemented

## Intermediate Fusion Network

Each modality is processed independently before their learned feature representations are combined to make a final credit risk prediction.

---

## Cross-Attention Network

A more advanced architecture where different modalities attend to one another, enabling richer interactions between financial history, text, images, and structured customer information.

---

# 🛠 Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- DistilBERT
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- OpenCV
- PIL
- NLTK

---

# 📊 Machine Learning Pipeline

1. Data preprocessing
2. Feature engineering
3. Text tokenization using DistilBERT
4. Image preprocessing
5. Time-series preparation
6. Custom PyTorch Dataset creation
7. Model training
8. Model evaluation
9. Performance visualization

---

# 📈 Evaluation

The models are evaluated using common classification metrics, including:

- ROC-AUC
- Confusion Matrix
- Classification Report
- ROC Curve

These metrics help measure how effectively the models distinguish between customers who are likely to repay their loans and those who may default.

---

# 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

- Multimodal Deep Learning
- Credit Risk Modeling
- Transformer-based NLP
- Computer Vision pipelines
- Time-Series Modeling
- Feature Fusion Techniques
- Cross-Attention Architectures
- PyTorch Model Development
- End-to-End Deep Learning Workflows

---

# 🙏 Acknowledgements

A special thank you to **Professor María Óskarsdóttir** of the University of Southampton for her outstanding instruction and guidance.
