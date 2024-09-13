# Project Overview

This project aims to predict the outcomes of each football match in the English Premier League (EPL) for the 2023-24 season using data from the 2022-23 season. The predicted results will be compared with actual match outcomes to assess the accuracy and precision of the predictions.

**Project Objectives**

* Data Extraction: Use libraries such as requests, BeautifulSoup, and pandas to scrape relevant match data from online sources.
* Data Cleaning/Preparing: Clean and prepare the extracted data for machine learning analysis using pandas.
* Predictive Modeling: Using machine learning algorithms from the scikit-learn library to forecast match outcomes.
* Error measurement and improvement: Evaluate the model performance by comparing with test data set.

**File Overview**
* `data_scraping.ipynb` - scrapes 2022-23 & 2023-24 seasons match data from [FBref](https://fbref.com/en/)
* `prediction.ipynb` - train machine learng model using 2022-23 season data and predicts 2023-24 match result (Win, Draw, or Lose) and compared with the actual results to find the accuracy of model.

**Packages/Libraries**
* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * requests
    * BeautifulSoup
    * scikit-learn