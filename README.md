# TUSK_final_project
The aim of the project is to predict students' answers to diagnostic questions with Matrix Factorization Algorithms.

The project is done as an individual project as a part of the UpSkilling Program offered by UofT and Vector Institute ([Machine Learning Software Foundations](https://tusk.utoronto.ca/programs/course-details/machine-learning-software-foundations)).

## Data
The data consists of correct and incorrect answers to diagnostic questions of an online learning platform. The matrix is very sparse. Also, the metadata (characteristics) of students and questions were given but were not used in this project. 

## Methodology
I compared the following Matrix Factorization algorithms: Singular Vector Decomposition, Non-Negative Matrix Factorization, and Logistic Matrix Factorization using the accuracy metric. Additionally, as some algorithms don't accept missing values I provided the functionality to test the model on different missing value imputation strategies. I tuned hyperparameters with the Bayesian Optimization algorithm to get the best results on each algorithm.

