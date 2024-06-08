# Bike Buyers Analysis Project

This project analyzes data from the [Bike Buyers dataset](https://www.kaggle.com/datasets/heeraldedhia/bike-buyers) available on Kaggle. The dataset provides various demographic and purchasing information about individuals and whether they have purchased a bike.

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)

## Overview
The goal of this project is to analyze the dataset to identify patterns and insights regarding bike purchases based on different demographics and other factors. We focus on understanding the relationship between income, gender, distance to work, age group, and age with the likelihood of purchasing a bike.

## Data
The dataset contains the following key columns:
- `Purchased Bike`: Whether the individual has purchased a bike (Yes/No).
- `Gender`: The gender of the individual (Male/Female).
- `Income`: The annual income of the individual.
- `Distance to Work`: The distance the individual travels to work.
- `Age`: The age of the individual.
- `Age Group`: The age group the individual belongs to (Adolescent, Middle Aged, Old).

## Analysis
The analysis is divided into several parts:
1. **Average Income by Gender and Purchase Decision**
2. **Count of Bike Purchases by Distance to Work**
3. **Count of Bike Purchases by Age Group**
4. **Count of Bike Purchases by Age**

### Average Income by Gender and Purchase Decision

| Gender | No Purchase | Purchased | Overall Average |
|--------|-------------|-----------|-----------------|
| Female | $53,440     | $55,774   | $54,581         |
| Male   | $56,208     | $60,124   | $58,063         |
| Total  | $54,875     | $57,963   | $56,360         |

### Count of Bike Purchases by Distance to Work

| Distance to Work | No Purchase | Purchased | Total |
|------------------|-------------|-----------|-------|
| 0-1 Miles        | 166         | 200       | 366   |
| 1-2 Miles        | 92          | 77        | 169   |
| 2-5 Miles        | 67          | 95        | 162   |
| 5-10 Miles       | 116         | 76        | 192   |
| More than 10 Miles | 78        | 33        | 111   |
| Total            | 519         | 481       | 1000  |

### Count of Bike Purchases by Age Group

| Age Group  | No Purchase | Purchased | Total |
|------------|-------------|-----------|-------|
| Adolescent | 71          | 39        | 110   |
| Middle Aged| 318         | 383       | 701   |
| Old        | 130         | 59        | 189   |
| Total      | 519         | 481       | 1000  |

### Count of Bike Purchases by Age

| Age | No Purchase | Purchased | Total |
|-----|-------------|-----------|-------|
| 25  | 2           | 4         | 6     |
| 26  | 8           | 8         | 16    |
| 27  | 15          | 8         | 23    |
| 28  | 12          | 10        | 22    |
| 29  | 11          | 5         | 16    |
| 30  | 23          | 4         | 27    |
| 31  | 17          | 8         | 25    |
| ... | ...         | ...       | ...   |
| 89  | 1           | 0         | 1     |
| Total | 519       | 481       | 1000  |

## Results
- **Income:** Males have a higher average income compared to females. Bike buyers generally have a higher income.
- **Distance to Work:** The majority of bike buyers live within 0-1 miles from work. Bike purchases decrease as the distance to work increases.
- **Age Group:** Middle-aged individuals are the most likely to purchase bikes.
- **Age:** Bike purchases vary significantly with age, with a noticeable peak among individuals in their late 30s.

## Conclusion
The analysis reveals that higher income, shorter distance to work, and being middle-aged are associated with a higher likelihood of purchasing a bike. Gender also plays a role, with males having a slightly higher tendency to buy bikes.

## How to Use
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/heeraldedhia/bike-buyers).
2. Load the dataset into your preferred analysis tool (e.g., Excel, Python, R).
3. Use the provided analysis framework to replicate and extend the analysis.

For any questions or contributions, please feel free to create an issue or submit a pull request on the project's GitHub repository.
