# Module 21 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    * The purpose of this analysis is create a model that would model loan risk.
    
* Explain what financial information the data was on, and what you needed to predict.
    * The model was trained on loan size, interest rates, borrower income, debt to income ratio, number of accounts
      derogatory marks, and total debt.  The objective was to predict the status of the loan.
      
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    * A loan status of 1 meant that the loan was a high-risk loan and a 0 meant that the loan was a healthy loan.
    
* Describe the stages of the machine learning process you went through as part of this analysis.
    * Individual scores cannot be considered separately.  Also, understanding the objective is paramount when choosing a model
      and interpreting results from that model.  Machine learning results in general are not so straightforward and it may take multiple
      attempts to achieve a model that satisfies the objective.  A good score in accuracy does not necessarily mean that the 
      model chosen is the most appropriate for the task. 
      
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    * Logistic Regression is useful in a case such as this where the decision is ultimately binary.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
        * Accuracy was .99 out of 1 which that is the overall number of correct predictions out of the total predictions.
        * Precision was 1 out of 1 which is the number of true positive and true negative out of all predictions.
        * Recall was .91 out of 1 which is the number of true positive over the total of true negative and true positive.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best? <br>
    Determining the most effective model for your data involves several key steps and considerations. Initially, it's essential to thoroughly understand your dataset whether it's supervised or unsupervised along with your specific goals, be they categorization, classification, or prediction. Once you have a clear understanding of your data and objectives, the process involves experimenting with different models to see which yields the best results.

    In practice, achieving 100% accuracy is usually unattainable, so the goal is to select a model that provides a robust explanation and reliable predictions within the scope of your requirements. For instance, K-means clustering is very effective for categorizing data into distinct groups. Regression models excel in estimating probabilities and understanding relationships between variables. On the other hand, Random Forest is excellent for handling complex datasets with intricate structures due to its ability to manage overfitting and provide significant accuracy.

    Ultimately, the best model is one that not only performs well statistically but also aligns with your practical needs and helps in making informed decisions based on its predictions.
   
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) <br> It depends on the situation.  In this instance predicting the 1's would be more important since the goal is inherently to reduce            risk.

If you do not recommend any of the models, please justify your reasoning.
