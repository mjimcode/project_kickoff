Aquí tienes la versión del README con algunos emojis para hacerla más visual y con los enlaces que mencionaste:

---

# 🏡 Madrid Housing Market Analysis - Machine Learning Project

## 📄 Overview

This project applies machine learning techniques to predict housing prices in Madrid using various regression models. The notebook includes data exploration, preprocessing, model training, and evaluation. The goal is to assess the performance of different algorithms in predicting housing prices, using metrics like Mean Squared Error (MSE), R-squared (R²), and Mean Absolute Error (MAE).

## 📁 Project Structure

- **Notebook**: The Jupyter notebook (`ML_project.ipynb`) contains the full analysis and model evaluation.
- **Data**: We used a dataset with features such as location, number of rooms, size, and price. You can access the metadata [here](https://drive.google.com/file/d/1nxtV2In6yIO9q8y1_6QjSYqg67KlpEYw/view?usp=sharing).
- **Models**: We implemented several machine learning models, including:
  - Linear Regression
  - Bagging Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - AdaBoost Regressor

## 🛠️ Dependencies

To run the notebook, make sure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the dependencies by running:

```bash
pip install -r requirements.txt
```

## 🔄 Data Preprocessing

- **Missing values** were handled appropriately.
- **Feature scaling** was applied to improve algorithm performance.
- The data was split into **training and test sets** using an 80/20 ratio.

## 📊 Models and Evaluation

We evaluated the performance of the models using the following metrics:

1. **Mean Squared Error (MSE)** 📉
2. **R-squared (R²)** 📊
3. **Mean Absolute Error (MAE)** 📈

Here are the results:

| Model                       | MSE  | R²   | MAE  |
|------------------------------|------|------|------|
| Linear Regression             | 0.17 | 0.46 | 0.33 |
| Bagging Regressor             | 0.15 | 0.51 | 0.30 |
| Random Forest Regressor       | 0.15 | 0.53 | 0.29 |
| Gradient Boosting Regressor   | 0.15 | 0.51 | 0.31 |
| AdaBoost Regressor            | 0.18 | 0.43 | 0.35 |

## 🏅 Results

- **Best Model**: The **Random Forest Regressor** performed the best, with an R² score of 0.53 and MAE of 0.29.
- **Model Comparison**: Ensemble methods (Bagging, Random Forest, Gradient Boosting) outperformed Linear Regression in this case.

## 🎯 Conclusion

This project showcases the application of machine learning in the real estate sector of Madrid. After evaluating multiple models, the **Random Forest Regressor** emerged as the best predictor of housing prices.

For more details, you can check the **presentation slides** [here](https://docs.google.com/presentation/d/1LVmDFHTKzmanNenxiTVsH-WEdEbPjotXDmI-wssVSgQ/edit?usp=sharing).

## 🚀 Future Work

- Explore additional features to enhance the model's performance.
- Fine-tune hyperparameters of the models for better accuracy.
- Extend the analysis to other regions or cities for broader comparisons.
