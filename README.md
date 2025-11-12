# ml-midterm-Bashyal
# Title: Build and evaluate different classification models to predict real bank notes from counterfeit ones

## Objective
To learn how to apply different classification models used in machine learning. 

---

## Introduction


In this project, We will use the Banknote Authentication dataset to build and evaluate different classification models in order to determine if the banknote is authentic or not.

## Steps Involved

### Section 1: Importing and Inspecting the data
1. Import necessary libraries  
2. Load the UCI Banknote Authentication Dataset
3. Display basic dataset information
4. Check for missing values and summary statistics
---

### Section 2: Data Exploration and Preparation
1. Explore data pattern and distributions
2. Handle missing values and clean data
3. Perform feature engineering  

---

### Section 3: Feature Selection and Justification
1. Choose features and target 
2. Define **X** (features) and **y** (target) 

---

### Section 4: Train a Classifcation Model (Decision Tree)
1. Split the data
2. Create and Train Model (Decision Tree)
3. Predict and Evaluate Model performance
4. Report confusion matrix (as a heatmap)
5. Report Decision Tree plot
   
### Section 5: Improve the Model or Try Alternates
1. Train and Evaluate Neural network model on Case 1
2. Visualize Neural network model for Case 1
3. Train and Evaluate Neural network model on Case 2
4. Visualize Neural network model for Case 2
5. Train and Evaluate Neural network model on Case 3
6. Visualize Neural network model for Case 3

### Summarize the findings
| Model Type           | Case   | Features Used         | Accuracy | Precision | Recall | F1-Score | Notes |
| -------------------- | ------ | --------------------- | -------- | --------- | ------ | -------- | ----- |
| Decision Tree        | Case 1 | Curtosis and Variance | 92.00%   | 93.10%    | 88.52% | 90.76%   | -     |
| Decision Tree        | Case 2 | Skewness and Variance | 92.73%   | 94.74%    | 88.52% | 91.53%   | -     |
| Decision Tree        | Case 3 | Entropy and Variance  | 86.91%   | 84.68%    | 86.07% | 85.37%   | -     |
| Neural Network (MLP) | Case 1 | Curtosis and Variance | 86.18%   | 84.43%    | 84.43% | 84.43%   | -     |
| Neural Network (MLP) | Case 2 | Skewness and Variance | 93.82%   | 92.68%    | 93.44% | 93.06%   | -     |
| Neural Network (MLP) | Case 3 | Entropy and Variance  | 90.18%   | 89.26%    | 88.52% | 88.89%   | -     |

### Final thoughts and insights
#### Overall, based on these analyses, Skewness and variance seems to be the best predictors of finding out whether the bank note is genuine or counterfeit. In case of decision tree, the accuracy and precision of the model was 92.74% and 94.74%, respectively, with a F1 score of 91.53%. When we used the Neural Network method, the accuracy and precision of the model was 93.82% and 92.68%, respectively with a F1 score of 93.06%. Moreover, when we compare the two models (Decision Tree vs Neural Network), Neural network seems to a better model in predicting genuine bank notes from counterfeit ones. 
   

---
