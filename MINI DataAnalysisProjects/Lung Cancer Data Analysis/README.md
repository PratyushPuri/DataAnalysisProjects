# Lung Cancer Data Analysis

<div align="center">
  
![Lung Cancer](../../assets/Lung.jpg)

</div>

A comprehensive data science project analyzing lung cancer patient data from across Europe to identify risk factors, treatment patterns, and survival outcomes.

## 📊 Dataset Overview

This project analyzes a large-scale lung cancer dataset containing **890,000 patient records** from **27 European countries**, providing insights into cancer patterns, treatment effectiveness, and survival rates across different demographic and clinical factors.

### Key Dataset Features
- **Patient Demographics**: Age (4-104 years), gender, country of origin
- **Clinical Measurements**: BMI, cholesterol levels, blood pressure
- **Medical History**: Family history, smoking status, comorbidities
- **Cancer Information**: Stage (I-IV), diagnosis dates (2014-2025)
- **Treatment Data**: Treatment type, duration, survival outcomes
- **Survival Rate**: 22% overall survival rate across all patients

## 🔍 Data Structure

| Variable | Description | Data Type | Example Values |
|----------|-------------|-----------|----------------|
| `id` | Unique patient identifier | Integer | 1, 2, 3... |
| `age` | Patient age in years | Float | 64.0, 50.0, 65.0 |
| `gender` | Patient gender | String | Male, Female |
| `country` | Country of diagnosis | String | Sweden, Netherlands, Hungary |
| `diagnosis_date` | Date of cancer diagnosis | Date | 2016-04-05, 2023-04-20 |
| `cancer_stage` | Cancer progression stage | String | Stage I, Stage II, Stage III, Stage IV |
| `family_history` | Family history of cancer | String | Yes, No |
| `smoking_status` | Smoking behavior | String | Current Smoker, Former Smoker, Passive Smoker, Never Smoked |
| `bmi` | Body Mass Index | Float | 29.4, 41.2, 44.0 |
| `cholesterol_level` | Cholesterol measurement | Integer | 199, 280, 268 |
| `hypertension` | High blood pressure | Binary | 0 (No), 1 (Yes) |
| `asthma` | Asthma condition | Binary | 0 (No), 1 (Yes) |
| `cirrhosis` | Liver cirrhosis | Binary | 0 (No), 1 (Yes) |
| `other_cancer` | Other cancer history | Binary | 0 (No), 1 (Yes) |
| `treatment_type` | Primary treatment method | String | Chemotherapy, Surgery, Combined, Radiation |
| `end_treatment_date` | Treatment completion date | Date | 2017-09-10, 2024-06-17 |
| `survived` | Patient survival status | Binary | 0 (No), 1 (Yes) |

## 📈 Key Statistics

### Demographics
- **Age Distribution**: Mean age of 55 years (range: 4-104)
- **Gender Split**: 50% male, 50% female
- **Geographic Coverage**: 27 European countries (Malta most represented)

### Clinical Characteristics
- **BMI**: Average 30.5 (range: 16.0-45.0)
- **Cholesterol**: Average 234 mg/dL (range: 150-300)
- **Hypertension**: 75% of patients
- **Asthma**: 47% of patients
- **Cirrhosis**: 23% of patients

### Cancer Patterns
- **Stage Distribution**: Stage III most common (25% of cases)
- **Smoking Status**: 
  - Passive Smokers: 25% (most common)
  - Current Smokers: ~25%
  - Former Smokers: ~25%
  - Never Smoked: ~25%

### Treatment Approaches
- **Chemotherapy**: 25% of cases (most common)
- **Surgery**: ~25%
- **Combined Therapy**: ~25%
- **Radiation**: ~25%

## 🛠️ Technical Implementation

### Dependencies
```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from scipy import stats
from scipy.stats import mstats
```

### Data Processing Features
- **Data Encoding**: Categorical variables converted to numerical format
- **Feature Engineering**: BMI categorization, date processing
- **Data Cleaning**: Missing value handling and type conversion
- **Statistical Analysis**: Survival analysis and risk factor identification


## 🎯 Research Questions

This analysis addresses several key research questions:

1. **Risk Factors**: Which demographic and clinical factors most strongly predict lung cancer survival?
2. **Treatment Effectiveness**: How do different treatment approaches compare in terms of survival outcomes?
3. **Geographic Patterns**: Are there regional differences in cancer stages and treatment success?
4. **Smoking Impact**: How does smoking status correlate with cancer stage and survival?
5. **Comorbidity Effects**: What role do pre-existing conditions play in treatment outcomes?

## 📊 Analysis Workflow

1. **Data Import & Exploration**
   - Load 890K patient records
   - Initial data profiling and quality assessment
   - Missing value analysis

2. **Data Preprocessing**
   - Categorical encoding (gender, family history, cancer stage)
   - Feature engineering (BMI categorization, date processing)
   - Data type optimization

3. **Exploratory Data Analysis**
   - Demographic distribution analysis
   - Clinical characteristic patterns
   - Treatment and outcome correlations

4. **Statistical Analysis**
   - Survival analysis by patient groups
   - Risk factor identification
   - Treatment effectiveness comparison

5. **Visualization & Reporting**
   - Interactive dashboards
   - Statistical summaries
   - Clinical insights documentation

## 🔬 Key Findings

### Survival Patterns
- **Overall Survival Rate**: 22% across all patients
- **Stage-Specific Survival**: Early-stage cancers show better outcomes
- **Treatment Response**: Combined therapy shows promising results

### Risk Factors
- **Age**: Older patients face higher mortality risk
- **Smoking**: Current smokers have worse outcomes than never smokers
- **Comorbidities**: Multiple conditions compound treatment challenges

### Geographic Insights
- **Country Variations**: Treatment approaches vary by healthcare system
- **Diagnostic Patterns**: Earlier detection in some regions

## 💡 Clinical Implications

This analysis provides valuable insights for:
- **Healthcare Providers**: Treatment decision support
- **Public Health**: Population-level intervention strategies
- **Researchers**: Hypothesis generation for clinical trials
- **Policy Makers**: Healthcare resource allocation

## 🚀 Future Enhancements

- **Machine Learning Models**: Predictive modeling for survival outcomes
- **Time Series Analysis**: Temporal trends in diagnosis and treatment
- **Advanced Visualization**: Interactive dashboards and real-time analytics
- **Integration**: Connection with external healthcare databases

## 👨‍💻 Author

**Pratyush Puri**  
Data Science & AI Enthusiast  
Specializing in Generative AI, NLP, Machine Learning, Deep Learning, and Data Analytics  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]( https://linkedin.com/in/pratyushpuri ) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)]( https://github.com/PratyushPuri ) [![Website](https://img.shields.io/badge/My_Website-4CAF50?style=for-the-badge&logo=chrome&logoColor=white)]( https://www.pratyushpuri.space )

---

*This analysis is intended for research and educational purposes. Clinical decisions should always be made in consultation with qualified healthcare professionals.*
