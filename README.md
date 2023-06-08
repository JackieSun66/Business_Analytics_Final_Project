# Business_Analytics_Final_Project
NYU BUSF-SHU 210: Business Analytics Final Project

This project aims to develop an uplift model that predicts the incremental impact or uplift of a treatment on individuals, allowing for targeted interventions and improved decision-making. The uplift model helps identify individuals who are most likely to respond positively to a treatment, enabling more effective and efficient resource allocation. 

# Problem Statement

In this project, we aim to develop an uplift model using advanced machine learning techniques to predict the incremental response to a treatment for clients in a database. The model will utilize the clients' historical purchasing behavior, including information such as the amount of time since their last purchase, the total amount purchased, and their engagement during promotional activities. By identifying clients who are more likely to respond positively to a treatment, the model enables targeted interventions and maximizes the overall impact.

# Approach and Methodology

1. Class Declaration:

Control Non-Responders(CN)

Customers that don't make a purchase without an offer (value = 0)

Control Responders(CR)

Customers that make a purchase without an offer (value = 1)

Treatment Non-Responders(TN)

Customer that don't make a purchase and receive an offer (value = 2)

Treatment Responders(TR)

Customers that make a purchase and receive an offer (value = 3): 

2. Train the uplift model: 

Lai's Generalized Weighted Uplift (LGWUM) is a specific approach or methodology used within the field of uplift modeling to calculate the uplift scores. It it involves applying a weighting scheme to the observed outcomes (response or conversion) of the treated and control groups. The weighting is based on the estimated propensity scores, which represent the probability of an individual being in the treatment group given their characteristics. By incorporating weights into the uplift calculation, Lai's Generalized Weighted Uplift aims to account for potential biases or confounding factors that could impact the estimation of treatment effects. The weighted estimators help to adjust for imbalances in the data and improve the accuracy of the uplift scores.

3. Evaluate the model: 

The uplift score represents the predicted incremental impact or uplift that a particular treatment or intervention would have on an individual. It is a numerical value assigned to each individual in a dataset, indicating their expected response to the treatment compared to not receiving the treatment.

The uplift score is derived from an uplift model, which is trained using historical data that includes information about individuals, their characteristics, and their responses to treatment. The uplift model analyzes the data to estimate the individual treatment effects and predict the likelihood of a positive response due to the treatment.


## Author: Jackie Sun
