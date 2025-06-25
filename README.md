# rainfall-prediction
 Rainfall Prediction Project
This project aims to analyze historical rainfall data in India and build predictive insights using Python. The dataset is preprocessed and visualized using pandas, matplotlib, and seaborn.

 Dataset Overview
Source: [IMD Rainfall Dataset]

Shape: ~36,000 records × 37 columns

Time Span: Yearly records for Indian states and union territories from 1901 to 2015

Target Variable: ANNUAL rainfall amount (in mm)

🛠 Tools and Libraries Used

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

 Project Highlights
Data Cleaning:

Checked for null values

Ensured numerical consistency

Exploratory Data Analysis (EDA):

Rainfall trends over years

State-wise rainfall comparison

Boxplots, line plots, and bar charts

Statistical Summary:

Used describe(), info(), and correlation matrices to understand data

Focused visual insights into seasonal patterns (JAN, FEB, ..., DEC) and their correlation with ANNUAL rainfall

 Visualizations
Line Plot: Annual rainfall trend (India overall and state-wise)

Boxplot: Monthly distribution comparisons

Heatmap: Correlation matrix between monthly rainfall and annual total

Bar Charts: Total rainfall per state

 Folder Structure

rainfall-prediction/
│
├── rainfall-prediction-project.ipynb
├── rainfall_data.csv               # (You may need to include this separately if not already present)
└── README.md


 Insights
Rainfall patterns show significant seasonal and geographic variation

Certain states show consistent decline or rise in rainfall over decades

The monsoon months (June–September) contribute the most to annual rainfall
