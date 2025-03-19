# **Food Allergy & Intolerance Dataset**
### **📂 Dataset for Predicting Food Allergies & Intolerance Effects**

## **📌 Overview**
This dataset contains **synthetic data** related to food allergies and intolerances. It includes key features such as **age, gender, symptoms, food type consumed, IgE levels, and allergy history**, helping in predictive modeling for **food allergy detection and reaction severity assessment**.

This dataset is designed for **Exploratory Data Analysis (EDA), Classification, and Regression** to predict:
- **(1) Whether a person is allergic to a specific food item (Classification)**
- **(2) The severity of allergic reactions (Regression)**

---

## **📑 Dataset Information**
- **Total Rows:** 10,000
- **Total Columns:** 11
- **Target Variable:** `Allergic` (1 = Yes, 0 = No)

---

## **📊 Features & Column Descriptions**
| Column Name           | Data Type   | Description |
|----------------------|------------|-------------|
| **Age**             | Integer     | Age of the individual (5 - 80 years) |
| **Gender**          | Categorical | Gender of the individual (Male, Female, Other) |
| **Family_History**  | Categorical | Whether family has a history of allergies (Yes/No) |
| **Previous_Reaction** | Categorical | Past allergic reaction severity (None, Mild, Moderate, Severe) |
| **Symptoms**        | Categorical | Common allergic symptoms (Skin rash, Swelling, Nausea, Breathing issues, No symptoms) |
| **Food_Type**       | Categorical | Type of food consumed (Dairy, Nuts, Seafood, Gluten, Eggs) |
| **Food_Frequency**  | Integer     | Frequency of food consumption (times per month) |
| **Medical_Conditions** | Categorical | Existing conditions (Asthma, Eczema, None) |
| **IgE_Levels**      | Float       | Immunoglobulin E (IgE) levels (higher levels indicate allergic responses) |
| **Severity_Score**  | Integer     | Severity score (0 = no reaction, 10 = extreme reaction) |
| **Allergic**        | Binary (0/1) | Target variable: 1 = Allergic, 0 = Not Allergic |

---

## **📌 Potential Use Cases**
✔ **Exploratory Data Analysis (EDA)** – Understanding the relationship between food, allergies, and medical history.  
✔ **Predictive Modeling** – Machine learning models for allergy prediction.  
✔ **Classification Tasks** – Identify allergic individuals based on symptoms and food type.  
✔ **Regression Tasks** – Estimate reaction severity based on IgE levels and past reactions.  
✔ **Healthcare Insights** – Study food allergies in different demographics.

---

## **🖥️ How to Use the Dataset**
1. **Download the CSV** file and load it into Python:
   ```python
   import pandas as pd
   df = pd.read_csv("food_allergy_dataset.csv")
   ```
2. **Explore the dataset:**
   ```python
   df.head()
   df.info()
   df.describe()
   ```
3. **Perform Feature Engineering** (e.g., encoding categorical variables)
4. **Train a Machine Learning Model** (e.g., Logistic Regression, Decision Tree, Random Forest, or Neural Networks)
5. **Evaluate Model Performance** (Accuracy, Precision, Recall, RMSE)

---

## **📂 Download the Dataset**
You can access the dataset **[here](https://github.com/your-username/food-allergy-dataset/blob/main/food_allergy_dataset.csv)** *(Update the URL with your actual GitHub link).*

---

## **📜 License & Citation**
- This dataset is **synthetically generated** for academic and research purposes.
- Feel free to use it for your projects, but please cite this repository when using it.
