# Predicting Diabetes Risk

This project applies data science techniques to predict the risk of diabetes using a public health dataset.  
The goal is to build and compare machine learning models to identify individuals who are likely to develop diabetes.

## Dataset

The dataset used is `diabetes_binary_5050split_health_indicators_BRFSS2015.csv`,  
which contains health-related variables such as BMI, blood pressure, general health status, and more.

## Tools Used

- Python (Jupyter Notebook)
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

## Models Trained

Three models were trained and compared:

- **Logistic Regression**
- **Random Forest**
- **Gradient Boosting**

## Results Summary

| Model               | Accuracy (Test) | AUC (Test) | CV Accuracy |
|--------------------|-----------------|------------|-------------|
| Logistic Regression| 0.742           | 0.817      | 0.745       |
| Random Forest       | 0.710           | 0.779      | 0.711       |
| Gradient Boosting   | 0.747           | 0.824      | 0.748       |

Gradient Boosting achieved the best performance overall, both in accuracy and AUC.

## Conclusion

This project shows how different classification models can be applied to health data.  
Gradient Boosting was the most effective model in this case, but Logistic Regression also provided strong and interpretable results.  
The analysis demonstrates a typical data science workflow: from data exploration to model evaluation and comparison.

## Files

- `diabetes_prediction.ipynb`: Full analysis notebook  
- `diabetes_binary_5050split_health_indicators_BRFSS2015.csv`: Dataset used (add or link as needed)


## Dataset Source

The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)  
It contains synthetic health records created based on the 2015 BRFSS survey.



## How to Use

1. Clone this repository:

```
git clone https://github.com/Dagp8/diabetes-risk-analysis.git
```

2. Open the notebook:

- Use Jupyter Notebook (Anaconda) or Jupyter Lab.
- Run the cells step by step.

3. Requirements:

- pandas
- numpy
- matplotlib
- scikit-learn






