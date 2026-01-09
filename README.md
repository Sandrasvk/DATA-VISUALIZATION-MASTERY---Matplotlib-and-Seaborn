# Data Visualization Lab: Matplotlib & Seaborn 📊

This repository is a comprehensive portfolio of my Jupyter Notebook exercises and assignments. It documents the technical implementation of statistical data visualization, ranging from basic coordinate plotting to advanced multi-variate grids and professional scaling.

## 🚀 Technical Features & Plot Gallery

### 1. Distribution Analysis
I have implemented several methods to visualize data density and frequency:
* *histplot:* The modern Seaborn command for creating Histograms with optional KDE overlays.
* *jointplot:* Analyzing the relationship between two variables with marginal distributions on the sides.
* *displot:* A figure-level interface for drawing distribution plots onto a FacetGrid.
* *KDE & Rug Plots:* Adding smoothed density estimates and individual data points for granular analysis.

### 2. Categorical & Comparison Plots
Techniques used to compare different groups within a dataset:
* *stripplot:* Visualizing every individual data point across categories to see distribution density.
* *boxplots & violin plots:* Identifying outliers and understanding the "inner quartiles" and density of data.
* *pairplot:* Creating a matrix of plots to visualize every relationship in a dataset instantly.

### 3. Advanced Grid Systems
Mastery of multi-plot layouts for high-dimensional data:
* *FacetGrids:* Manually mapping plot types to a grid based on categorical columns.
* *JointGrids:* Full control over the joint and marginal axes of a bivariate plot.
* *Matrix Plots:* Using *Heatmaps* for correlation and *Clustermaps* for hierarchical grouping.

### 4. Regression & Trends
* *lmplot & regplot:* Mapping linear regression lines to identify trends and confidence intervals.

## 🎨 Professional Display Contexts
A key focus of this lab was scaling visualizations for different professional environments using sns.set_context():
* *Poster:* Extra-bold lines and large text for physical display boards.
* *Talk:* Optimized for presentation slides and projector screens.
* *Notebook:* Standard scaling for interactive coding and analysis.
* *Paper:* High-detail, small-font scaling for academic publications.

## 🛠 Tech Stack
* *Language:* Python
* *Libraries:* Matplotlib, Seaborn, Pandas, NumPy
* *Environment:* Jupyter Notebook

## ⚙️ Installation
To run these notebooks locally:
```bash
pip install matplotlib seaborn pandas numpy
