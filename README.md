# Predicting-Term-Deposit-Subscriptions

This project aims to predict whether a client will subscribe to a term deposit based on features derived from marketing campaign data. It includes model training, evaluation, feature importance analysis, and actionable insights for the marketing team.

## Dataset Description
The dataset is related to direct marketing campaigns of a banking institution. The goal is to predict if a client will subscribe (yes) or not (no) to a term deposit (y).

Features :

age (numeric)
job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student","blue-collar","self-employed","retired","technician","services") 
marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
education (categorical: "unknown","secondary","primary","tertiary")
default: has credit in default? (binary: "yes","no")
balance: average yearly balance, in euros (numeric) 
housing: has housing loan? (binary: "yes","no")
loan: has personal loan? (binary: "yes","no")
contact: contact communication type (categorical: "unknown","telephone","cellular") 
day: last contact day of the month (numeric)
month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
duration: last contact duration, in seconds (numeric)
campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client (numeric)
poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

Target Variable : y – binary classification (yes / no)

Available datasets:

bank-additional-full.csv: Full dataset with 41,188 examples and 20 inputs.
bank-additional.csv: 10% sample of the full dataset.
bank-full.csv: Older version with fewer features.
bank.csv: 10% sample of the older version.

Link: https://docs.google.com/spreadsheets/d/1g218zOl2tUeZ9jOZwgZ696qzSWwV-Une/edit?usp=sharing&ouid=102831201071985235715&rtpof=true&sd=true

## Report

Link: https://docs.google.com/document/d/1bVqOiQjfCrcK0UhEdDW5NXzqABpzjIJA0t_4mIhEDEE/edit?usp=sharing


## Requirements

To run this project locally or in Colab, ensure you have the following libraries 

# How to Run

## Getting Started:

* Clone this repository: `git clone https://github.com/yourusername/Term_Deposit_Prediction.git `

* cd `Term_Deposit_Prediction`

* create new env with python 3 and activate it `(virtualenv venv & venv\scripts\activate)`.

* Install the required packages using pip install -r requirements.txt


### Questions?

If you have any questions about the implementation, want to improve the model, or need help deploying it, feel free to reach out!