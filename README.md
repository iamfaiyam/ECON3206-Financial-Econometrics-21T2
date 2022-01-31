# ECON3203-Econometric-Theory-and-Methods-21T3
Machine Learning group assignment - ECON3203 (2021 T3) - Distinction Grade

Project: ECON3203 Assignment (Faiyam Islam; 2021 T3) 

Description: Repository for Faiyam Islam's ECON3203 Assignment (2021 T3) 

Date: 12/11/21

## Built with...

• Python (Jupyter Notebook) 

## File Directory

• <b>Group_DFM_implementation.ipynb</b> Jupyter notebook containing the implementation code for the assignment </b>

• <b>Group_DFM_implementationPart2.ipynb</b> Jupyter notebook containing the part 2 of the implementation code for the assignment </b>

• <b>Group_DFM_document.pdf</b> Document containing all the interpretations and analysis of the machine learning code into one file </b>

• <b>Assignment brief.pdf</b> Assignment brief of the project </b>

• <b>ATM_training.csv</b> The training data used on this project </b> 

• <b>ATM_test.csv</b> The test data which was used to calculate the mean squared error and compared with other groups </b>

## Motivation 

Requirements summary: 

<b> • Exploratory data analysis of the training data, determining the features of the given covariates and interpreting basic graphs to grasp a basic understanding of the data at first-hand </b>

<b> • Methodologies that were conducted to determine the mean squared error and use the test data to confirm the validity </b>

<b> • Results and discussion of the different methodologies used, some were ineffective whereas others produced a substantially lower mean squared error </b>

## Summary of Code

  • Various basic plots including bar plots, scatter plots and box plots for summary statistics 
  
  • Simple and Multiple Linear Regression with hypothesis testing (using p-value) 
  
  • Ridge Regression and Elastic Net (regression with a penalty term) 
  
  • LASSO Variable Selection
  
  • KNN Classification 
  
  • Neural Networks
  
## Summary of Results

  • Models which were considered and fitted against the data include linear regression models such as OLS, LASSO, Ridge, and elastic net regression models which aided in the 
    feature selection process despite not having the lowest prediction error; KNN classification; and deep learning models.

  • Cross validation allowed for effective assessments of some models, whilst fitting against a validation dataset was used to test the predictive capabilities of other models. 
  
  • Ultimately, we identified the deep learning model to be the optimal model for predicting ATM cash demand, with the lowest CV MSE of 0.2550.
