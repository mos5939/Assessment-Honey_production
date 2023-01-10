# What is happening to the bees?
A study of the trends in the production of honey across the United States of America between 1995 and 2021

## Overview 
A dataset on honey production using data sourced from the National Agricultural Statistics Service, USDA. 
This dataset was chosen due to its biological relevance to the current concerns regarding the international decline of insects with >40% of species being threatened with extinction (Sanchez-Bayo and Wyckhuys, 2018). Over the last 60 years the number of honeybee colonies in the USA has shrunk by 3.5 million from a peak of 60 million in 1947 (Sanchez-Bayo and Wyckbuys, 2018). This project will study interactions between different factors measuring success of honey production with the aim of understanding which areas may be contributing to the decay of honey production.

This project uses statistical analysis and graphical representation to display and investigate trends and patterns in honey production and coloniy success.

## Table of Contents
1.	Importing modules and data
2.	Investigating the dataset
3.	Trends in production amount
4.	Ranking states by production 
5.	Multi panel plot 
6.	Quantifying production ranking changes
7.	Relationship between amount and value of honey
8.	Trends in regional differences
9.	Influence of colony numbers

## Prerequsiites for project 
THe functioning of this project requires the installation and running of project:
•	Python3
•	Jupyter
•	The following python packages:
o	pandas
o	seaborn 
o	matplotlib.pyplot
o	numpy
o	scipy.stats (rankdata)
o	scipy.stats (spearmanr)

If you are new to jupyter you can download jupyterlab through the Anaconda software which can be downloaded from the [Anaconda website](https://www.anaconda.com/products/distribution)

## Sample dataset
This project was written for analysis of data on Honey Production in America from 1995-2021. This dataset was compiled by Mohit Poudel of the Agriculture and Forestry University in Nepal with the goal of providing insights into honey production, demand, and supply across the United States of America.

This dataset can be found within the repositary of this file as "US_honey_dataset.csv" or can alteranively be found at [link](https://www.kaggle.com/datasets/mohitpoudel/us-honey-production-19952021/download?datasetVersionNumber=1)

## Methods

