# ​ Fake News Detection with LSTM & Bi-LSTM

##  Project Overview
This repository contains Jupyter Notebook implementations for detecting fake news using deep learning:

- **FakeNewsLSTM.ipynb** – Implements an LSTM (Long Short-Term Memory) model.
- **FakeNewswithBi_LSTm.ipynb** – Implements a Bi-LSTM (Bidirectional LSTM) model.

Both models are designed to classify news articles as *fake* or *real*, enabling a direct comparison of their performance.

---

##  Repository Structure
├── FakeNewsLSTM.ipynb # LSTM model implementation\
├── FakeNewswithBi_LSTm.ipynb # Bi-LSTM model implementation\
└── README.md # Project documentation

---

##  Usage Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/marwan-rashad5820/Fake-News-with-LSTM.git
   cd Fake-News-with-LSTM
   ```
   
---

   # Install dependencies
```
pip install -r requirements.txt
```

---

# Results 

Model	   |      Accuracy	   |      Loss\
LSTM	   |       87%	       |      0.2072\
Bi-LSTM	 |       91%         |       0.1772

# Insights
• LSTM effectively captures sequences in one direction.\

• Bi-LSTM leverages bidirectional context, which may enhance accuracy.\

• Initial experiments suggest Bi-LSTM may outperform LSTM, but you should confirm with your results.

---

# Future Enhancements
• Add GRU, Transformer, or BERT based models\
• Test pre-trained embeddings (e.g., GloVe, Word2Vec)\
• Automate evaluation: generate metrics and graphical comparisons\
• Package as a deployable app or API


