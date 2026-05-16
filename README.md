# Part 3 - NLP and Sequence Modeling Mini Project

## Objective
The objective of this project is to build an NLP pipeline for customer support text classification and compare traditional vectorization techniques with sequence-based deep learning approaches.

---

## Tasks Performed

### 1. Dataset Understanding
- Explored dataset structure
- Checked class distribution
- Analyzed sample text records
- Calculated average text length

### 2. Text Preprocessing
- Lowercased text
- Removed special characters
- Removed stopwords
- Tokenized text
- Created padded sequences

### 3. Text Vectorization
- Applied TF-IDF vectorization
- Created tokenizer-based sequences

### 4. Baseline Model
- Built Logistic Regression classifier
- Evaluated using accuracy and confusion matrix

### 5. Sequence Model
- Built LSTM-based sequence model
- Used embedding and recurrent layers

### 6. Attention and Transformer Reflection
- Discussed RNN limitations
- Explained LSTM memory
- Explained attention and transformers

---

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Repository Structure

```text
part-3-nlp-sequence-modeling/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_evaluation.png
    └── sample_predictions.txt
```

---

## Conclusion
The project demonstrates how NLP pipelines convert text into numerical representations and how sequence models like LSTMs process sequential information for text classification tasks.
