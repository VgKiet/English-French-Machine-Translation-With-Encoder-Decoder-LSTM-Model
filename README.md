# English → French Neural Machine Translation using Encoder–Decoder LSTM with Luong Attention

This project implements a Neural Machine Translation (NMT) system from scratch using PyTorch.
The model translates English sentences into French using an Encoder–Decoder LSTM architecture with Luong Attention mechanism and Beam Search decoding.

---

## Project Features

- Encoder–Decoder architecture with LSTM
- Luong Attention mechanism
- Beam Search decoding
- Tokenization using spaCy
- Vocabulary construction
- Dynamic padding and batching
- Teacher forcing during training
- BLEU score evaluation

---

## Dataset & Model Files

Due to GitHub storage limitations, the dataset and trained model files are stored externally on Google Drive.

Download here:

https://drive.google.com/drive/folders/1LBgZsoadd5BCwYRC3F4pCpVikLon2pGb

After downloading:

Place extracted files into the project directory before running notebooks.

Example:

project_root/
│
├── data/
├── model/
├── NLP_Attention_beam.ipynb
├── Test.ipynb

---

## Project Structure

project/
│
├── NLP_Attention_beam.ipynb   # Training + attention + beam search
├── Test.ipynb                 # Model testing notebook
├── report/                    # Project report
├── README.md
└── .gitignore

---

## Technologies Used

- Python
- PyTorch
- spaCy
- NumPy
- NLTK

---

## Evaluation Metric

Model performance is evaluated using:

- BLEU Score

---

## Objectives

- Build Neural Machine Translation system from scratch
- Understand attention mechanism in seq2seq models
- Apply beam search decoding
- Implement full NLP training pipeline using PyTorch

---

## Authors

- Võ Gia Kiệt
- Phan Đức Nhân

---

## Notes

Dataset and trained model weights are provided via Google Drive link above.
This project is implemented for research and learning purposes in Deep Learning and Natural Language Processing.
