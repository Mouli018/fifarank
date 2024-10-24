# FIFA Ranking Prediction App

This web application predicts the FIFA rankings of football teams based on past match data. The project uses machine learning algorithms to predict future rankings based on input data such as team statistics, performance, and historical results.

## Table of Contents
- [Overview](#overview)
- [Dataset Overview](#datasetoverview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Output](#output)
- [Technologies](#technologies)
- [License](#license)

## Overview

The FIFA Ranking Prediction App allows users to input match data and predict the FIFA rankings of football teams. The app is built using machine learning models to analyze historical data and make predictions. This application is deployed using **Streamlit** and is available as a web-based tool.

## Dataset Overview
The dataset consists of historical FIFA ranking data, which includes over 17,000 records of national football teams. Key variables in this dataset include total points, previous points, rank, and the confederation to which each team belongs. One of the challenges we encountered was handling missing data and managing regional biases, particularly since teams from different confederations participate in varying numbers of international matches, affecting their ranking opportunities.


## Features

- Predict FIFA rankings for teams based on past performance
- Input data like team statistics, match results, and other relevant features
- Visualize data and predictions using interactive graphs
- User-friendly interface powered by Streamlit

## Installation

To run this project locally, follow these steps:
1.Python Version:
   Python 3.12.7

2.Clone the repository:
   #bash
   git clone https://github.com/Mouli018/FIFA-Ranking-Prediction-App.git

i)Change directory:
bash
cd FIFA-Ranking-Prediction-App

ii)Create a virtual environment (optional but recommended):
python -m venv env
source env/bin/activate  # For Linux/macOS
env\Scripts\activate 

iii)Install the required dependencies:
bash
pip install -r requirements.txt

## Usage
To run the app locally, execute the following command:
bash
streamlit run streamlit_app.py
This will start the Streamlit web app, which you can access locally in your browser at http://localhost:8501.
## Input
Input historical match data (e.g., teams, goals scored, match results) to predict FIFA rankings.
## Output
![image](https://github.com/user-attachments/assets/81b509b5-a145-48c1-89a3-cce26f947646)
![image](https://github.com/user-attachments/assets/0dcfefc6-ecf0-4eee-8741-c6dbdb294503)
![image](https://github.com/user-attachments/assets/1b127cce-b313-4275-b61f-c51e56492f3b)
![image](https://github.com/user-attachments/assets/a8767a44-4f05-4223-aed2-5a77639ce034)
![image](https://github.com/user-attachments/assets/e0b49693-7ac3-4f2c-8571-0d1ab2b8945c)
![image](https://github.com/user-attachments/assets/fbcc5762-459a-420a-9bbe-0034a3cc253e)
![image](https://github.com/user-attachments/assets/b152938c-d3ad-4b4c-b611-469a21e97080)

## Technologies
Programming Language: Python
Libraries:Streamlit, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
Deployment: Streamlit Cloud

##License
This project is licensed under the MIT License - see the LICENSE file for details.

