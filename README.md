# IMDB Sentiment Classification (SLM Optimization)

This project fine-tunes a Small Language Model (SLM) — `distilbert-base-uncased` — on the IMDB movie reviews dataset for **sentiment analysis** (positive vs negative).  
The work includes training, evaluation, inference, and governance logging for reproducibility.

---

## 📌 Features
- Fine-tunes DistilBERT on cleaned IMDB dataset (CSV format).
- Achieves ~84% accuracy on eval subset (higher expected with full training).
- Saves **evaluation reports** (confusion matrix, precision, recall, F1).
- Inference pipeline with **human-friendly labels (Positive/Negative)**.
- Logs predictions with timestamp, input, label, and score to CSV for governance.
- Ready to scale training with hyperparameter tuning & larger epochs.

---

## ⚙️ Setup

1. **Clone repository**:
   ```bash
   git clone https://github.com/your-username/IMDB_SLM_Optimizing.git
   cd IMDB_SLM_Optimizing
