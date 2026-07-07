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

## 📂 Project Structure

```text
ClarityFlow-LexicalSimplificationBERT-main/
├── implementation.ipynb
└── README.md
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

