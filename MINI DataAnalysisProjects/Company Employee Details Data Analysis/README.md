# 🏢 Employee Data Analysis Project

<div align="center">
  
![Bank Churn](../../assets/churn.jpg)

</div>


<div align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen.svg" alt="Project Status">
  <img src="https://img.shields.io/badge/Data%20Science-Analytics-orange.svg" alt="Data Science">
  <img src="https://img.shields.io/badge/Visualizations-20+-purple.svg" alt="Visualizations">
</div>

## 📊 Project Overview

This comprehensive data analysis project explores employee demographics, retention patterns, and organizational dynamics using a dataset of **4,653 employees** across three major Indian cities (Bangalore, Pune, and New Delhi) spanning from 2012 to 2018. The project provides actionable insights for HR strategy and workforce planning through advanced statistical analysis and beautiful visualizations.

## 🎯 Key Objectives

- **Demographic Analysis**: Understanding workforce composition by education, age, gender, and location
- **Retention Insights**: Identifying factors affecting employee attrition and retention
- **Career Progression**: Analyzing compensation patterns and experience correlation
- **Organizational Planning**: Providing data-driven recommendations for HR strategy

## 📈 Dataset Information

| **Attribute** | **Description** | **Type** |
|---------------|-----------------|----------|
| Education | Educational qualification (Bachelors, Masters, PHD) | Categorical |
| JoiningYear | Year of joining (2012-2018) | Numerical |
| City | Work location (Bangalore, Pune, New Delhi) | Categorical |
| PaymentTier | Compensation tier (1-3) | Ordinal |
| Age | Employee age (22-41 years) | Numerical |
| Gender | Employee gender (Male, Female) | Categorical |
| EverBenched | Whether employee was benched (Yes, No) | Binary |
| ExperienceInCurrentDomain | Years of experience (0-7) | Numerical |
| LeaveOrNot | Attrition status (0=Stayed, 1=Left) | Binary |

**Dataset Size**: 4,653 records  
**Time Period**: 2012-2018  
**Geographic Coverage**: 3 cities in India

## 🔍 Analysis Components

### 🎨 Visualization Categories

#### **1. Demographic Visualizations (10 Questions)**
- Distribution analysis by education level
- Age patterns across cities
- Experience vs attrition relationships
- Gender-based payment tier analysis
- Yearly hiring trends
- Benching impact on retention
- Educational qualification effects on attrition

#### **2. Advanced Analytics (10 Additional Visualizations)**
- Bivariate and multivariate analysis
- Correlation matrices
- Bubble charts with multi-dimensional data
- Heatmaps for pattern identification
- Violin plots for distribution analysis
- Stacked visualizations for comparative analysis

### 📊 Key Findings Summary

| **Metric** | **Value** | **Insight** |
|------------|-----------|-------------|
| **Overall Attrition Rate** | 34.4% | Significant turnover requiring attention |
| **Dominant Education** | 77.4% Bachelors | Strong undergraduate talent base |
| **Average Age** | 29.4 years | Young, dynamic workforce |
| **Top Location** | Bangalore (47.9%) | Technology hub concentration |
| **High-Risk Group** | 0-2 years experience | Early-career attrition challenge |
| **Retention Champions** | PhD holders | Advanced degree loyalty |

## 🛠️ Technical Implementation

