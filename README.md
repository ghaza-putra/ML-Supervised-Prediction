# ML-Supervised-Prediction-CoverTypes
## Background Problem
This project aims to predict land cover types using the Roosevelt National Forest dataset, which includes environmental and topographic features. This prediction is crucial for conservation, forest management, and land planning. An accurate and interpretable classification model is built using various supervised machine learning algorithms such as Random Forest, KNN, Naive Bayes, Decision Tree, and Logistic Regression. The project includes stages of Preprocessing & EDA, modeling, and Model Evaluation.

## Libraries Version
- Pandas version: 2.2.2
- Numpy version: 2.0.2
- Matplotlib version: 3.10.0
- Seaborn version: 0.13.2
- Scikit-learn version: 1.6.1

## Insight
1. **Random Forest:** has the highest accuracy (0.93) with a high TP (225) and low FP (20), showing the best performance.
2. **KNN:** achieves an accuracy of 0.92, with solid results and minimal errors (FP = 11).
3. **Decision Tree:** has an accuracy of 0.89, with a high TP (210), but slightly more errors (FP = 26).
4. **Logistic Regression:** shows the lowest accuracy (0.55) with high FP and FN, making it less effective for this prediction.
5. **Naive Bayes:** has an accuracy of 0.64, but performs poorly with high FN (129) and low TN (108).

## Advice
Based on the evaluation results, Random Forest is the most recommended model with the highest accuracy (0.93) and low errors, making it highly effective for predicting land cover types. KNN also shows very good performance (0.92) and can be a strong alternative, especially if computational efficiency is prioritized, although it is more sensitive to imbalanced data. Decision Tree with an accuracy of 0.89 provides solid results but requires careful parameter tuning to avoid overfitting. On the other hand, Logistic Regression and Naive Bayes have low accuracy (0.55 and 0.64) with relatively high error rates, making them less effective for this task and suggesting that they should be replaced with more suitable models. Overall, Random Forest, KNN, and Decision Tree are the best choices for predicting land cover types.

#ML #Python #CoverTypes #DataScience #SupervisedLearning Feel free to connect with me if you'd like to discuss anything
ghazaputra99@gmail.com
