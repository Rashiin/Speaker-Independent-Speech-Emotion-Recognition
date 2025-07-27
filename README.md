# Speaker-Independent Speech Emotion Recognition 🎤🧠

> **Robust, honest, and real-world-ready AI for emotion recognition from speech.**

---

## 🚀 Overview

Can machines truly recognize emotions from voices they've never heard?  
Most AI models excel at emotion detection when tested on familiar voices—but what about real-life scenarios, where users are always new?

This project takes speech emotion recognition to the next level:  
**It tests machine learning models not only on random splits but, crucially, on entirely unseen speakers.**  
The result? A transparent look at the real generalization gap in today’s emotion AI.

---

## 🗂️ Dataset

- **TESS**: Toronto Emotional Speech Set  
  - 7 core emotions  
  - High-quality audio  
  - Two speakers (for honest speaker-independent evaluation)

---

## 🔍 Features

- **Feature Extraction:** MFCCs and statistical audio features
- **Models:** Random Forest, SVM, XGBoost
- **Robust Evaluation:**  
  - *Random Split*: Standard approach (all speakers mixed)  
  - *Speaker-Independent*: Train on one speaker, test on the other (true generalization)
- **Visualization:** Confusion matrices, F1-score bar plots, detailed analytics
- **Fully reproducible code (Jupyter notebook + Python script)**

---

## 📊 Key Results

- **Random Split Accuracy:** ~100% (but not realistic!)
- **Speaker-Independent Accuracy:** ~17% (true challenge revealed)
- **Takeaway:** Most AI models overestimate real-world readiness. Honest benchmarks matter.

---

## 💡 Why It Matters

Emotion-aware AI is crucial for digital health, education, accessibility, and human-computer interaction.  
**If our models can't understand emotions from new users, they can't serve real people.**  
This repo offers a practical benchmark, lessons learned, and a call to action for more robust, inclusive emotion AI.

---

## 🛠️ How to Use

1. Clone this repo.
2. Place `features_tess_final.csv` in the root directory.
3. Run the notebook `Dubai_Competition_SER_TESS_Rashin.ipynb` (or the Python script) step by step.
4. Visualize results and explore the analysis.

---

## 📈 Sample Visualizations

![Confusion Matrix Example](sample_confusion_matrix.png)
![F1-score Bar Plot](sample_f1_score_bar.png)

---

## 🔬 Future Work

- Test on larger, more diverse datasets (CREMA-D, RAVDESS)
- Explore deep learning and transfer learning for better generalization
- Add data augmentation for robustness in noisy environments
- Benchmark across accents, ages, and recording conditions


## ⭐️ If you find this project useful, please give it a star and share your thoughts or issues!

---

*Real-world AI means real-world evaluation. Let’s build emotion recognition that truly works—for everyone.*
