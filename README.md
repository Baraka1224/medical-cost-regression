Medical Cost Regression Project

This project demonstrates how to predict individual medical insurance charges using a **Linear Regression** model. The dataset contains demographic and health-related information that influence insurance costs.

## Dataset

**Source:** [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
**Columns:**
- `age`
- `sex`
- `bmi`
- `children`
- `smoker`
- `region`
- `charges` (target)

## Approach

- **Data Preprocessing:** Handled categorical variables using OneHotEncoding and built a preprocessing pipeline.
- **Model Used:** Linear Regression from scikit-learn.
- **Evaluation Metric:** Mean Squared Error (MSE) to assess the model's accuracy.

##  Results

After training and testing the model, the Mean Squared Error on the test set was printed in the notebook. Model accuracy may improve by:
- Using a larger dataset
- Trying other regression techniques (Ridge, Lasso, Random Forest)

##  Reflection on the Problem and Solution
This project aimed to predict individual medical insurance charges using linear regression based on factors like age, BMI, smoking status, and region. Through this process, I gained practical experience in handling real-world healthcare data and building a supervised machine learning pipeline.

One of the key challenges was preprocessing the categorical variables, especially ensuring that unseen categories did not cause errors during model evaluation. Using OneHotEncoder with the right parameters (drop="first" and handle_unknown="ignore") helped create a robust preprocessing pipeline that handled this gracefully.

While the Linear Regression model was simple and easy to interpret, it still provided valuable insights into how lifestyle and demographic factors influence medical costs. However, the model’s accuracy may be limited by the linearity assumption and potential outliers in the dataset.

In future iterations, I would explore:

Using more advanced models like Ridge, Lasso, or Gradient Boosting

Performing deeper exploratory data analysis (EDA)

Adding interaction features (e.g., smoker * age)

Evaluating model fairness across different subgroups

Overall, this project reinforced the importance of data preprocessing, evaluation metrics like Mean Squared Error (MSE), and model interpretability in healthcare analytics.
## Files in Repository

- `Medical cost personal dataset`: Main notebook with code, training, and evaluation
- `insurance.csv`: Dataset used
- `README.md`: This documentation
