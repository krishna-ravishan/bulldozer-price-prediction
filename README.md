# Bulldozer Price Prediction

## 🚜 Predicting the sale price of Bulldozers using Machine Learning

This repository contains the code and resources for predicting the sale price of bulldozers using machine learning. The goal is to develop a model that can accurately forecast the future sale price of a bulldozer based on its characteristics and historical sales data.

## Table of Contents
1. [Problem Definition](#1-problem-definition)
2. [Data](#2-data)
3. [Evaluation](#3-evaluation)
4. [Features](#4-features)

## 1. Problem Definition

How well can we predict the future sale price of a bulldozer given its characteristics and previous examples of how much similar bulldozers have been sold for?

## 2. Data

The data used in this project is from the Kaggle Bluebook for Bulldozers competition. It is split into three parts:

- **Train.csv:** The training set, containing data through the end of 2011.
- **Valid.csv:** The validation set, containing data from January 1, 2012, to April 30, 2012. Predictions on this set are used for the public leaderboard.
- **Test.csv:** The test set, released in the last week of the competition, containing data from May 1, 2012, to November 2012. Predictions on this set determine the final competition rank.

## 3. Evaluation

The evaluation metric for this competition is the `RMSLE (root mean squared log error)` between the actual and predicted auction prices. The goal is to minimize this error in our machine learning model.

For more details on the evaluation, refer to the [Kaggle competition overview](https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview).

## 4. Features

The key fields in `train.csv` include:

- `SalesID:` the unique identifier of the sale
- `MachineID:` the unique identifier of a machine. A machine can be sold multiple times
- `saleprice:` what the machine sold for at auction (only provided in train.csv)
- `saledate:` the date of the sale

For a detailed data dictionary, refer to [this link](https://docs.google.com/spreadsheets/d/16jXqzqUlLUxjwWLY12LDwDyWFQqSk_lqR-0ZarQQcuM/edit?usp=sharing).
