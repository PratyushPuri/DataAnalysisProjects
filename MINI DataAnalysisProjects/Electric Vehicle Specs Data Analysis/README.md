# 🚗 Electric Vehicle Specs Data Analysis 2025

## 📊 Project Overview

This comprehensive data analysis project examines electric vehicle specifications across 478 vehicles from 22 different parameters, providing deep insights into the current EV market landscape, technology trends, and consumer preferences. The analysis reveals critical patterns in battery technology, charging capabilities, performance metrics, and market positioning strategies across different vehicle segments.

## 🎯 Key Objectives

- **Market Analysis**: Understand current EV market segmentation and brand positioning
- **Technology Trends**: Identify patterns in battery capacity, charging speeds, and efficiency
- **Performance Insights**: Analyze relationships between drivetrain, range, and acceleration
- **Consumer Guidance**: Provide data-driven recommendations for stakeholders
- **Future Predictions**: Identify emerging trends and technology developments

## 📈 Dataset Characteristics

- **Total Vehicles**: 478 electric vehicles
- **Specifications**: 22 detailed parameters per vehicle
- **Data Source**: Electric Vehicle Specifications Dataset 2025
- **Coverage**: Multiple brands, segments, and drivetrain configurations
- **Analysis Period**: 2025 market data

### Key Variables Analyzed
- Battery capacity (kWh)
- Range (km)
- Charging speed (kW)
- Price segments
- Drivetrain types (AWD, RWD, FWD)
- Acceleration (0-100 km/h)
- Top speed
- Vehicle segments
- Brand information
- Efficiency metrics

## 🔍 Analysis Methodology

### 1. **Data Preprocessing**
- **Data Loading**: Import and initial dataset exploration
- **Quality Assessment**: Check for duplicates, null values, and data types
- **Outlier Detection**: Identify and handle anomalous data points
- **Data Cleaning**: Fill missing values and standardize formats

### 2. **Exploratory Data Analysis (EDA)**
- **Price Segment Analysis**: Market segmentation by price ranges
- **Range Distribution**: Statistical analysis of vehicle range capabilities
- **Brand Analysis**: Comparative performance across manufacturers
- **Correlation Analysis**: Relationships between key specifications

### 3. **Deep-Dive Analysis**
- **Battery Technology**: Capacity vs efficiency patterns across segments
- **Drivetrain Impact**: Performance metrics by drivetrain configuration
- **Charging Capabilities**: Fast charging trends and market positioning
- **Market Segmentation**: Luxury, mid-range, and economy segment characteristics

### 4. **Statistical Analysis**
- Correlation analysis between specifications
- Descriptive statistics for all numerical variables
- Segment-wise aggregations and comparisons
- Outlier analysis and treatment strategies

## 📊 Key Findings & Insights

### 🔋 **Battery & Range Performance**
- **Average Range**: Most EVs fall within 300-500 km range bracket
- **Premium Advantage**: Luxury segments achieve 600+ km consistently
- **Market Leaders**: Tesla, Mercedes-Benz, BMW lead in range performance
- **Consumer Threshold**: 400+ km appears to be mainstream acceptance point

### 🏭 **Brand Market Positioning**
- **Volume Leader**: Tesla dominates with highest model count
- **Premium Focus**: German manufacturers concentrate on luxury segments
- **Emerging Players**: Chinese brands showing aggressive market entry
- **Specialization**: Some brands focus on specific segments rather than broad coverage

### ⚡ **Charging Technology Revolution**
- **Power Range**: 50-350 kW DC fast charging capabilities
- **Segment Differentiation**: Premium segments offer 200+ kW vs economy models
- **Infrastructure Readiness**: Market prepared for ultra-fast charging networks
- **Future-Proofing**: Latest models designed for next-gen charging infrastructure

