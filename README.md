 Quora Duplicate Question Classifier 

This project predicts whether two questions asked on Quora are semantically similar (duplicates) using a deep learning model.

 Overview
- **Dataset:** Quora Question Pairs (from Kaggle)
- **Goal:** Classify pairs of questions as *duplicate* or *not duplicate*.
- **Architecture:** LSTM-based model trained on word embeddings.
- **Framework:** TensorFlow / Keras

Results
| Metric | Value |
|--------|-------|
| Train Accuracy | 84.0% |
| Validation Accuracy | 81.0% |
| Test Accuracy | 81.02% |

Model Summary
- Embedding layer 
- Bidirectional LSTM
- Dense layers with dropout regularization
- Binary cross-entropy loss, Adam optimizer

 Future Improvements
- Experiment with Transformer-based models (BERT, DistilBERT)
- Use sentence embeddings (SBERT) for better semantic understanding

dataset Link
[Kaggle – Quora Question Pairs](https://www.kaggle.com/competitions/quora-question-pairs)

---
