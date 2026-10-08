# 🎮 Video Game Sales Analysis

## 📌 Project Overview

This project analyzes video game sales data using Python to identify patterns and trends in genres, platforms, publishers, regions, and global sales.

## 📊 Dataset

**Dataset:** Video Game Sales Dataset  
**Source:** Kaggle

The dataset contains information about:
- Game Name
- Platform
- Year
- Genre
- Publisher
- Regional Sales
- Global Sales

## 🎯 Project Objectives

- Analyze video game sales by genre
- Identify top-selling platforms
- Analyze yearly sales trends
- Compare regional sales
- Identify best-selling video games
- Analyze top publishers
- Compare genre-wise regional sales

## 🧹 Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Outliers

Missing values in the `Year` and `Publisher` columns were handled. Duplicate records were checked and removed if present. The `Year` column was converted to integer format.

Outliers in the sales columns were identified using box plots. Extreme sales values were retained because they represent actual high-selling games.

## 📈 Data Visualizations

The project includes the following visualizations:

1. Global Sales by Genre
2. Top 10 Platforms by Global Sales
3. Global Video Game Sales by Year
4. Regional Distribution of Video Game Sales
5. Top 10 Best-Selling Video Games
6. Top 10 Publishers by Global Sales
7. Genre-wise Regional Sales

## 🔍 Key Findings

- Action is the highest-selling video game genre.
- PS2 has the highest global sales among the platforms analyzed.
- Global video game sales reached their highest level around 2008–2009.
- North America contributes the largest share of regional sales.
- Wii Sports is the best-selling individual game in the dataset.
- Major publishers account for a significant share of global video game sales.
- Sales patterns vary across different genres and regions.

## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 💻 Implementation

The complete Python implementation is provided in the Jupyter Notebook.

The notebook includes:

- Dataset loading
- Data exploration
- Data cleaning
- Missing value handling
- Duplicate checking
- Data type conversion
- Outlier detection
- Data visualization
- Analysis and insights

### Python Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## 📁 Project Files

- `Video_Game_Sales_Analysis.ipynb` — Complete Python data analysis notebook containing the code, visualizations, outputs, and analysis.

## 📌 Conclusion

The analysis of the Video Game Sales dataset helped identify important patterns in video game sales.

The project provides insights into popular genres, platforms, best-selling games, publishers, regional sales, and yearly sales trends.

Data cleaning and visualization helped transform the raw dataset into meaningful information about video game sales.

## 👩‍💻 Author

**Pankti Mevada**
