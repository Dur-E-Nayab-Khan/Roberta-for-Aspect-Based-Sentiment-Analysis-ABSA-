# Roberta for Aspect-Based Sentiment Analysis (ABSA)

This repository contains two complete implementations of ABSA using **Roberta-base** on:

1. **ATSA Dataset (Aspect Term Sentiment Analysis)**  
   - Custom train/val/test XML files  
   - Uses HuggingFace Trainer API

2. **SemEval 2016 Task 5 – Restaurants Dataset**  
   - Official XML dataset  
   - Uses manual PyTorch training loop

Both pipelines include:
- XML parsing
- Preprocessing
- Tokenization with Roberta
- Training + evaluation
- Test predictions
- Aspect extraction + inference

---

## 📂 Repository Structure

