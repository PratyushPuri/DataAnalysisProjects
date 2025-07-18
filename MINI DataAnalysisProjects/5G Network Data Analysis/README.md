# 5G Network Data Analysis

<div align="center">
  
![Lung Cancer](../../assets/5g.jpg)

</div>



[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-red.svg)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-orange.svg)](https://seaborn.pydata.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📊 Project Overview

This comprehensive data analysis project examines **50,000 5G network performance records** spanning from 2024 to 2025, providing deep insights into network behavior, device performance, and user experience metrics across real-world 5G deployments. The analysis covers multiple dimensions including geographic distribution, carrier performance, device optimization, and technology adoption patterns.

**Created by:** [Pratyush Puri](https://linkedin.com/in/pratyushpuri)  
**Domain:** Data Science & Network Analytics  
**Technology Stack:** Python, Pandas, Matplotlib, Seaborn, SciPy

## 🎯 Key Objectives

- **Performance Analysis**: Evaluate 5G network speed, latency, and reliability metrics
- **Geographic Insights**: Compare network performance across 8 global locations
- **Carrier Benchmarking**: Analyze performance differences among 7 major carriers
- **Device Optimization**: Assess how different devices perform on 5G networks
- **Technology Evolution**: Track 5G SA vs NSA deployment patterns
- **User Experience**: Measure video streaming quality and connection stability

## 📈 Dataset Overview

### Data Specifications
- **Records**: 50,000 network performance measurements
- **Time Period**: 2024-2025
- **Locations**: 8 cities (Berlin, Chennai, Mumbai, Tokyo, San Francisco, etc.)
- **Carriers**: 7 major networks (AT&T, Verizon, Airtel, BSNL, etc.)
- **Devices**: 5 models (iPhone 14, Nord 4, GT 7, Galaxy S23, etc.)
- **Frequency Bands**: 5 bands (n28, n78, n260, etc.)

### Key Metrics Analyzed
- **Speed Performance**: Download speeds (100-999.99 Mbps), Upload speeds (20-150 Mbps)
- **Connection Quality**: Signal strength (-110 to -60 dBm), Latency (1-20 ms), Jitter (0.1-5 ms)
- **User Experience**: Video streaming quality, VoNR enablement, dropped connections
- **Environmental Factors**: Temperature, battery levels, network congestion
- **Network Behavior**: Handover counts, connection duration, data usage patterns

## 🔍 Analysis Highlights

### Network Performance Insights
- **Exceptional Speed**: Average download speeds of 551.18 Mbps demonstrate 5G's transformative potential
- **Low Latency**: Mean latency of 10.5 ms enables real-time applications (gaming, AR/VR, IoT)
- **Technology Distribution**: 5G NSA dominates with 16,793 records, showing ongoing network evolution
- **Reliability Challenges**: ~50% connection drop rate indicates areas for infrastructure improvement

### Geographic Performance
- **Berlin Leadership**: 6,346 records show concentrated testing or high network activity
- **Signal Variation**: -84.8 dBm average signal strength with significant geographic variation
- **Coverage Patterns**: Performance varies significantly across different cities and regions

### Carrier & Device Analysis
- **Carrier Competition**: AT&T leads with 8,382 records, showing market presence
- **Device Optimization**: Nord 4 most prevalent (10,076 records) with varying performance profiles
- **Frequency Strategy**: n78 band dominates (16,694 records) as primary mid-band deployment

## 📊 Visualizations & Analysis

### Performance Dashboards
1. **Network Performance Radar Chart** - Multi-dimensional performance comparison
2. **Geographic Heat Maps** - Location-based performance analysis
3. **Carrier Benchmarking** - Comprehensive carrier performance metrics
4. **Device Performance Matrix** - Device-carrier optimization analysis
5. **Technology Evolution Tracking** - 5G SA vs NSA deployment patterns

### Advanced Analytics
- **Correlation Analysis** - Relationships between performance metrics
- **Distribution Analysis** - Performance pattern identification
- **Trend Analysis** - Network evolution over time
- **Quality Assessment** - User experience optimization insights

## 🛠️ Technical Implementation

### Core Libraries
```python
import pandas as pd 
import numpy as np 
import matplotlib.pyplot as plt 
import seaborn as sns 
from scipy import stats 
```

### Data Processing Pipeline
1. **Data Loading**: CSV import with 50,000 records
2. **Quality Assessment**: No missing values across 21 columns
3. **Statistical Analysis**: Descriptive statistics and distribution analysis
4. **Visualization Creation**: 20+ unique charts and plots
5. **Insight Generation**: Performance benchmarking and recommendations

### Analysis Methodology
- **Descriptive Analytics**: Central tendencies, distributions, and variability
- **Comparative Analysis**: Performance across carriers, devices, and locations
- **Correlation Studies**: Relationships between network metrics
- **Visualization Design**: Custom plots optimized for different data types

## 📋 Key Findings

### 🚀 Performance Excellence
- **Ultra-High Speeds**: 5G delivers average 551 Mbps download speeds
- **Real-Time Ready**: Sub-11ms latency enables critical applications
- **Technology Leadership**: 5G SA shows superior performance vs NSA

### 🌍 Geographic Insights
- **Coverage Variation**: Significant performance differences across cities
- **Infrastructure Maturity**: Some locations show optimized network deployment
- **Market Focus**: Concentrated testing in key metropolitan areas

### 📱 Device & Carrier Analysis
- **Performance Variability**: Device-carrier combinations show distinct patterns
- **Optimization Opportunities**: Some pairings achieve superior performance
- **Market Dynamics**: Carrier competition drives network improvements

### 🔧 Technical Recommendations
- **Infrastructure Investment**: Address connection stability challenges
- **Coverage Optimization**: Improve signal strength consistency
- **Technology Migration**: Accelerate 5G SA deployment for full benefits

## 🎯 Business Impact

### For Network Operators
- **Performance Benchmarking**: Identify optimization opportunities
- **Infrastructure Planning**: Data-driven network investment decisions
- **Quality Assurance**: Customer experience improvement strategies

### For Device Manufacturers
- **Optimization Insights**: Device-network performance enhancement
- **Power Management**: Battery efficiency improvements
- **Market Positioning**: Competitive advantage through superior performance

### For Researchers & Analysts
- **Baseline Metrics**: Industry-standard performance benchmarks
- **Trend Analysis**: Network evolution patterns and predictions
- **Methodology Framework**: Replicable analysis approach


## 🔮 Future Enhancements

### Advanced Analytics
- **Machine Learning Models**: Predictive performance optimization
- **Anomaly Detection**: Network issue identification
- **Real-Time Monitoring**: Live network performance dashboards
- **Geographic Expansion**: Multi-country analysis

### Technical Improvements
- **Interactive Dashboards**: Plotly/Dash implementation
- **API Integration**: Real-time data ingestion
- **Cloud Deployment**: Scalable analysis infrastructure
- **Automated Reporting**: Scheduled insight generation

## 💡 Use Cases

### Academic Research
- **Network Performance Studies**: 5G deployment analysis
- **Technology Adoption Research**: SA vs NSA transition patterns
- **Geographic Analysis**: Urban network optimization studies

### Industry Applications
- **Network Planning**: Infrastructure investment decisions
- **Performance Optimization**: Carrier benchmark analysis
- **Device Testing**: Hardware-network compatibility assessment

### Career Development
- **Portfolio Project**: Demonstrates data science capabilities
- **Technical Skills**: Shows proficiency in Python, analytics, and visualization
- **Domain Expertise**: Telecommunications and network analysis knowledge


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

