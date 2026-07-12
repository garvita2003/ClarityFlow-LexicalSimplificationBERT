# Clarity Flow - Lexical Simplification with BERT 🧠

## 📌 Introduction

Clarity Flow is a lexical simplification project focused on making complex text easier to understand while preserving meaning. Based on the notebook implementation, the workflow combines:

- ✅ Complex Word Identification (CWI)
- ✅ Candidate generation using BERT masked language modeling
- ✅ Candidate filtering/ranking for replacement selection
- ✅ Evaluation using classification and text-quality metrics

---

## 🔄 Process / Flow

1. Load and preprocess lexical simplification datasets.
2. Build a CWI pipeline to identify difficult words in context.
3. Prepare embeddings/features for model training.
4. Train sequence models for CWI prediction.
5. Use BERT masked LM to generate replacement candidates.
6. Rank/select candidate substitutes for simplification.
7. Evaluate results with model metrics (for CWI) and BERTScore (for simplified output quality).

---

## 🛠️ Technology Used

| Component | Technology |
|-----------|-----------|
| Language | Python |
| Notebook Environment | Jupyter Notebook (`implementation.ipynb`) |
| Data & Processing | pandas, numpy, nltk |
| Embeddings | GloVe + gensim |
| Deep Learning | Keras / TensorFlow |
| Candidate Generation | Hugging Face transformers (BERT) + PyTorch |
| Evaluation | scikit-learn (`f1_score`), BERTScore |

---

## 🎓 Skills Gained

### Natural Language Processing

- ✅ Complex Word Identification (CWI) workflow design
- ✅ Context-aware candidate generation using BERT masked LM
- ✅ Lexical simplification pipeline structuring (identify, generate, rank)
- ✅ Text quality evaluation using BERTScore

### Machine Learning & Modeling

- ✅ Sequence modeling with Keras/TensorFlow components
- ✅ Feature preparation from lexical and embedding-based inputs
- ✅ Model validation using classification metrics like F1-score
- ✅ Combining traditional NLP features with transformer-based methods

### Data Handling & Experimentation

- ✅ Dataset preprocessing and transformation in pandas
- ✅ Tokenization, POS tagging, and corpus utilities with NLTK
- ✅ Embedding integration using GloVe and gensim
- ✅ Notebook-driven experimentation and iterative evaluation

---

## 📂 Project Structure

```text
ClarityFlow-LexicalSimplificationBERT/
├── implementation.ipynb    # End-to-end lexical simplification pipeline notebook
└── README.md               # Project documentation and setup instructions
```

--- 

## 📸 Demonstration

![Picture1](https://github.com/user-attachments/assets/baffe3ef-a894-4e2e-a832-1b09204ef1b1)
![image](https://github.com/user-attachments/assets/1217b63f-95b1-4dd4-acba-d92a7505f923)
![image](https://github.com/user-attachments/assets/ea211593-3248-47db-a319-879887a8cb62)
![image](https://github.com/user-attachments/assets/fdda35fe-e5d9-440e-a34d-4655d1d112fb)
![2](https://github.com/user-attachments/assets/66d67f95-793e-46a2-a945-7ab05a2f3f15)
![3](https://github.com/user-attachments/assets/398e99cd-a016-4afe-adaa-fa705d47598f)

---

## ⚙️ Setup Instructions

### ✅ Prerequisites

- ✅ Python 3.8+
- ✅ Jupyter Notebook / JupyterLab
- ✅ Required Python libraries used in the notebook:
	- `pandas`
	- `numpy`
	- `matplotlib`
	- `seaborn`
	- `nltk`
	- `gensim`
	- `tensorflow`
	- `keras`
	- `scikit-learn`
	- `transformers`
	- `torch`
	- `bert-score`
	- `wordfreq`

### 📦 Installation

```bash
pip install pandas numpy matplotlib seaborn nltk gensim tensorflow keras scikit-learn transformers torch bert-score wordfreq
```

### ▶️ Run

1. Open `implementation.ipynb` in Jupyter.
2. Run cells in order from top to bottom.
3. Ensure NLTK resources are downloaded when prompted in notebook cells.

