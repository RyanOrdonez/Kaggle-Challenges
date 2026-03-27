# Kaggle Challenges

Competition entries from Kaggle — each in its own directory with notebooks, data pipelines, and write-ups.

---

## Challenges

### 1. NLP with Disaster Tweets
**Competition:** [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)

Classifying tweets as real disasters vs. non-disasters using four architectures: Bidirectional LSTM, standard LSTM, Bidirectional GRU, and a TF-IDF baseline. Best Kaggle score: **0.80631 (Rank 377)** with the Bidirectional GRU model.

**Tech:** TensorFlow, NLTK, GloVe embeddings, Pandas, Seaborn

---

### 2. Monet Style Transfer
**Competition:** [I'm Something of a Painter Myself](https://www.kaggle.com/competitions/gan-getting-started)

Transforming photographs into Monet-style paintings using three generative approaches: Neural Style Transfer, CycleGAN, and DCGAN. Neural Style Transfer achieved **MiFID 53.14 (Rank 20)**.

**Tech:** TensorFlow, Keras, CycleGAN, Neural Style Transfer

---

### 3. Histopathologic Cancer Detection
**Competition:** [Histopathologic Cancer Detection](https://www.kaggle.com/competitions/histopathologic-cancer-detection)

Identifying metastatic cancer in 96x96 pixel pathology patches using a custom CNN with structured hyperparameter search over pooling strategies, L2 regularization, and dropout rates. Achieved **84.8% validation accuracy**.

**Tech:** TensorFlow, Keras, NumPy, Matplotlib

---

## Repository Structure
```
Kaggle-Challenges/
├── nlp-disaster-tweets/       # Challenge 1
├── monet-style-transfer/      # Challenge 2
├── cancer-detection/          # Challenge 3
└── README.md
```

## Author
Ryan Ordonez — MS in Data Science, University of Colorado Boulder