### **Libraries Used**
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
import warnings
```

### **Visualization Techniques**
- **Statistical Plots**: Histograms, box plots, violin plots
- **Categorical Analysis**: Count plots, stacked bars, pie charts
- **Correlation Analysis**: Heatmaps, scatter plots
- **Multi-dimensional**: Bubble charts, subplots
- **Advanced**: Donut charts, correlation matrices


## 🎯 Strategic Insights

### **🔴 Critical Findings**

#### **Workforce Demographics**
- **Education Distribution**: 77.4% Bachelors, 20.1% Masters, 2.5% PhD
- **Age Profile**: Mean age 29.4 years (young workforce)
- **Gender Balance**: 59.7% Male, 40.3% Female
- **Geographic Spread**: Bangalore-dominant (47.9%)

#### **Retention Challenges**
- **Early-Career Risk**: 0-2 years experience show highest attrition
- **Benching Impact**: Never-benched employees retain better
- **Education Effect**: PhD holders show superior retention
- **Experience Correlation**: 3-5 years experience = optimal retention

#### **Compensation Insights**
- **Fair Distribution**: Consistent payment tiers across demographics
- **Merit-Based**: Higher tiers correlate with broader experience
- **Geographic Equity**: No significant location-based bias

### **🔵 Recommendations**

#### **Immediate Actions**
1. **Onboarding Enhancement**: Robust programs for first 2 years
2. **Benching Process**: Redesign to minimize negative impact
3. **Mentorship Programs**: Leverage PhD holders for knowledge transfer
4. **Retention Incentives**: Target 0-2 year experience employees

#### **Long-term Strategy**
1. **Career Development**: Structured progression pathways
2. **Succession Planning**: Prepare for young workforce maturation
3. **Diversity Initiatives**: Maintain gender balance improvements
4. **Knowledge Management**: Formalize expertise retention

## 📋 Project Deliverables

### **📊 Analysis Reports**
- [x] Demographic Analysis (10 visualizations)
- [x] Advanced Analytics (10 visualizations)
- [x] Statistical Insights and Correlations
- [x] Comprehensive Conclusion Document

### **📈 Visualizations**
- [x] Beautiful, publication-ready charts
- [x] Consistent styling and color schemes
- [x] Insightful annotations and labels
- [x] Interactive and engaging presentations

### **📝 Documentation**
- [x] Detailed methodology explanations
- [x] Code documentation and comments
- [x] Insight summaries (30 words each)
- [x] Strategic recommendations

## 📚 Key Learning Outcomes

### **Technical Skills**
- Advanced data visualization techniques
- Statistical analysis and interpretation
- Multi-dimensional data exploration
- Professional report generation

### **Business Insights**
- HR analytics and workforce planning
- Retention strategy development
- Compensation analysis
- Organizational behavior patterns

### **Data Science Methods**
- Exploratory data analysis (EDA)
- Correlation and regression analysis
- Categorical data visualization
- Business intelligence reporting

## 🎨 Visualization Highlights

The project features **20+ unique visualizations** including:

- **Demographic Distributions**: Education, age, gender patterns
- **Retention Analysis**: Attrition by experience, education, benching
- **Compensation Insights**: Payment tiers across demographics
- **Temporal Trends**: Hiring patterns over time
- **Geographic Analysis**: City-wise employee distribution
- **Correlation Studies**: Multi-variate relationship exploration

Each visualization includes:
- ✅ Beautiful, professional styling
- ✅ Clear, informative titles
- ✅ Proper axis labels and legends
- ✅ Color-coded insights
- ✅ 30-word insight summaries

## 🔮 Future Enhancements

### **Potential Extensions**
- **Machine Learning Models**: Predictive attrition modeling
- **Real-time Dashboard**: Interactive visualization platform
- **Comparative Analysis**: Industry benchmarking
- **Longitudinal Studies**: Multi-year trend analysis

### **Additional Data Sources**
- Performance metrics integration
- Salary information analysis
- Employee satisfaction surveys
- Market compensation data

## 📧 Contact

For any questions or feedback, feel free to reach out:

**Pratyush Puri**  
Data Science & AI Enthusiast  
Specializing in Generative AI, NLP, Machine Learning, Deep Learning, and Data Analytics  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]( https://linkedin.com/in/pratyushpuri ) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)]( https://github.com/PratyushPuri ) [![Website](https://img.shields.io/badge/My_Website-4CAF50?style=for-the-badge&logo=chrome&logoColor=white)]( https://www.pratyushpuri.space )

---

<div align="center">
  <b>⭐ If you found this analysis helpful, please consider starring the repository! ⭐</b>
</div>