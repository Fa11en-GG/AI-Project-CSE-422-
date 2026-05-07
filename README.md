# AI-Project-CSE-422
Multiclass classification of cricket player positions using Decision Trees, Random Forests, and MLP Neural Networks, including K-Means clustering and PCA visualization. Developed as a CSE422 (Artificial Intelligence) project at BRAC University.



# Cricket Player Position Prediction using Machine Learning

**RAIYAN AHMED** **CS, BRAC University, Bangladesh** *Group 8 - CSE422: Artificial Intelligence*

---

## 📌 Project Overview
This project aims to predict a cricket player's position based on their physical and playing characteristics. We analyzed a comprehensive dataset of international and franchise cricket players from 15+ countries across four continents. This is a **Multiclass Classification** problem where we map player attributes to specific roles like Batsman, Bowler, Allrounder, and Wicketkeeper.

## 📊 Methodology

### 1. Dataset Description
- **Total Features:** 16 (including demographic, physical, and style attributes).
- **Diversity:** Data covers players from 15+ countries and 4 continents.
- **Target:** `position` (consolidated into core playing roles).

### 2. Preprocessing & Feature Engineering
- **Data Cleaning:** Handled missing values in batting and bowling styles.
- **Scaling:** Used `StandardScaler` to normalize numerical data for distance-based algorithms.
- **Encoding:** Implemented `LabelEncoder` to convert categorical text (Continent, Styles) into numerical formats.

### 3. Machine Learning Models
We compared three major algorithms to evaluate predictive performance:
- **Decision Tree Classifier:** Used as a baseline for logical splits.
- **Random Forest Classifier:** An ensemble approach to reduce variance and overfitting.
- **Neural Network (MLPClassifier):** A deep learning approach to capture non-linear relationships.

## 📈 Key Findings
- **Class Imbalance:** The dataset is heavily skewed toward Bowlers and Batsmen, which significantly impacts the recall for minority classes like Wicketkeepers.
- **Performance:** All models achieved a similar accuracy range (~34-37%).
- **Evaluation:** Precision and Recall metrics were used (Classification Reports) to understand the model's struggle with overlapping roles like "Allrounders."

## 🛠️ Tools & Libraries
- **Python**
- **Scikit-Learn** (Classification, Preprocessing, Metrics)
- **Pandas & NumPy** (Data Handling)
- **Matplotlib & Seaborn** (Visualizations/Heatmaps)

## 📂 Repository Contents
- `422_project_final.ipynb`: Complete source code and visualization.
- `CSE422 Project Report.pdf`: The official final report containing detailed group info, dataset descriptions, and comparison analysis.

---
*This project was completed for the CSE422 (Artificial Intelligence) course at BRAC University.*
