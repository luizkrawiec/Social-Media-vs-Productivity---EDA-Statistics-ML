# 📊 Social Media vs Productivity - EDA-Statistics-ML

This project explored the relationship between digital habits, lifestyle factors, and actual productivity using both regression and classification approaches.

## 🔹 Regression
We predicted the continuous variable `actual_productivity_score` using a Random Forest Regressor.  
The model performed strongly, achieving an R² score of **0.85**, suggesting that the selected features explain a significant portion of the variance in productivity.

The most important predictor was the **perceived productivity score**, indicating a strong alignment between individuals’ self-assessment and their actual performance. Other variables such as job satisfaction, sleep hours, and screen time before sleep also contributed, though to a lesser extent.

## 🔹 Classification
We also categorized productivity into three levels (`Low`, `Medium`, `High`) and used a Random Forest Classifier.  
The model achieved an overall accuracy of **82%**, performing well especially in identifying users in the **Low** and **High** categories. The **Medium** group showed lower performance, possibly due to overlap in behaviors with both extremes.

Feature importance in the classification task mirrored the regression task, again highlighting **perceived productivity** and **job satisfaction** as the most influential variables.

## 📈 Summary
Both models consistently demonstrated that:
- **Self-perception (perceived productivity)** is a powerful indicator of actual productivity.
- **Job satisfaction** and certain lifestyle elements (like sleep and offline time) are relevant but secondary.

## 🚀 Next Steps
To improve model performance and generate deeper insights:
- Apply advanced feature engineering (e.g., feature interactions or ratio features).
- Try additional models (e.g., XGBoost, LightGBM, or interpretable models like Lasso).
- Use SHAP values for explainable AI insights.
- Address class imbalance using SMOTE or weighted classes.
- Segment analysis by demographics or job type for richer patterns.

