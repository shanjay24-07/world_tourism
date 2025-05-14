# 🧳 Tourism Intelligence: Regression, Classification & Recommendation

## 📌 Project Overview

This project aims to enhance user experiences in the tourism domain by using data science techniques to:
- Predict user satisfaction (Regression)
- Classify user travel behavior (Classification)
- Recommend personalized tourist attractions (Recommendation)

By analyzing historical travel data, user preferences, and attraction features, this system provides actionable insights for tourism agencies and travel platforms to personalize services and improve customer engagement.

---

## 🎯 Objectives

### 1. 🎚 Regression: Predicting Attraction Ratings
**Goal:** Estimate the rating a user would give to a tourist attraction based on:
- User demographics (continent, region, country, city)
- Visit details (year, month, mode of visit)
- Attraction features (type, location, average rating)

**Use Case:** Predict user satisfaction and identify attractions at risk of low ratings to improve service quality and expectation management.

---

### 2. 🏷 Classification: Predicting Visit Mode
**Goal:** Classify the user's mode of visit:
- Categories: Business, Family, Couples, Friends

**Input Features:**
- User demographics
- Attraction characteristics (type, popularity)
- Historical visit data (month, year, previous visit modes)

**Use Case:** Enable targeted marketing, tailored packages, and better resource planning at attractions or accommodations.

---

### 3. 🤖 Recommendation System: Personalized Attraction Suggestions
**Goal:** Recommend attractions based on:
- User visit history and preferences
- Attraction metadata (type, popularity, location)
- Similar user behavior and ratings

**Techniques Used:**
- Collaborative Filtering (user-item interactions)
- Content-Based Filtering (attraction similarity)
- Hybrid Recommendation System (optional)

**Use Case:** Boost engagement, promote relevant destinations, and enhance customer loyalty through personalized recommendations.

---

## 🛠 Approach

### 🧹 Data Cleaning
- Handle missing values in transaction, user, and city data
- Resolve discrepancies in city names and categorical variables
- Standardize date/time formats
- Remove or fix outliers and incorrect ratings

### ⚙ Preprocessing & Feature Engineering
- Encode categorical variables (VisitMode, Country, AttractionTypeId)
- Aggregate user-level statistics (e.g., average ratings per visit mode)
- Merge transaction, user, city, and attraction datasets into a consolidated view
- Normalize numerical features like rating and popularity

---

## 💼 Business Use Cases

- 🎯 **Personalized Recommendations:** Increase satisfaction through customized suggestions
- 📊 **Tourism Analytics:** Identify popular attractions and adjust offerings
- 🧑‍🤝‍🧑 **Customer Segmentation:** Classify travelers for targeted promotions
- 🔁 **Customer Retention:** Boost loyalty by aligning recommendations with preferences

---

## 📚 Tech Stack

- **Languages:** Python
- **Libraries:** pandas, numpy, scikit-learn, xgboost, LightFM, Surprise, matplotlib, seaborn
- **Models:** Linear Regression, Random Forest, XGBoost, Decision Trees, SVD (Recommendation)

---

## 📈 Evaluation Metrics

- **Regression:** RMSE, MAE, R²
- **Classification:** Accuracy, Precision, Recall, F1-score
- **Recommendation:** Precision@k, Recall@k, NDCG, MRR

---

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/tourism-analytics.git
cd tourism-analytics
