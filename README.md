# 🚀Predicting-the-Adoption-of-Clean-Energy-Vehicles-A-Machine-Learning-Based-Market-Analysis-25305
## 📌 Project Overview  
The adoption of clean energy vehicles (EVs) is crucial for achieving sustainable transportation. This project applies **machine learning** to analyze and predict factors influencing EV adoption using real-world data. We implemented **classification models** to predict vehicle adoption trends based on attributes like electric range, vehicle make, model year, and fuel eligibility.

---

## 📂 Dataset Description  
The dataset consists of **223,995 records** and contains information about electric vehicles registered across different states. The key columns include:

- **Vehicle Information**: VIN, Make, Model, Model Year  
- **Location Details**: County, City, State, Postal Code  
- **Electric Vehicle Features**: Electric Vehicle Type, Electric Range, Clean Alternative Fuel Vehicle (CAFV) Eligibility  
- **Pricing & Identification**: Base MSRP, DOL Vehicle ID, Legislative District  

After preprocessing, the dataset was used to **train classification models**.

---

## 🛠 Data Preprocessing  
The following preprocessing steps were performed before training the models:

1. **Handling Missing Values**:  
   - Dropped irrelevant or duplicate columns.  
   - Imputed missing numerical values using **median imputation**.  
   - Filled missing categorical values with the **most frequent category**.  

2. **Feature Engineering & Encoding**:  
   - Converted categorical features into numerical form using **One-Hot Encoding**.  
   - Scaled numerical values using **Min-Max Scaling** for better model performance.  

3. **Class Balancing**:  
   - Checked class distribution and applied **Synthetic Minority Over-sampling Technique (SMOTE)** if necessary.  

---

## 📊 Data Visualization  
To gain insights, we created **13+ professional visualizations**, including:  
✔️ **Distribution of Electric Vehicle Types**  
✔️ **Electric Range vs. MSRP Analysis**  
✔️ **State-wise Clean Energy Vehicle Adoption Trends**  
✔️ **Most Popular Electric Vehicle Makes & Models**  
✔️ **Correlation Heatmap of Key Features**  
✔️ **Legislative Districts Supporting EVs**  
✔️ **Vehicle Adoption Trends Over the Years**  

These visualizations provided insights into **factors driving EV adoption**.

---

## 🔍 Machine Learning Models Used  
We trained and compared three **classification models**:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Decision Tree Classifier**  

Each model was fine-tuned using **hyperparameter optimization** to improve performance and prevent overfitting.

---

## 📌 Model Performance & Results  

### **🔹 Logistic Regression**
- **Accuracy**: `98.73%`
- **Classification Report:**
  - Precision: `98-99%`
  - Recall: `93-100%`
  - F1-score: `96-99%`

### **🔹 Random Forest**
- **Accuracy**: `98.60%`
- **Classification Report:**
  - Precision: `97-100%`
  - Recall: `89-100%`
  - F1-score: `94-100%`

### **🔹 Decision Tree**
- **Accuracy**: `100%`
- **Classification Report:**
  - Precision: `100%`
  - Recall: `100%`
  - F1-score: `100%`

### **📊 Model Comparison**
| Model               | Accuracy  | Precision  | Recall  | F1-score  |
|---------------------|----------|------------|---------|-----------|
| Logistic Regression | 98.73%   | 98-99%     | 93-100% | 96-99%    |
| Random Forest       | 98.60%   | 97-100%    | 89-100% | 94-100%   |
| Decision Tree       | 100%     | 100%       | 100%    | 100%      |

📌 **Observations**:
- The **Decision Tree model achieved 100% accuracy**, indicating possible overfitting.  
- **Logistic Regression and Random Forest** performed well with high precision and recall.  
- The **Random Forest model balanced generalization and accuracy better** than Decision Tree.

---

## 📌 Conclusion  
✔️ **Decision Trees tend to overfit**, so for a more generalized model, **Random Forest is preferable**.  
✔️ **EV adoption is influenced by factors like Electric Range, Model Year, and CAFV eligibility**.  
✔️ **Government incentives and regional support** significantly impact adoption trends.  

This project showcases how **machine learning can analyze market trends and predict adoption patterns**, which can help policymakers and manufacturers in **accelerating clean energy adoption**.


