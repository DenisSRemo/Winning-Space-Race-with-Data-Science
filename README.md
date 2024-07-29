# Winning the Space Race with Data Science

## Overview

Welcome to the repository for the "Winning the Space Race with Data Science" project. This project showcases a comprehensive analysis of SpaceX Falcon 9 first-stage landings, aiming to predict the success of these landings using machine learning models. The project demonstrates various skills in data collection, preprocessing, exploratory data analysis, visualization, predictive modeling, and developing interactive dashboards.

## Project Structure

### Executive Summary
The project begins with exploratory data analysis (EDA) to understand the dataset's structure, features, and distributions. Several machine learning algorithms, including Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K Nearest Neighbors (KNN), were employed. Based on training accuracy, the decision tree model was identified as the preferred choice.

### Data Collection
Data was collected using multiple methods:
- **API Requests**: Data was obtained from SpaceX's API and other sources.
- **Web Scraping**: Relevant data was scraped from various websites, including Wikipedia.
- **Data Wrangling**: The collected data was cleaned, transformed, and filtered to ensure quality and relevance.

### Data Analysis and Visualization
EDA was performed using:
- **Visualization Tools**: Pandas, Matplotlib, Seaborn, and Plotly were used to create various visualizations, such as histograms, scatter plots, and heatmaps.
- **Interactive Maps**: Folium was used to build interactive maps displaying launch sites and other key features.

### Predictive Modeling
The following steps were taken:
- **Feature Engineering**: Informative features were extracted and transformed.
- **Model Selection**: Several classification models were evaluated using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
- **Hyperparameter Tuning**: Techniques like GridSearchCV were used to optimize model parameters.
- **Ensemble Methods**: Methods like bagging and boosting were explored to enhance model predictions.

### Dashboard Development
An interactive dashboard was created using Plotly Dash, featuring:
- **Dropdown Menus**: To select specific launch sites.
- **Pie Charts**: To display successful launch counts.
- **Scatter Charts**: Showing the relationship between payload mass and launch success.
- **Sliders**: For filtering data based on payload mass.

## Key Findings
- CCAFS SLC 40 had the most launches, but VAFB SLC 4E had the highest success rate.
- Launches with lighter payloads had a higher failure rate than heavier ones.
- The success rate of launches has generally improved over the years, with some fluctuations.

## Repository Contents
- **Data Collection**: Scripts for API requests and web scraping.
- **Data Preprocessing**: Code for data cleaning and transformation.
- **EDA and Visualizations**: Notebooks and scripts for exploratory data analysis and visualizations.
- **Predictive Modeling**: Notebooks detailing the model selection, tuning, and evaluation processes.
- **Dashboard**: Code for the interactive dashboard developed using Plotly Dash.

## Installation
To run this project locally, follow these steps:
1. Clone the repository: `git clone https://github.com/DenisSRemo/SpaceRaceDataScience.git`
2. Navigate to the project directory: `cd SpaceRaceDataScience`
3. Install the required packages: `pip install -r requirements.txt`
4. Run the Jupyter notebooks for data analysis and model training.
5. Start the dashboard: `python dashboard.py`


