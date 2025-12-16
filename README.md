# CAFA-6 Protein Function Prediction

##  Project overview

This project predicts Gene Ontology (GO) terms for proteins using protein language models.
Used ESM2 (650M params) to generate embeddings, then trained a neural network classifier to perform multi-label biological function prediction.

##  How to reproduce locally

First, 
```bash
git clone https://github.com/quanmcvn/cafa6.git
cd cafa6
pip install -r requirements.txt
```

Run notebook

## Credit

Credit to `https://github.com/blazinbanana/cafa6` for data handling code (extracting zip, loading data, formatting data to submit). I expanded upon their simple logistic regression classifier by using neural network classifier.