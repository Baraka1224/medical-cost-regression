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

##  Reflection

This exercise reinforced the importance of data encoding and pipeline automation in regression workflows. Despite using a basic model, it yielded insightful predictions and formed a strong foundation for further model enhancements.

---

## 🗂Files in Repository

- `Medical cost personal dataset`: Main notebook with code, training, and evaluation
- `insurance.csv`: Dataset used
- `README.md`: This documentation
