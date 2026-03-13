# Diabetes-Scikit-Learn-Regression-Models
Project Overview-- Purpose: This project utilizes machine learning regression to predict the progression of diabetes in patients. 



Context: Diabetes is a complex condition involving glucose regulation, and modern research uses machine learning to detect and prevent disease progression.

Objective: Build and compare three distinct regression models to determine which best predicts disease outcomes based on physiological metrics.System RequirementsLanguage: Python 3.xLibraries: scikit-learn, pandas, numpy

Execution Environment: Any Python IDE or terminal with the above libraries installed.

Implementation Details

Type of Execution

    Object-Oriented Programming (OOP): The project is implemented using a class-based structure to ensure modularity, high readability, and easy maintenance.

Class Design: 

    DiabetesModelerPurpose: To encapsulate the entire machine learning pipeline—from data loading to performance evaluation.

Attributes:

    self.models: A dictionary containing the initialized machine learning estimators (Linear Regression, Ridge Regression, and Random Forest).
    
    self.results: A list used to store performance metrics for comparison.Methods:run_analysis(): Loads the dataset, performs the training/testing split, and fits each model to the 
    
    data.display_results(): Aggregates the performance metrics into a formatted table for user review.

Inputs and Outputs:

    Input Data: The built-in Scikit-Learn diabetes dataset, which includes 10 baseline variables such as age, sex, body mass index, and blood serum measurements.
    
    Processing: Data is divided into training and testing sets to evaluate model performance on unseen data.
    
    Output: A console-based summary table displaying the Mean Squared Error (MSE) and $R^2$ Score for each model, followed by a selection of the best-performing model.

Model Evaluation Results


    Linear Regression Mean squared error 2900.19 R2 score 0.4526
    
    Ridge Regression Mean squared error 3077.42 r2 score0.4192
    
    Random Forest Mean squared error 2952.01 R2 score 0.4428
    
    Best Performer: The Linear Regression model yielded the best results with the lowest MSE and highest $R^2$ score.

Analysis: 

    While the Random Forest is a more complex model, the linear nature of this specific dataset allowed the simpler Linear Regression model to generalize better.

Limitations:

    Dataset Size: The dataset is relatively small (442 instances), which may cause more complex models like Random Forests to overfit the training data.
    
    Scope: These models predict a quantitative measure of disease progression; they do not diagnose the disease itself.

Generative AI Disclosure

    Usage: Generative AI was used to assist in structuring the Python class and formatting this documentation.
    
    Verification: All AI-generated code and analysis were manually reviewed and corrected for technical accuracy, specifically regarding function arguments and metric interpretation.

Chat Log: [https://gemini.google.com/share/bc26ec483e35](https://gemini.google.com/share/bc26ec483e35)
