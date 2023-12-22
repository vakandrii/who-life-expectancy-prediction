# Life Expectancy Prediction

This project aims to predict life expectancy using machine learning algorithms, specifically Random Forest, Ridge 
regression and AdaBoost. The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who).

## Dataset Overview
Although there have been lot of studies undertaken in the past on factors affecting life expectancy considering
demographic variables, income composition and mortality rates. It was found that affect of immunization and human
development index was not taken into account in the past. Also, some of the past research was done considering multiple
linear regression based on data set of one year for all the countries.

The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status 
as well as many other related factors for all countries The data-sets are made available to public for the purpose of 
health data analysis. The data-set related to life expectancy, health factors for 193 countries has been collected from 
the same WHO data repository website and its corresponding economic data was collected from United Nation website. 

## Project Structure
The project is organized as follows:
- `data.csv`: Dataset from Kaggle in csv format
- `README.md`: This file providing an overview of the project (You are reading it right now!).
- `titanic.ipynb`: Jupyter Notebook containing the code for data preprocessing, EDA, model training, and evaluation.
- `requirements.txt`: List of Python packages required to run the notebook.

## Setup and Usage
1. **Setup**
   - Clone this repository to your local machine.
      ```bash
      git clone https://github.com/your_username/your_repository.git
      ```
   - Navigate to the project directory.
   - Install the required Python packages using pip:
     ```bash
     pip install -r requirements.txt
     ```
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `life_exp.ipynb` in your browser.

## Acknowledgment
This project is inspired by the Kaggle community and the dataset provided by Kumar Rajarshi. Thank you for making this learning experience possible!