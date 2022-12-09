Project Overview:

The aim of this project was to develop a machine learning model that could accurately predict whether or not a pediatric patient receiving reconstructive plastic surgery would develop a postoperative wound infection. The dataset used was from the American College of Surgeons NSQIP program, which gathers data from hospitals across the United States across different specialties to better understand medical trends and practice evidence based medicine. 

Exploratory data analysis was initially conducted along with preprocessing to clean the data set and prepare it for four different machine learning models to train on. The four different ml models used was the random forest classifier, support vector classifer, logistic regression, and k-nearest-neighbors. The model with the highest accuracy score of over 0.8 was the random forest classifier. 

Packages Used:

channels:
- conda-forge
- defaults
dependencies:
- python=3.10.5
- matplotlib=3.5.2
- pandas=1.4.2
- scikit-learn=1.1.1
- numpy=1.22.4
- xgboost=1.5.1
- shap=0.40.0
- jupyter_client=7.3.1
- jupyter_core=4.10.0
- jupyterlab=3.4.2
- jupyter_server=1.17.0
- jupytext=1.13.8
- rise=5.7.1
- plotly=5.8.0
- ipywidgets=7.7.0
- openpyxl=3.0.10
- seaborn=0.12.1
prefix: /opt/conda