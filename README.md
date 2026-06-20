# Yulu Bike Demand Analysis using Hypothesis Testing

## Project Overview

Yulu is India's leading micro-mobility platform that provides shared electric bicycles for daily commuting.

Recently, Yulu experienced a decline in revenue and wanted to understand the factors affecting demand for shared electric cycles. This project analyzes customer rental patterns and uses statistical hypothesis testing to identify variables that significantly impact bike rentals.

The analysis helps Yulu make data-driven decisions regarding fleet management, pricing strategies, and customer demand forecasting.

---

## Business Problem

Yulu wants to understand:

* Which factors significantly affect bike rental demand?
* How weather conditions influence rentals?
* Whether working days impact customer usage?
* How seasonal changes affect bike demand?
* Whether weather conditions depend on seasons?

The goal is to identify key demand drivers and provide recommendations to improve business performance.

---

## Dataset Information

The dataset contains bike rental information along with weather and seasonal conditions.

### Features

| Feature    | Description                  |
| ---------- | ---------------------------- |
| datetime   | Date and time                |
| season     | Spring, Summer, Fall, Winter |
| holiday    | Holiday indicator            |
| workingday | Working day indicator        |
| weather    | Weather condition            |
| temp       | Temperature                  |
| atemp      | Feels-like temperature       |
| humidity   | Humidity level               |
| windspeed  | Wind speed                   |
| casual     | Casual users                 |
| registered | Registered users             |
| count      | Total bike rentals           |

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

## Statistical Techniques Used

### Hypothesis Testing

#### 1. Two-Sample T-Test

Objective:

Determine whether working days have a significant impact on bike rentals.

**Null Hypothesis (H0):**
Average bike rentals are the same on working and non-working days.

**Alternative Hypothesis (H1):**
Average bike rentals differ between working and non-working days.

---

#### 2. ANOVA Test

Objective:

Check whether average rentals differ across:

* Seasons
* Weather Conditions

**Null Hypothesis (H0):**
Average rentals are equal across groups.

**Alternative Hypothesis (H1):**
At least one group differs significantly.

---

#### 3. Chi-Square Test

Objective:

Determine whether weather conditions depend on seasons.

**Null Hypothesis (H0):**
Weather and season are independent.

**Alternative Hypothesis (H1):**
Weather and season are dependent.

---

## Data Preprocessing

Performed:

* Missing value analysis
* Duplicate record verification
* Data type validation
* Outlier detection using boxplots
* Date-time feature extraction
* Statistical summary analysis

---

## Exploratory Data Analysis

### Univariate Analysis

* Bike Rental Distribution
* Weather Distribution
* Seasonal Distribution
* Temperature Distribution
* Humidity Distribution

### Bivariate Analysis

* Working Day vs Rentals
* Season vs Rentals
* Weather vs Rentals
* Temperature vs Rentals
* Humidity vs Rentals

### Correlation Analysis

* Correlation Heatmap
* Relationship between weather variables and demand

---

## Key Insights

### Working Day Impact

* Bike rentals vary significantly between working and non-working days.
* Commuting demand contributes strongly to rental volume.

### Seasonal Impact

* Demand increases during favorable weather seasons.
* Certain seasons consistently generate higher rental activity.

### Weather Impact

* Clear weather conditions result in the highest rentals.
* Rainy and extreme weather conditions reduce customer demand significantly.

### Temperature Influence

* Moderate temperatures encourage higher rentals.
* Extreme temperatures negatively affect usage.

### Humidity & Windspeed

* Higher humidity and windspeed tend to reduce rental demand.

---

## Hypothesis Testing Results

### Two-Sample T-Test

Finding:

Working day status has a statistically significant impact on bike rentals.

Business Impact:

Yulu should focus operational planning around weekday commuter demand.

---

### ANOVA Results

Finding:

Rental demand differs significantly across seasons and weather categories.

Business Impact:

Seasonal demand forecasting can improve bike allocation and availability.

---

### Chi-Square Test

Finding:

Weather conditions and seasons are statistically dependent.

Business Impact:

Seasonal weather patterns should be considered while forecasting future demand.

---

## Business Recommendations

### 1. Increase Fleet Availability on High-Demand Days

Deploy more bicycles during weekdays and peak commuting periods.

### 2. Optimize Operations Based on Weather

Adjust inventory and staffing according to weather forecasts.

### 3. Seasonal Planning

Increase bicycle availability during seasons with historically high demand.

### 4. Demand Forecasting

Use weather, temperature, and season as key variables in demand prediction models.

### 5. Target Commuters

Create promotional offers around metro stations, offices, and business districts during working days.

---

## Project Structure

Yulu-Hypothesis-Testing/

├── Dataset/
│   └── yulu_data.csv

├── Notebook/
│   └── Yulu_Hypothesis_Testing.ipynb

├── Images/
│   ├── Rental_Distribution.png
│   ├── Season_Analysis.png
│   ├── Weather_Analysis.png
│   ├── Correlation_Heatmap.png
│   └── Hypothesis_Test_Results.png

├── Reports/
│   └── Yulu_Business_Report.pdf

└── README.md

---

## Results

The analysis identified key drivers of bike rental demand and demonstrated how statistical hypothesis testing can be used to validate business assumptions.

The findings provide actionable recommendations for improving operational efficiency, customer targeting, and revenue growth.

---

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Statistical Hypothesis Testing
* T-Test
* ANOVA
* Chi-Square Test
* Data Visualization
* Business Analytics
* Python Programming

---

## Author

Vaishnavi Kothur

GitHub: https://github.com/vaishnavi-kothur
LinkedIn: https://linkedin.com/in/your-profile
