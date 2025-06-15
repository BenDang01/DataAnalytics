# Benjamin Dang - Data Analytics Portfolio
## About
Hi, I'm Ben – I have a strong interest in uncovering insights and solving problems through data. This is a repository to showcase skills and share my projects.

My Resume in [pdf](https://drive.google.com/file/d/17PnKPalYmj1tICfdNd8Dltvei6TQpEN9/view?usp=drive_link).



## Table of Contents
- [About]()
- [Portfolio Projects]()
  - Python
    - [Predicting Song Popularity from Spotify Dataset]()
    - [Social Media Behaviors Among Students]()  
  - SQL
  - Excel / Google Sheets
  - Tableau
  - Power BI
  



## Portfolio Projects
In this section I will list data analytics projects briefly and describe the data stack used to solve cases.

### Predicting Song Popularity from Spotify Dataset
**Code:** [`Predicting Song Popularity from Spotify Dataset.ipynb`](https://github.com/BenDang01/Project/blob/bd23344b7b4a21ef3c04851fa907b253b8063bce/Predicting%20Song%20Popularity%20from%20Spotify%20Dataset.ipynb)

**Goal:** To explore and predict song popularity using  Spotify dataset.

**Description:** This project explores whether the popularity of Taylor Swift's songs can be predicted using audio features from the Spotify dataset, such as loudness, energy, and acousticness. After cleaning and preprocessing the data, various regression models - including Linear Regression, Random Forest, SVR, and XGBoost—were implemented and evaluated using metrics like R² and mean squared error. Visualizations were created using Plotly, Matplotlib, and Seaborn to support analysis and model interpretation.

**Skills:** Data cleaning, exploratory data analysis (EDA), feature engineering, correlation analysis, regression modeling, model evaluation, data visualization.

**Data Package:** Python, Pandas, Numpy, Scikit-learn, XGBoost, Plotly, Matplotlib, Seaborn.

**Results:** The analysis found that energetic and loud songs tend to be less acoustic, and energy contributes positively to a song's valence. Track number on an album has minimal impact on other features. Among the models, XGBoost performed best, while Support Vector Regression showed the weakest results.