### 🚙 **Drivetrain Performance Impact**
- **AWD Advantage**: Superior acceleration performance
- **RWD Efficiency**: Better energy efficiency for long-distance travel
- **FWD Economy**: Most cost-effective for urban mobility
- **Performance Trade-offs**: Inverse relationship between acceleration and efficiency

## 📊 Visualizations & Analysis

The notebook includes 13+ comprehensive visualizations:

1. **Box Plots**: Outlier detection across all numerical variables
2. **Histograms**: Distribution analysis of key specifications
3. **Scatter Plots**: Correlation analysis between price, range, and performance
4. **Bar Charts**: Brand comparison and segment analysis
5. **Heatmaps**: Correlation matrices for specification relationships

## 🛠️ Technical Implementation

### Libraries & Tools Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
import warnings
```

### Analysis Techniques Applied
- **Descriptive Statistics**: Mean, median, standard deviation analysis
- **Correlation Analysis**: Pearson correlation coefficients
- **Outlier Detection**: Statistical and visual methods
- **Groupby Operations**: Segment-wise aggregations
- **Data Visualization**: Multiple chart types for comprehensive insights

## 🎯 Market Segmentation Analysis

### **Luxury Segment**
- Battery capacity: 80-100+ kWh
- Range performance: 500+ km
- Fast charging: 200+ kW
- Premium brand concentration

### **Mid-Range Segment**
- Battery capacity: 60-80 kWh
- Range performance: 400-500 km
- Charging speed: 100-150 kW
- Highest market volume

### **Economy Segment**
- Battery capacity: 40-60 kWh
- Range performance: 250-400 km
- Charging speed: 50-100 kW
- Price-sensitive positioning

## 📝 Key Recommendations

### **For Manufacturers**
1. Focus on 400+ km range as minimum viable product
2. Invest in fast charging capabilities (150+ kW) as differentiator
3. Optimize efficiency ratios for cost-sensitive segments
4. Develop platform strategies for economies of scale

### **For Consumers**
1. Prioritize range over battery capacity when evaluating vehicles
2. Consider regional charging infrastructure availability
3. Evaluate total cost of ownership including efficiency
4. Future-proof purchases with advanced charging capabilities

### **For Policymakers**
1. Standardize charging infrastructure for emerging capabilities
2. Incentivize efficiency improvements over capacity increases
3. Support R&D in battery technology and charging infrastructure
4. Create segment-specific policies for different use cases

## 🚀 Future Research Opportunities

### **Dataset Expansions**
- **Temporal Analysis**: Historical EV data (2015-2025) for technology evolution
- **Geographic Analysis**: Regional market preferences and adoption patterns
- **Consumer Behavior**: Purchase decision factors and satisfaction metrics
- **Competitive Intelligence**: Patent analysis and R&D investment correlation

### **Advanced Analytics**
- **Machine Learning**: Price prediction models and market segmentation
- **Predictive Analytics**: Range optimization and charging network planning
- **Recommendation Systems**: Consumer preference-based vehicle recommendations


## 🏃‍♂️ How to Run

1. **Clone the repository**
2. **Install required dependencies**:
```python
pip install pandas numpy matplotlib seaborn scipy
```
3. **Open the Jupyter notebook**:
```python
jupyter notebook ev-specs.ipynb
```
4. **Run all cells** to reproduce the complete analysis

## 📊 Dataset Source

The analysis uses the Electric Vehicle Specifications Dataset 2025, containing comprehensive specifications for 478 electric vehicles across multiple brands, segments, and configurations.

## 👨‍💻 Author

**Pratyush Puri**  
Data Science & AI Enthusiast  <br>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]( https://linkedin.com/in/pratyushpuri ) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)]( https://github.com/PratyushPuri ) [![Website](https://img.shields.io/badge/My_Website-4CAF50?style=for-the-badge&logo=chrome&logoColor=white)]( https://www.pratyushpuri.space )


---

*This analysis provides a comprehensive view of the 2025 electric vehicle market, offering valuable insights for manufacturers, consumers, and policymakers in the rapidly evolving EV landscape.*

