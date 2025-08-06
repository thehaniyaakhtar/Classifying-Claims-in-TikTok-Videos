# 🧠 ClaimEngage: Analyzing Claim-Driven Engagement in TikTok Content

This project explores how different types of **claims made in TikTok videos** affect user engagement—measured via views, likes, and shares. Through rigorous **exploratory data analysis (EDA)** and statistical modeling, this work provides the foundation for building an automated system to **classify claims** and detect **viral or misleading content patterns**.

---

## 📁 Project Overview

### 🎯 Objective  
To identify which types of user-generated claims are most associated with higher engagement on TikTok and establish statistical evidence for their influence on virality.

### 🧑‍💻 Business Use Case  
For platforms like **TikTok**, understanding the relationship between **claim types** and **engagement** supports:

- Scalable **content moderation**
- **Misinformation detection**
- **Trend analysis** for content strategy

This project simulates the **early analytical stages** of such a system—prior to the deployment of any machine learning model.

---

## 🛠️ Tools & Libraries

- **Language**: Python  
- **Data Manipulation**: `pandas`, `numpy`  
- **Visualization**: `matplotlib`, `seaborn`  
- **Statistical Testing**: `scipy.stats`  
- **Modeling & Encoding**: `sklearn`

---

## 🧪 Methodology

### 1️⃣ Problem Framing (PACE Framework)
- What types of **claims** are users making in TikTok videos?
- Do specific **claim categories** drive higher engagement metrics (likes, shares, views)?

### 2️⃣ Data Preparation
- Cleaned and normalized raw TikTok dataset  
- Engineered features:
  - `word_count`, `claim_keyword_presence`
  - Encoded `claim_type` into categories (e.g., **health**, **finance**, **political**)  

### 3️⃣ Exploratory Data Analysis
- **Bar plots**: Frequency distribution of claim categories  
- **Heatmaps**: Correlation between engagement metrics  
- **Pivot tables**: Mean engagement per claim type  

### 4️⃣ Statistical Testing
- **Chi-square tests** to evaluate independence between claim types and engagement  
- **Pearson correlation** for continuous variables  
- **p-values** used to validate significance  

### 5️⃣ Lightweight Modeling for Insight
- **Logistic Regression**: Engagement vs binary claim features  
- **Linear Regression**: Predict engagement metrics using content-based predictors  
- **One-hot encoding** applied to categorical variables  
- Verified **model assumptions** (normality, multicollinearity, heteroscedasticity)

---

## 📊 Key Insights

| Insight Category        | Findings                                                                 |
|-------------------------|--------------------------------------------------------------------------|
| 📈 **Engagement Drivers** | Claims around **health** and **finance** consistently showed higher engagement |
| 🔬 **Statistical Evidence** | Chi-square test showed a **significant relationship** between claim type and engagement |
| 🧩 **Feature Influence** | Regression models indicated **claim keywords** and **content length** were strong predictors of virality |
| 📉 **Underperforming Claims** | Political and educational claims showed **lower average shares and views** |

---

## ✅ Outcome

- Delivered a **clean and enriched dataset** with engineered features ready for machine learning  
- Uncovered **evidence-based relationships** between content claims and user behavior  
- Set a strong **analytical foundation** for a future ML classifier to **detect claim types and predict content reach**

---

