# Medical-Insurance-Cost

This notebook has taken us on an investigative journey through the medical insurance cost dataset (https://www.kaggle.com/datasets/mosapabdelghany/medical-insurance-cost-dataset/data).I performed data cleaning, exploratory analysis (EDA) with a wide range of visualizations, and built several predictive models. The R-squared score provides an initial gauge of our model's fit, though further feature engineering and model tuning could be pursued.

The models I compared include:

- LinearRegression

- Lasso

- Ridge

- ElasticNet
  
- Decision Tree
  
- RandomForestRegressor
  
- GradientBoostingRegressor
  
- SVR

After running hyperparameter tuning on all models, the Random Forest Regressor was selected as the best model, achieving an R² score of 0.87.

Feature importance analysis showed that smoking status is the most influential feature, with an importance score of 0.6. This confirms that smoking significantly increases medical charges — highlighting that beyond health risks, smoking is also financially costly.

🔧 Possible Improvements

My current code repeats similar steps for each model. In the future, I plan to automate training and evaluation with functions or pipelines to make the workflow more efficient.

I would also like to experiment with cloud platforms (e.g., AWS) to scale up computation, rather than relying solely on my local laptop.
