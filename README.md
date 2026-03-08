# Music-and-Mental-Health-Data-Analysis-using-Python

Project Overview

This project performs exploratory data analysis on the Music & Mental Health Survey dataset to investigate relationships between music listening habits and mental health indicators. Using Python and data processing libraries, the dataset is explored, cleaned, and analysed to understand patterns in music consumption and self-reported mental health conditions.

The objective of this project is to demonstrate practical data analysis skills including data exploration, preprocessing, statistical analysis, and correlation analysis using Python.

Dataset

The dataset used in this project is Music & Mental Health Survey Results, sourced from Kaggle.

Dataset link:
https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results

Dataset characteristics:
- 736 survey responses
- 33 attributes
- Contains both numerical and categorical variables

Key attributes include:
- Age of respondents
- Hours spent listening to music per day
- Favourite music genre
- Frequency of listening to different music genres

Mental health indicators:
- Anxiety
- Depression
- Insomnia
- OCD

Tools & Technologies:
- Python
- Jupyter Notebook
- Pandas
- NumPy

Data Processing & Analysis

The following steps were performed during the analysis:
1. Data Loading
   - Loaded the dataset into a Pandas DataFrame
   - Displayed the first and last five rows for inspection

2. Dataset Exploration
   - Checked dataset dimensions
   - Examined column data types
   - Identified numerical and categorical variables

3. Data Filtering
   - Removed unnecessary columns
   - Created a refined dataset containing relevant attributes

4. Numerical Analysis

   Using loops and Pandas functions:
   - Calculated sum and averages of numerical columns
   - Generated summary statistics
   - Examined distributions of mental health indicators

5. Text Processing
   - Iterated through categorical columns
   - Standardised text values by converting them to lowercase

6. Correlation Analysis

   A correlation table was generated to analyse relationships between:
   - Music listening time
   - Anxiety
   - Depression
   - Insomnia
   - OCD

Key Insights

- The average age of respondents is around 25 years, indicating a relatively young population.
- Participants listen to music for approximately 3–4 hours per day on average.
- Respondents reported moderate levels of anxiety and depression.
- Correlation analysis suggests a weak relationship between music listening time and mental health conditions.
- Stronger correlations appear between mental health conditions themselves, particularly anxiety and depression.

Data Quality
- Missing values represent a small proportion of the dataset
- No duplicate rows or columns were identified
- Overall dataset quality was considered suitable for analysis

Learning Outcome

This project demonstrates practical experience in:
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Working with real-world datasets
- Statistical summarisation
- Correlation analysis using Python

Future Improvements

Possible extensions of this project include:
- Data visualisation using Matplotlib or Seaborn
- Genre-based analysis of mental health indicators
- Predictive modelling using machine learning techniques
- Interactive dashboards using Tableau or Power BI
