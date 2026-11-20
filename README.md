# Campus Walk Data: Machine Learning Mini Project

A machien learning with python mini project that explores how the campus environment relates to how people felt on campus walks  
It uses data cleaning, corrilation analisis and K-Means clustering

## Contents

| `[your_notebook_name].ipynb` | Main Colab notebook with all code and exsplanations |  
| `CampusWalkDataset_TemplateIDs.csv` | Campus walk survey data |  
| `README.md` | This file |  

## What the notebook does  
- **Loads** the campus walk dataset with pandas
- **Cleans** the data by removing empty rows and columns, filling gaps with 0, and remove unneeded columns and rows
- **Encodes** text columns as numbers and converts temperature, insect count and bird count to ints
- **Scales** the data to be comparable for clustering
- **Analysis correlations** with a heatmap and scatter plots of temperature and weather by location
- **Clusters** the walks into three groups with K-Means clusters and compares them with wellbeing, stress / ease

## Libraries used  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Created By
Seth Butler
