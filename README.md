# Marketing Campaign Analysis

### Level: Beginner

## Project Overview

This project analyzes a social media ad campaign dataset to identify key factors influencing ad conversions. By exploring aspects such as age, gender, and interests, the project aims to uncover behavioral patterns using **cluster analysis**. The insights gained from this analysis can help optimize future marketing strategies for better conversion rates and return on ad spend (ROAS).

---

## Table of Contents

1. [Project Aim](#project-aim)
2. [Dataset](#dataset)
3. [Tools Used](#tools-used)
4. [Installation](#installation)
5. [Key Steps](#key-steps)
6. [Results](#results)
7. [Conclusion](#conclusion)

---

## Project Aim

The main goal of this project is to analyze factors affecting ad conversions and identify patterns in customer behavior. Specifically, the project focuses on:

- Understanding how variables like age, gender, interests, and campaign spending impact conversion rates.
- Performing **cluster analysis** to group users with similar behaviors.
- Gaining actionable insights to optimize marketing strategies and improve Return on Investment (ROI).

---

## Dataset

The dataset used for this analysis is a social media ad campaign dataset that contains information such as:

- Age
- Gender
- Campaign details (xyz_campaign_id, fb_campaign_id)
- Impressions, clicks, conversions, and ad spend
- Total and approved conversions

This dataset is used to examine the effectiveness of various ad campaigns and user engagement.

---

## Tools Used

- **Python**: for data manipulation and analysis
- **Jupyter Notebook**: for executing code and generating visualizations
- **Pandas**: for data cleaning and exploration
- **Matplotlib/Seaborn**: for data visualizations
- **Scikit-learn**: for cluster analysis and model building
- **Scipy**: for statistical analysis

---

## Installation

## Set up the Environment

### Install the required dependencies by running:

```bash
pip install -r requirements.txt

### Clone the Repository

```bash
git clone https://github.com/your-username/Marketing-Campaign-Analysis.git
```

## Requirements
- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Scipy

## Key Steps

### Data Exploration:
We begin by loading the dataset and exploring the data with summary statistics, missing values analysis, and visualizations of key variables such as age, gender, impressions, and clicks.

### Data Preprocessing:
- Cleaning the dataset by replacing null values and normalizing numerical features.
- Creating new features such as **CTR** (Click-Through Rate), **CPC** (Cost Per Click), and **ROAS** (Return on Ad Spend).

### Exploratory Data Analysis (EDA):
- Boxplots and correlation heatmaps are generated to understand relationships between ad spending, clicks, and conversions.
- Statistical tests (e.g., Wilcoxon test) are performed to analyze the impact of gender on ROAS.

### Clustering:
We apply clustering techniques to group users by similar interests, conversion behavior, and spending habits.

### Visualization:
Visualizations such as scatter plots, histograms, and boxplots are used to highlight key findings and trends.

## Results
- Identified which age groups and genders had the highest ROAS.
- Found that certain interest groups had significantly higher conversion rates and ad engagement.
- Statistical tests revealed differences in ad performance by gender and interest.

## Conclusion
This project demonstrates how data analysis and clustering can be applied to real-world marketing datasets to improve ad campaign efficiency. By understanding customer behavior, businesses can refine their strategies, increase conversion rates, and maximize ROAS.

## Credits

This project was initially created in R by [Chris Bow](https://www.kaggle.com/code/chrisbow/an-introduction-to-facebook-ad-analysis-using-r) and has been converted to Python by [Sargun Singh]. Special thanks to the original creator for their contributions.

## Dataset

The dataset used for this project is publicly available on Kaggle. You can access it here: [Kaggle Dataset Link](https://www.kaggle.com/code/chrisbow/an-introduction-to-facebook-ad-analysis-using-r/input)


