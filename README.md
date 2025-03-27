# Netflix Global Top 10 Performance Predictor (Python)

### 🎬 Predicting Netflix Title Performance 📊 <br>


Can we predict how many hours a Netflix title will be viewed based on its first two weeks in the Global Top 10? What trends influence what we watch? To find out, I developed a multiple linear regression model to forecast the success of Netflix titles in the Global Top 10. <br>


### 💡Key results:
 - **77.0%** of the variation in total hours viewed is explained by the model
 - **All predictors** were statistically significant, meaning they have a measurable impact on total hours viewed
 - **Category matters:** 📺 TV shows tend to perform better than 🍿 Films


### 📊 Statistical Approach:
 -  **Data Preprocessing:** applied log transformation and removed outliers beyond IQR for model robustness <br>
 -  **ANOVA & Tukey’s HSD Test:** identified significant differences in viewing trends across content categories <br>
 -  **Regression Diagnostics:** assessed homoscedasticity, multicollinearity, and normality (Q-Q plot, histogram) <br>
 -  **Model Evaluation:** computed R², adjusted R², F-statistic, and Mean Squared Error (MSE) <br>


### 🔗 Project Resources:
📖 Jupyter Notebook: [GitHub](https://github.com/dpb24/netflix-global-top-10-performance-predictor/blob/main/netflix-global-top-10-performance-predictor.ipynb) | [Kaggle](https://www.kaggle.com/code/davidpbriggs/netflix-global-top-10-performance-predictor)  <br>
📂 Dataset: [Netflix Global Top 10 weekly data](https://www.kaggle.com/datasets/davidpbriggs/most-popular-netflix-shows) <br>


<div style="display: flex; justify-content: center; align-items: center;">
    <img src="netflix_global_top_10_weekly.png" width="800">
    <img src="netflix_global_top_10_model_results.png" width="800">
</div>
