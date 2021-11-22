# Multi-label text classification baseline (Agrohack)
- **Task:** to classify cow disease description into 11 categories
- **Model:** pre-trained RuRoBerta
- **Approach:** fine-tuning with standard HF trainer interface with low lr, clf head on top of CLS embedding, no preprocessing and simple text augmentations 
- **Perfomance:** 0.25 logloss, ~ top 10% on private LB

