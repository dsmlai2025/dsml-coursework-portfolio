### NETFLIX Business Case
 📺🎬📽️ **Netflix - Exploratory Data Analysis** 🍿👥👀

## 🎯 **Overview**
This repository contains an exploratory data analysis (EDA) project focusing on Netflix data. 
The goal of this project is to clean the data , unnest the comma seperated columns and treat the missing values, gain insights, visualize trends, and explore patterns within the Netflix dataset. 

🏷️ **Project Objective:**
    Uncover patterns, visualize trends, and gain insights into Netflix's content and user reviews.

## 📊 **Dataset**
See the `data` subfolder

## 🎓 **Concepts Demonstrated**
[Insert your NumPy/Pandas/Viz tables here]

#### 📝 Project Report
    You can access the project python file here -> Python
    You can access the project report in pdf here -> Report
    
## 🔍 **Approach**

| Step | Task | Tools/Methods |
|------|------|---------------|
| **1. Data Loading** | Import CSV, inspect structure | `pd.read_csv()`, `df.info()` |
| **2. Preprocessing** | MD5 Show_ids, clean ratings | Custom `md5(title+year)`, `fillna()` |
| **3. EDA** | Distributions, correlations | `df.describe()`, `corr()` heatmap |
| **4. Visualization** | Genre trends, country analysis | Plotly pie/bar charts, line plots |
| **5. Insights** | Top findings, business implications | Statistical summaries, trend analysis |

**Flow**: Raw → Clean → Analyze → Visualize → Insights

## 🎓 **Concepts Demonstrated**
[NumPy/Pandas/Viz tables]

## 📈 **Key Findings**

## 🚀 **Quick Start**
```bash
cd dav-pythonlib/projects/netflix-eda
jupyter notebook 01_netflix_eda.ipynb
