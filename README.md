# Asthma Hospitilization Counts Analysis using GLM and Non-parametric Models

## Research Question: What factors impact asthma hospitalizations most greatly in the United States? How can we predict asthma hospitalizations based on demographic (socioeconomic and racial) data and environmental data such as PM2.5 and ozone levels?

#### Language: Python
#### Libraries: Pandas, Statsmodels, Scikit-learn

### Notebooks completed in Jupyter Description: 

1) Data cleaning - Cleaning datasets across 5 different states in the United States with publicly available data on asthma hospitalization accounts and merging with PM2.5, ozone, and demographic data to form a comprehensive csv file containing predictors and the dependent variable in preparation for running a generalized linear model (GLM). 
2) GLM - On the cleaned dataset, running a comparison of GLM (frequentist method) in comparison to a nonparametric method (random forest and decision tree) to see which models perform with the lowest RMSE. Also determine which variables/predictors are most important for predicting hospitalization counts due to asthma for each respective model.
