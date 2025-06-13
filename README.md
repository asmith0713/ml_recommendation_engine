# 🧠 Beginner-Level Product Recommendation System

*A Content-Based Filtering Project | AI Placement Drive Hackathon 2025*

---

## 📘 Overview

This project implements a **content-based product recommendation system** developed as part of the **Beginner Track (0–2 years)** in the **AI Placement Drive Hackathon 2025**. Using product metadata and textual descriptions, it recommends similar products by leveraging **TF-IDF vectorization** and **cosine similarity**.

> ✅ Final Notebook:  
> [Kaggle Notebook](https://www.kaggle.com/code/maramreddyasmith/recommendationsystem-asmith-beginner)  
> 🔗 GitHub Repository:  
> [GitHub Repo](https://github.com/asmith0713/ml_recommendation_engine)

---

## 🚀 Problem Approach & Methodology

📌 Dataset: Amazon Product Metadata  
📌 Approach:

- Selected features: `Product Name`, `About Product`, `Category`, `Selling Price`
- Dropped missing/irrelevant entries
- Used **TF-IDF** to vectorize textual fields
- Calculated **cosine similarity** for recommendations
- Built modular functions with interactive output
- Evaluated with **Precision@5**, **Coverage**, and **Similarity Score**

---

## 🛠 Tech Stack

| Tool/Library            | Purpose                              |
| ----------------------- | ------------------------------------ |
| `pandas`                | Data manipulation                    |
| `numpy`                 | Numeric operations                   |
| `scikit-learn`          | TF-IDF Vectorizer, Cosine similarity |
| `matplotlib`, `seaborn` | EDA & visualization                  |
| `Kaggle`                | Notebook environment                 |

---

## 📊 Evaluation Metrics

| Metric             | Value |
| ------------------ | ----- |
| 🌟 Precision@5     | 0.927 |
| 📈 Avg. Similarity | 0.755 |
| 📥 Coverage        | 0.991 |
| 📦 Records Used    | 9,910 |

---

## 🧪 Sample Demo

Here’s how a product recommendation call looks inside the notebook:

```python
get_recommendations_by_name("DB Longboards CoreFlex Crossbow 41\" Bamboo Fiberglass Longboard Complete")
```

### 📥 Top 5 Recommendations (Sample Output)

| Rank | Product Index | Similarity Score | Product Name | Category | Selling Price |
|------|----------------|------------------|--------------|----------|----------------|
| 1️⃣ | 9064 | 0.893707 | DB Longboards Phase 38" Maple Drop Through Longboard | Sports & Outdoors → Outdoor Recreation → Skateboarding | $134.82 |
| 2️⃣ | 9695 | 0.886452 | DB Longboards Contra Drop Deck Maple Longboard | Sports & Outdoors → Outdoor Recreation → Skateboarding | $80.96 |
| 3️⃣ | 4868 | 0.884624 | Moose Bamboo Kicktail/Kryptonics Longboard | Sports & Outdoors → Outdoor Recreation → Skateboarding | $72.95 |
| 4️⃣ | 6924 | 0.857718 | PARADISE The Mallows Kicktail Complete Longboard | Sports & Outdoors → Outdoor Recreation → Skateboarding | $112.19 |
| 5️⃣ | 4493 | 0.856613 | Bamboo Skateboards – Pintail Longboard Tiki Mask | Sports & Outdoors → Outdoor Recreation → Skateboarding | $74.77 |


---

## 📊 Exploratory Data Analysis (EDA)

- 📌 Price Distribution Analysis
- 📌 Description Length by Category
- 📌 Product Frequency by Category
- 📌 Similarity Heatmaps

---

## 📈 Business Relevance

- 🔍 Enhances **product discoverability**
- 🛒 Boosts **engagement and session time**
- 📊 Can be applied in **e-commerce, electronics, fashion, home décor**
- 🌐 Scalable for **real-world deployment**

---

## 📝 Best AI Project Summary

This AI project is a **content-based recommendation system** designed to suggest similar products using product metadata. It applies TF-IDF vectorization to product titles and descriptions, and identifies top matches using cosine similarity. The system was built in a Kaggle notebook and uses standard ML libraries like pandas, scikit-learn, and matplotlib.

Although I am new to the field of AI/ML, I am highly motivated to learn. I took up this project with the intention to explore real-world applications of machine learning. This project helped me understand essential workflows—preprocessing, modeling, and evaluation—while using AI tools like ChatGPT for guidance in documentation and idea validation.

The experience has deepened my interest in intelligent systems and strengthened my resolve to pursue more AI/ML learning opportunities going forward.



---

## 🙋 About Me

**Maramreddy Asmith**  
🎓 B.Tech CSE @ KMIT, Hyderabad  
📧 [asmithreddy2004@gmail.com](mailto:asmithreddy2004@gmail.com)  
🔗 [GitHub](https://github.com/asmith0713)  
🔗 [Kaggle](https://www.kaggle.com/maramreddyasmith)  
🔗 [LinkedIn](https://www.linkedin.com/in/asmithreddy0713)



---

> ⭐ If you found this project useful or interesting, please give it a star. Your support motivates me to keep building better solutions!
