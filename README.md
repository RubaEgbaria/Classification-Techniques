# Classification Techniques Assignment

## Part One:

In this assignment, you will explore and experiment with several classification and predictive modeling techniques, including **K-Nearest Neighbors (KNN)**, **Support Vector Machine (SVM)**, **Decision Tree**, and **Naïve Bayes**.

### Tasks:
- **Decision Tree**: Tune it for the best hyperparameters.
- **KNN**: Tune it for the best K value.
- **For the best-tuned classifier**, you should determine the following metrics:
    - Confusion Matrix
    - Precision
    - Recall
    - F1-Score
    - Draw the ROC curves for all classifiers on one graph.

After computing these metrics, **interpret and explain your observations** based on the results.

---

## Part Two:

### Draw the training error and validation error curves on one graph for each of the above algorithms as follows:

1. **Data Split**: First, split your dataset into a **training set (70%)** and a **test set (30%)**.
   
2. **Cross-Validation Technique**: Use cross-validation on the training set to draw the training and validation error curves:
   
    - **Repeat the experiment 10 times**:
        - In the first experiment, use **10%** of the training set for training and validation.
        - In the second experiment, use **20%** of the training set, and so on, until the tenth experiment where you use **100%** of the training set for training and validation.
   
    - **Fold Division**: In each experiment, divide the used set (e.g., 10%, 20%, ..., 100%) into **10 folds**:
        - One fold is used for validation, and the other 9 folds are used for training.
        - Repeat this process **10 times**, each time recording the **training error** and **validation error**.
        - Finally, take the **average** of the training and validation errors for each experiment.
   
3. **Training & Validation Curves**: After completing the 10 experiments, you will have 10 average values for the **training error** and 10 average values for the **validation error**. 

    - **Plot the training and validation error curves** with respect to the training set size used in each experiment.
   
4. **Overfitting or Underfitting**:
    - Analyze the error curves to check if **overfitting** or **underfitting** occurs in your algorithm.
    - If either overfitting or underfitting is observed, **solve** the issue and show the result after applying the solution.
   
5. **Error Comparison**: Compare the **training error**, **validation error**, and **test error** for each algorithm.

---

## Notes:
1. You can find the data file on the **Moodle course page** under the name **"globalterrorism"**.
2. The target column in the dataset corresponds to **attack types**.
3. Pre-process the data (e.g., filling missing values, cleaning, scaling, etc.) **before applying the algorithms**.

---

### Submission Instructions:

- Ensure that your code is well-commented and easy to follow.
- Submit your report, which should include:
    - A description of your methodology.
    - The error curves for each algorithm.
    - Observations on overfitting or underfitting.
    - The final tuned model and its corresponding metrics.

Good luck!
