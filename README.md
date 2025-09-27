# ⚽ Football Sub-Events Detection from Twitter Streams  

This project was developed as part of a **Kaggle competition**, focusing on the **real-time recognition of football match sub-events** (goals, fouls, substitutions, etc.) using millions of tweets segmented by minute.  

The aim was to explore and compare different **machine learning approaches** to classify events from large-scale, noisy textual data.  

---

## 🚀 Project Overview  

- **Task**: Detect football sub-events from minute-level tweet batches.  
- **Data**: Millions of tweets collected during football matches.  
- **Approach**: Combine **preprocessing**, **feature extraction**, and **multi-model comparison** to evaluate performance.  

---

## 🛠️ Preprocessing  

1. **Data Cleaning**  
   - Removed ads, spam, and retweets to preserve **chronology** and avoid bias.  

2. **Feature Engineering**  
   - Used **Large Language Models (LLMs)** to:  
     - Evaluate **sentiment polarity** of tweets (positive, negative, neutral).  
     - Extract **keyword associations** relevant to football events.  

3. **Representation**  
   - Transformed tweets into feature vectors using text embeddings and TF-IDF variants.  

---

## 🤖 Models Implemented  

We compared several models to study the trade-offs between interpretability, accuracy, and scalability:  

- **Logistic Regression (LogReg)** – baseline linear model  
- **Support Vector Machines (SVM)** – robust to high-dimensional data  
- **XGBoost** – tree-based boosting, strong performance on sparse features  
- **Deep Learning (NNs)** – experimented with neural networks for sequence-level embeddings  

---

## 📊 Results & Insights  

- **XGBoost** and **Logistic Regression** achieved the best performance.  
- This shows that **higher complexity is not always a guarantee of better performance**.  

---

## 🎯 Key Takeaways  

- Effective preprocessing (removing noise + leveraging LLMs) is crucial in social media mining.  
- Combining **classical ML** with **modern NLP techniques** provides a strong framework for event detection.  
- Football matches offer a **rich case study** for real-time event recognition, with direct applications in **sports analytics** and **media monitoring**.  

---

## 👥 Teamwork  

This project was developed collaboratively with teammates, combining expertise in:  
- **Data preprocessing and NLP**  
- **Machine learning model implementation**  
- **Evaluation and benchmarking on Kaggle**  

---

👉 This project showcases the intersection of **natural language processing, machine learning, and sports analytics**.  
