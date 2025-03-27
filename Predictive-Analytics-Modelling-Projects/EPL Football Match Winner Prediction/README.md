# English Premier League (EPL) Match Winner Prediction

## Project Overview

Welcome to my English Premier League (EPL) match winner prediction project. In this portfolio project, we aim to predict the outcomes of football matches in the English Premier League using a combination of web scraping, data cleaning, and machine learning.

## Project Steps

1. **Data Scraping**: We begin by scraping match data from the web using popular libraries like `requests`, `BeautifulSoup`, and `pandas`. The scraping process is detailed in the `scraping.ipynb` Jupyter notebook. The datset contains data from 2023 to 2021 seasons.

2. **Data Preparation**: Once we've gathered the data, we perform data cleaning and preprocessing to get it ready for machine learning. This step ensures that the data is in a format that can be used effectively for predictive modeling.

3. **Predictive Modeling**: Using the `scikit-learn` library, we build a machine learning model that predicts the winner of each EPL match based on historical data and match attributes.

4. **Error Measurement and Improvement**: We evaluate the performance of our model and work on improving its accuracy. This iterative process involves refining the model and fine-tuning our approach to enhance prediction quality.

## Code

You can access the code for this project in the following files:

- `scrapping.ipynb`: This Jupyter notebook contains the code for data scraping.
- `predictions.ipynb`: In this Jupyter notebook, you will find the code for making match winner predictions.

## Local Setup

### Installation

To follow this project, please ensure you have the following installed locally:

- [JupyterLab](https://jupyter.org/)
- Python 3.8+
- Python packages:
  - `pandas`
  - `requests`
  - `BeautifulSoup`
  - `scikit-learn`

### Data

In the first part of this project (`scrapping.ipynb`), we scrape data from [FBref](https://fbref.com/en/comps/9/Premier-League-Stats) to gather the necessary information for our predictions. If you'd like to skip the scraping step and work only on the predictive modeling part, you can download the pre-scraped dataset as `PLmatches.csv`.

## Project Goals

By the end of this project, we aim to create a predictive model that can accurately forecast match winners in the EPL. The skills demonstrated in this project include web scraping, data cleaning, feature engineering, and machine learning.
