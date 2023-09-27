## This is ML project

In this project, taken a student database in order to implement student performance predictor. Deployed this end to end ML application using CI CD pipelines and GitHub actions using ECR and EC2 instance.

Project Pipeline:
* Data Ingestion
* Data Transformation
* Model Trainer
* Model Deployment

### 1. Data Ingestion:
Data ingestion is the process in which unstructured data is extracted from one or multiple sources and then prepared for training machine learning models. 

### 2. Data Transformation
Data transformation is the process of converting raw data into a format or structure that would be more suitable for model building.

### 3. Model Trainer
Model training in machine learning is the process in which a machine learning (ML) algorithm is created or selected and fed with sufficient training data so that it could learn and give accurate predictions in the future.

### 4. Model Deployment
Deployment is the method by which we integrate a machine learning model into production environment to make practical business decisions based on data.


Used different ML models like LinearRegression, CatBoostRegressor, KNeighborsRegressor, DecisionTreeRegressor , XGBRegressor, also different ensemble techniques like - AdaBoostRegressor, GradientBoostingRegressor, RandomForestRegressor. From these list of models, got the best model along with the best model score.


### End to End Machine Learning Project deployment in AWS:
1. Docker Build checked
2. Github Workflow
3. Iam User In AWS


### Configured EC2 as self-hosted runner, and did setup GitHub secrets:
* AWS_ACCESS_KEY_ID=
* AWS_SECRET_ACCESS_KEY=
* AWS_REGION = 
* AWS_ECR_LOGIN_URI = 
* ECR_REPOSITORY_NAME =


### EC2 instance connection establshied with GitHub, and successfully completed Continuous Integration, Continuous Delivery and Continuous-Deployment

<p align="center">
  <img src="image.png" width="500">
</p>




### Run instance with Public IPv4 address

<p align="center">
  <img src="image-1.png" width="500">
</p>



<p align="center">
  <img src="image-2.png" width="500">
</p>


