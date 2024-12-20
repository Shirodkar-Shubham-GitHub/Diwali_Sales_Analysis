# Diwali Sales Analysis

## Introduction
Diwali, the festival of lights, is one of the most celebrated occasions in India, marked by grand celebrations and significant shopping activities. Businesses across various sectors witness a surge in sales during this festive season, offering discounts and promotions to attract customers. This project, Diwali Sales Data Analysis, aims to analyze sales data during the Diwali season to uncover valuable insights into customer behavior, purchasing patterns, and product performance.

## Dataset Description
The dataset used for this analysis contains detailed sales data from the Diwali festive season. It includes information such as customer demographics (age, gender, marital status), purchase details (product categories, quantity, and amount), and geographical insights (city and state). This dataset serves as the foundation for identifying patterns and trends in customer behavior and sales performance.

## Objective
The primary objective of this project is to analyze Diwali sales data to uncover actionable insights into customer behavior, purchasing patterns, and product performance. By understanding key trends such as high-performing product categories, regional sales distribution, and customer demographics, the project aims to help businesses optimize their marketing strategies and improve sales outcomes during the festive season.

## Tools and Technologies Used
The following tools and technologies were utilized in this project:
* **Python**: For data manipulation, analysis, and visualization.
* **Pandas**: To clean, preprocess, and analyze the dataset efficiently.
* **NumPy**: For numerical operations and handling large datasets.
* **Matplotlib**: To create static visualizations and charts.
* **Seaborn**: For advanced and aesthetically pleasing visualizations.
* **Jupyter Notebook**: As the development environment for interactive data analysis.

## Data Preprocessing
Data preprocessing is a critical step to ensure the dataset is clean and ready for analysis. The following steps were performed on the Diwali sales dataset:
1. **Handling Missing Values**:
   * Identified and filled or removed missing or null values to maintain data consistency.
2. **Data Cleaning**:
   * Removed duplicates and irrelevant entries.
   * Standardized data formats for columns like dates and categorical values.
3. **Data Transformation**:
   * Encoded categorical variables such as gender and marital status using label encoding for better analysis.
   * Transformed and aggregated numerical columns, such as sales and quantity, to extract meaningful insights.
4. **Outlier Detection**:
   * Identified and treated outliers in numerical fields like purchase amount to ensure accurate analysis.
5. **Feature Selection**:
   * Selected relevant columns such as customer demographics, product details, and purchase amount for analysis.

## Exploratory Data Analysis (EDA)
**1. Gender**
* **Insights**:
  * Females contributed more to sales than males, especially in product categories like clothing and home decor.
  * Male customers preferred electronics and gadgets during the Diwali season.
* **Visualization**:
  * A bar chart was used to compare total sales by gender.
**2. Age Group**
* **Insights**:
  * The age group 26-35 years had the highest purchase frequency and sales contribution.
  * Younger customers (18-25 years) leaned towards fashion and gadgets, while older customers (36-50 years) preferred home decor and appliances.
* **Visualization**:
  * A pie chart displayed the proportion of purchases by different age groups.
  * A bar chart was used to compare which age group are the most of the buyers.
 
**3. State**
* **Insights**:
  * States with metropolitan cities (e.g., Maharashtra, Delhi, Karnataka) recorded the highest sales, driven by larger populations and higher spending capacities.
  * Smaller states showed limited sales activity, likely due to lower customer density.
* **Visualization**:
  * A heatmap highlighted the distribution of sales across different states.
  * A bar chart was used for amount spend across different states.

**4. Marital Status**
* **Insights**:
  * Married customers contributed significantly more to total sales than single customers.
  * Married individuals showed higher interest in family-oriented products such as appliances, home decor, and clothing.
* **Visualization**:
  * A grouped bar chart compared sales and amount for married and single customers.


