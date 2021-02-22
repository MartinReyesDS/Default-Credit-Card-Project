# Recommendations for Microsoft's New Movie Studio

<img src="images/CC-Default1.png" style="width:550px;height:250px"/>

**Author**: Martin Reyes

## Table of contents
1. [Project Description](#introduction)
2. [Project Overview](#paragraph1)
3. [Business Problem](#paragraph2)
4. [Data](#paragraph3)
5. [Methods](#paragraph4)
7. [Results](#paragraph6)
    1. [Next Steps](#paragraph6)

<hr style="border:1px solid gray"> </hr>

## Project Overview

In this project, a dataset with credit card client information is analyzed to build insights. These insights include which features are most important or relevant with whether or not the customer will default on their next payment and how the features compare with each other in terms of default rate. After the data is analyzed, machine learning models are trained, tuned, and evaluated in order to best predict if a customer will default.

<hr style="border:1px solid gray"> </hr>

## Business Problem

A credit card company in Taiwan wants to know which feature is the biggest predictor in whether a customer will default their next payment. The company also wants to develop a machine learning algorithm in order to predict defaulters. They have emphasized that they want the model to predict as many defaulters. Although the costs of mistakenly predicting a non-defaulter as a defaulter is not high, the company wants the algorithm to at least predict half of the non-defaulters correctly.

<hr style="border:1px solid gray"> </hr>

## Data

[Data](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#) is from the UCI Machine Learning Repository can be extracted to customer information as well as the target feature of this project, whether or not the customer defaulted on their credit card. This data can be found in the "data" folder along with the cleaned version of this dataset.

<hr style="border:1px solid gray"> </hr>

## Methods

This project uses EDA to gain insights on the customers and machine learning algorithms to predict whether or not the customer will fail to make the next payment on their credit card. In this project, the main variable of focus (target) is the binary variable, "DEFAULT", which tells us whether or not the customer defaulted. Most of the other variables (features) will be used to gain insight on the customers and create machine learning models to predict the target variable.


<hr style="border:1px solid gray"> </hr>

## Results

- Insights:
    - Pay history is the most important feature in predicting defaulters, especially recent payment history.
- Optimal Model: XGBoost
    - .88 recall score
    
### Next Steps

- Use advanced ML and Deep Learning techniques, like a neural network
- Use advanced dimensionality reduction like PCA and LDA for many of the algorithms
- Explore the data more for insights
- Gather more data

<hr style="border:1px solid gray"> </hr>

## For More Information

Please review the full analysis and modeling in [the Jupyter Notebook](./EDA-and-Modeling.ipynb) or the [presentation](./Movie_Recommendations_Presentation.pdf).

For any additional questions, please contact **Martin Reyes** at **martinreyes.eng@gmail.com**

## Repository Structure

```
├── data
├── images
├── CRISP-DM-and-Planning.ipynb
├── EDA-and-Modeling.ipynb
├── Obtain-and-Clean-Data.ipynb
├── Credit-Card-Defaulters-Presentation.pdf
├── README.md
```