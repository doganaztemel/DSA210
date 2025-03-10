# Research Proposal: The Relationship Between GDP per Capita and Women's Tertiary Education Attainment in OECD Countries

## 1. Research Question

- **Is there a significant relationship between GDP per capita and women’s tertiary education attainment rates in OECD countries?**

## 2. Motivation

Understanding the interplay between economic prosperity and educational attainment is crucial for policymakers aiming to promote sustainable development and gender equality. In many OECD countries, women have surpassed men in tertiary education attainment, with **52% of 25-34-year-old women holding tertiary qualifications compared to 39% of men**. Investigating how GDP per capita influences these educational trends can provide insights into the effectiveness of economic policies and investments in education.

## 3. Data Sources

This study will utilize the following datasets:

- **OECD Education Statistics:**  
  - *Description:* Provides data on educational attainment by gender across OECD countries.  
  - *Key Variables:*  
    - Percentage of women aged 25-64 with tertiary education.  
    - Percentage of men aged 25-64 with tertiary education.  

- **OECD Economic Indicators:**  
  - *Description:* Offers data on economic performance indicators, including GDP per capita.  
  - *Key Variables:*  
    - GDP per capita in USD.  

## 4. Methodology

### 4.1 Data Collection and Preparation

- Gather data from OECD databases for the most recent year available.  
- Ensure data consistency by aligning definitions and measurement units.  
- Address missing values through appropriate imputation methods.  

### 4.2 Exploratory Data Analysis (EDA)

- Compute summary statistics (mean, median, standard deviation) for GDP per capita and women’s tertiary education attainment rates.  
- Visualize data distributions using histograms and boxplots. ([Source: Wikipedia](https://en.wikipedia.org/wiki/Exploratory_data_analysis))  
- Examine the relationship between GDP per capita and women’s tertiary education attainment using scatter plots.  

### 4.3 Statistical Analysis

#### Correlation Analysis

- Calculate the **Pearson correlation coefficient** to assess the strength and direction of the relationship between GDP per capita and women’s tertiary education attainment.  

#### Regression Analysis

- Perform a **simple linear regression** with women’s tertiary education attainment as the dependent variable and GDP per capita as the independent variable.  
- Evaluate the regression model’s assumptions and fit.  

## 5. Tools Used

This study will use **Python** for data analysis and visualization. The following libraries will be utilized:

- **Pandas:** For data manipulation and analysis.  
- **NumPy:** For numerical computations.  
- **Matplotlib & Seaborn:** For visualizing distributions and relationships.  
- **Scipy & Statsmodels:** For statistical hypothesis testing and regression modeling.  
