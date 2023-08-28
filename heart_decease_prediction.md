## Heart Disease Prediction (Logistic Regression)

**Project Link:**<a href="https://github.com/dilruu89/Kaggle/blob/main/01-logistic-regression-heart-desease.ipynb" target="_blank">Heart Disease Prediction Jupyter Notebook</a>

<div style="text-align: justify"> 

**Project description:** Studies show that coronary heart disease (CHD) is responsible for around 382,820 fatalities each year in the USA, while approximately  697,000 individuals face the risk of heart disease annually. It is not better in Australia, and CHD is a leading cause of death in Australia. Deaths from CHD represent 78,052 years of potential life lost in Australia. Hence, detecting heart conditions early on is very important to prevent them from happening or encourage high-risk people to make changes in their lifestyles or habits to minimize potential risks.
</div>

<div style="text-align: justify"> 
In this study, my goal is to identify the key factors contributing to heart disease and develop a predictive model for estimating the overall risk of heart disease using logistic regression analysis.
</div>

<div style="text-align: justify"> 
I used the Heart Disease Framingham dataset which is accessible on Kaggle for this analysis. It derives from an ongoing cardiovascular study conducted in Framingham, Massachusetts. 
</div>

```javascript
data = pd.read_csv('/kaggle/input/heart-disease-prediction-using-logistic-regression/framingham.csv')

```

### Techniques/ Algorithms / Metrics
<div style="text-align: justify"> 
In the beginning stages, I performed Exploratory Data Analysis (EDA). This was followed by the selection of important features, construction of the model, and subsequently evaluation of its performance. The primary techniques applied for model creation and performance assessment are as follows.
</div>
1. Logistic Regression
2. Correlation Analysis
3. Backward Feature selection
4. Confusion Matrix
5. ROC curve


