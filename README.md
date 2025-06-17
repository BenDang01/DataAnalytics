# Benjamin Dang - Data Analytics Portfolio
## About
Hi, I'm Ben – I have a strong interest in uncovering insights and solving problems through data. This is a repository to showcase skills and share my projects.

My Resume in [pdf](https://drive.google.com/file/d/17PnKPalYmj1tICfdNd8Dltvei6TQpEN9/view?usp=sharing).



## Table of Contents
- [About](#about)
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

**Goal:** To explore and predict song popularity using Spotify dataset.

**Description:** This project explores whether the popularity of Taylor Swift's songs can be predicted using audio features from the Spotify dataset, such as loudness, energy, and acousticness. After cleaning and preprocessing the data, various regression models - including Linear Regression, Random Forest, SVR, and XGBoost—were implemented and evaluated using metrics like R² and mean squared error. Visualizations were created using Plotly, Matplotlib, and Seaborn to support analysis and model interpretation.

**Skills:** Data cleaning, exploratory data analysis (EDA), feature engineering, correlation analysis, regression modeling, model evaluation, data visualisation.

**Data Package:** Python, Pandas, Numpy, Scikit-learn, XGBoost, Plotly, Matplotlib, Seaborn.

**Results:** The analysis found that energetic and loud songs tend to be less acoustic, and energy contributes positively to a song's valence. Track number on an album has minimal impact on other features. Among the models, XGBoost performed best, while Support Vector Regression showed the weakest results.



### Analysing Social Media Behavior Among Students
**Code:** [`Analysing Social Media Behavior Among Students.ipynb`](http://github.com/BenDang01/Project/blob/main/Social%20Media%20Behavior%20Among%20Students.ipynb)

**Goal:** To explore the relationship between social media usage and academic performance.

**Description:** This project explores how students' social media usage patterns relate to their academic performance, mental health, and relationship status. Using survey data, the analysis investigates key trends and correlations to understand the broader impact of digital behavior on student wellbeing.

**Skills:** Data cleaning, exploratory data analysis (EDA), correlation analysis, hypothesis testing, data visualisation, statistical interpretation.

**Data Package:** Python, Pandas, Numpy, SciPy, Seaborn, Matplotlib, Plotly.

**Results:** The analysis revealed meaningful associations between heavy social media use and lower academic performance, as well as increased reports of stress and anxiety. Relationship status showed some patterns of usage variation, though with less pronounced effects.
