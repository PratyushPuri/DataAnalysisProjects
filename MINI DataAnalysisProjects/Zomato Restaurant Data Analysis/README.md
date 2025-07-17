# 🍽️ Zomato Restaurant Data Analysis

<div align="center">
  
![Zomato Restaurant](../../assets/zomato%20restaurant.jpg)

</div>

This repository contains an exploratory data analysis (EDA) of Zomato restaurant data, aimed at uncovering insights related to restaurant ratings, pricing, cuisines, cities, and customer behavior. The dataset includes a rich set of features such as dining and delivery ratings, votes, prices, cuisine types, and city-level data, enabling a multi-dimensional analysis of restaurant performance and customer preferences.

## 🔍 Overview

The analysis is structured to provide a comprehensive understanding of the restaurant ecosystem on Zomato. The dataset contains **123,657 rows and 26 columns**, with both numerical and categorical features. The notebook explores data distribution, correlations, and visualizations to identify trends and patterns that can help stakeholders make data-driven decisions.

## 📁 Dataset

The dataset used in this analysis is sourced from Kaggle and has been cleaned and enhanced for analysis. It includes the following key features:

- **Restaurant_Name**: Name of the restaurant
- **Dining_Rating / Delivery_Rating**: Ratings for dining and delivery services
- **Dining_Votes / Delivery_Votes**: Number of votes for dining and delivery
- **Cuisine**: Type of cuisine served
- **Place_Name / City**: Location and city of the restaurant
- **Item_Name**: Name of the food item
- **Prices**: Price of the item
- **Average_Rating**: Average rating of the restaurant
- **Total_Votes**: Total votes received by the restaurant
- **Price_per_Vote**: Price divided by total votes
- **Log_Price**: Logarithm of price
- **Is_Bestseller**: Whether the item is marked as a bestseller
- **Restaurant_Popularity**: Popularity metric based on votes
- **Avg_Rating_Restaurant / Avg_Price_Restaurant**: Average rating and price per restaurant
- **Avg_Rating_Cuisine / Avg_Price_Cuisine**: Average rating and price per cuisine
- **Avg_Rating_City / Avg_Price_City**: Average rating and price per city
- **Is_Highly_Rated / Is_Expensive**: Binary flags for high ratings and prices

## 🧹 Data Cleaning

- **Missing Values**: Minimal missing values found; no imputation required
- **Duplicates**: 22,127 duplicate rows removed, reducing the dataset to **101,530 rows**
- **Outliers**: Handled using IQR Winsorization to manage extreme values in numerical features
- **Column Renaming**: `Best_Seller` was renamed to `Item_Rating` for clarity
- **Column Drop**: `Is_Bestseller` was dropped due to lack of variability (only one unique value)

## 📊 Exploratory Data Analysis (EDA)

### 📈 Key Visualizations

#### 1. Restaurant Ratings by City
- **Visualization**: Boxplot showing the distribution of average ratings across cities
- **Insight**: Kolkata shows the most consistent ratings, while Mumbai has the highest variance, indicating differing levels of market maturity

#### 2. Price Distribution
- **Visualization**: Histogram of original price distribution (heavily right-skewed, most items under ₹300)
- **Log Transformation**: Reveals a more normal distribution, useful for modeling

#### 3. Median Prices by Cuisine
- **Visualization**: Bar chart of top 15 cuisines ranked by median price
- **Insight**: Continental and North Indian cuisines command premium pricing, while Beverages and Fast Food remain affordable

#### 4. Popularity vs. Price Efficiency
- **Visualization**: Violin plot examining the relationship between restaurant popularity and price per vote
- **Insight**: Higher popularity correlates with better price-per-vote efficiency, indicating effective pricing strategies

#### 5. Correlation Heatmap
- **Visualization**: Heatmap of correlation between numerical variables like ratings, votes, prices, and popularity
- **Insight**: Strong positive correlation between dining and delivery ratings, suggesting consistent service quality across channels

#### 6. Bestseller Distribution
- **Visualization**: Bar chart showing that the majority of items are not marked as bestsellers
- **Insight**: Untapped potential for menu optimization and strategic promotion of underperforming items

#### 7. Cuisine Rating vs. Price Analysis
- **Visualization**: Clustered bar chart comparing the proportion of highly rated and expensive items across cuisines
- **Insight**: Continental cuisine has the highest proportion of expensive items, while Beverages maintain high ratings at moderate prices

#### 8. Restaurant Popularity vs. Rating
- **Visualization**: Scatter plot with relationship between restaurant popularity and average rating, with color-coded pricing
- **Insight**: High-rated restaurants tend to be more popular and command premium prices

## 📌 Key Insights

### 🏆 Restaurant Performance
- High-rated restaurants attract more votes and command premium pricing
- There's a clear segmentation between value and premium segments

### 🍽️ Cuisine Strategy
- Continental and North Indian cuisines are premium-priced
- Beverages and Fast Food are affordable and highly rated, suggesting upselling opportunities

### 🌆 City-Level Trends
- Jaipur and Chandigarh have a higher concentration of expensive items
- Hyderabad maintains moderate pricing, indicating potential for premium pricing strategies

### 📉 Menu Optimization
- Over 95,000 items are not marked as bestsellers, highlighting opportunities for targeted promotions and menu reengineering

### 📊 Data Quality
- The dataset is well-structured with minimal missing values and robust categorical classifications

## 🛠️ Technical Details

### 📦 Libraries Used
- **pandas**: For data manipulation and analysis
- **matplotlib.pyplot and seaborn**: For data visualization
- **numpy**: For numerical operations and transformations

### 🧪 Data Transformation
- **Log Transformation**: Applied to price to normalize distribution
- **Winsorization**: Used to handle outliers in numerical columns

### 📈 Visualization Techniques
- Boxplots, histograms, bar charts, violin plots, scatter plots, and correlation heatmaps


## 📦 Installation

To run this notebook locally:

1. **Clone the repository**:
```git
git clone https://github.com/yourusername/zomato-restaurant-data-analysis.git
```

2. **Navigate to the directory**:
```git
cd zomato-restaurant-data-analysis
```

3. **Install dependencies**:
```python
pip install -r requirements.txt
```


4. **Launch Jupyter Notebook**:
```git
jupyter notebook
```

5. **Open** `notebooks/zomato_eda.ipynb` and run the cells

## 📝 Requirements

- [x] python 3.11+
- [x] pandas
- [x] scipy 
- [x] matplotlib
- [x] seaborn
- [x] numpy

## 📧 Contact

For any questions or feedback, feel free to reach out:

**Pratyush Puri**  
Data Science & AI Enthusiast  
Specializing in Generative AI, NLP, Machine Learning, Deep Learning, and Data Analytics  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]( https://linkedin.com/in/pratyushpuri ) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)]( https://github.com/PratyushPuri ) [![Website](https://img.shields.io/badge/My_Website-4CAF50?style=for-the-badge&logo=chrome&logoColor=white)]( https://www.pratyushpuri.space )

## 🚀 Future Work

- **Predictive Modeling**: Build models to predict restaurant ratings or pricing strategies
- **Customer Segmentation**: Use clustering techniques to identify customer behavior patterns
- **Time Series Analysis**: Explore how ratings and popularity evolve over time
- **Interactive Dashboard**: Build a dashboard using tools like Plotly or Dash for real-time exploration


