# CDC_Diabetes_Health_Indicators
 **Short description:** AAI-500-01 final project: CDC Diabetes dataset is used for exploratory data analysis and modeling


**Team 1 Members:**

Ali Abdul-Hameed

Sai Gautham Bandi

Peng Wang


**Dataset:**

The dataset "CDC diabetes health indicators" is from the website: https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators 

**Target:**

To better understand the relationship between  lifestyle and diabetes in the US

# 🩺 Diabetes Health Indicators Dataset

### 📘 Overview
The **Diabetes Health Indicators Dataset** contains healthcare, demographic, and lifestyle survey data collected from U.S. adults, along with their diabetes diagnosis.  
It includes **21 features** (demographics, medical history, and behavioral indicators) and a **target variable** that classifies individuals as *diabetic*, *pre-diabetic*, or *healthy*.

---

### 📊 Dataset Summary

| **Property** | **Description** |
|---------------|------------------|
| **Instances** | 253,680 |
| **Features** | 21 |
| **Feature Types** | Binary (categorical), Integer (ordinal) |
| **Target Variable** | `Diabetes_012` → 0 = healthy, 1 = pre-diabetic, 2 = diabetic |
| **Data Type** | Tabular, Multivariate |
| **Associated Task** | Classification |
| **Missing Values** | No |
| **Source** | [CDC BRFSS 2014](https://www.cdc.gov/brfss/annual_data/annual_2014.html) |
| **Subject Area** | Health and Medicine |
| **Funded By** | Centers for Disease Control and Prevention (CDC) |

---

### 🎯 Purpose
This dataset was created to help researchers **analyze the relationship between lifestyle factors and diabetes prevalence** in the United States.  
Each record represents one individual’s survey and health information.

---

### ⚙️ Data Processing Notes
- Age values were **bucketed** into 13 categories (`_AGEG5YR`).
- All variables are **numerical (binary or integer)** — no one-hot encoding is required.
- Recommended data splitting methods:  
  - **Cross-validation**, or  
  - **Fixed train/validation/test split**.

---

### ⚖️ Sensitive Attributes
The dataset includes personal demographic attributes:
- **Gender**
- **Income**
- **Education level**

Use responsibly and ensure compliance with data ethics policies.

---

### 🧩 Feature Summary

| **Variable Name** | **Role** | **Type** | **Description** |
|--------------------|-----------|-----------|------------------|
| `Diabetes_012` | Target | Binary | 0 = healthy, 1 = pre-diabetic, 2 = diabetic |
| `HighBP` | Feature | Binary | High blood pressure |
| `HighChol` | Feature | Binary | High cholesterol |
| `CholCheck` | Feature | Binary | Cholesterol check in past 5 years |
| `BMI` | Feature | Integer | Body Mass Index |
| `Smoker` | Feature | Binary | Smoked ≥ 100 cigarettes in lifetime |
| `Stroke` | Feature | Binary | Ever diagnosed with stroke |
| `HeartDiseaseorAttack` | Feature | Binary | Coronary heart disease or heart attack |
| `PhysActivity` | Feature | Binary | Physical activity in past 30 days |
| `Fruits` | Feature | Binary | Eats fruits daily |
| `Veggies` | Feature | Binary | Eats vegetables daily |
| `HvyAlcoholConsump` | Feature | Binary | Heavy alcohol consumption |
| `AnyHealthcare` | Feature | Binary | Has any healthcare coverage |
| `NoDocbcCost` | Feature | Binary | Couldn’t see doctor due to cost |
| `GenHlth` | Feature | Integer | Self-rated general health (1 = excellent → 5 = poor) |
| `MentHlth` | Feature | Integer | Number of days mental health was not good (0–30) |
| `PhysHlth` | Feature | Integer | Number of days physical health was not good (0–30) |
| `DiffWalk` | Feature | Binary | Difficulty walking or climbing stairs |
|

