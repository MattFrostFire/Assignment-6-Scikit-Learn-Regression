# Assignment-6-Scikit-Learn-Regression
Project Overview-- Purpose: This project utilizes machine learning regression to predict the progression of diabetes in patients. 
Context: Diabetes is a complex condition involving glucose regulation, and modern research uses machine learning to detect and prevent disease progression.
Project Overview: Diabetes Progression Regression
Purpose:
The purpose of this project is to use machine learning to predict the progression of diabetes using the Scikit-Learn diabetes dataset. By building and comparing three different regression models, we aim to identify which algorithm most accurately captures the relationship between physiological variables and the disease's progression.



Class Design & Implementation: 

Class: DiabetesModeler — Acts as the central hub for the machine learning workflow.

Attributes:

self.models: A dictionary storing the three regression objects (Linear, Ridge, and Random Forest).

self.results: A list used to store the calculated performance metrics for each model.

Methods:

run_analysis(): Handles the loading of data, splitting it into training and testing sets, and executing the training loop.

display_results(): Formats the performance metrics into a readable table using the Pandas library.


Limitations: 
The primary limitation of this implementation is the small size of the diabetes dataset. With only a few hundred samples, complex models like the Random Forest Regressor may be prone to overfitting, which is likely why the simpler Linear Regression model outperformed it in this specific test.


Chat Log: Don't forget to include a copy of this conversation in your repository to meet the generative AI requirements.

Would you like me to help you format the chat log so it's ready to upload to your GitHub?
