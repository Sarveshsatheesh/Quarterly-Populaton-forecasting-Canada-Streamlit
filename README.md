# About
* This project aims to forecast the quarterly population in Canada using a dataset obtained from Statistics Canada spanning from 1991 to 2023. It utilizes a multi-page application approach, with a focus on the forecasting functionality. The project includes data reading, user interface for target selection and forecast horizon, and three time series forecasting models: autoregressive, double exponential smoothing, and theta model. The best model is selected based on symmetric mean absolute percentage error (sMAPE) and trained on the entire dataset for generating out-of-sample predictions. Visualizations of predictions and model performance provide insights into population trends and forecasting accuracy.

# Objective
* The goal of this project is to Forecast the quarterly population in Canada.

# Dataset
* The dataset used in this project is obtained from the official website of Statistics Canada. It spans from the third quarter of 1991 to the first quarter of 2023 and provides quarterly population data for Canada. The dataset serves as the foundation for the forecasting task and enables the analysis and prediction of population trends over time. By leveraging this reliable and official source of data, the project aims to generate accurate forecasts and gain insights into the population dynamics of Canada. https://www150.statcan.gc.ca/t1/tbl1/en/cv.action?pid=1710000901

# Models
* For the modeling part of this project, three forecasting models are utilized simultaneously: autoregressive, double exponential smoothing, and theta model. Each of these models is trained and evaluated independently on the dataset. The evaluation is performed using the symmetric mean absolute percentage error (sMAPE) as the metric.

* After training and evaluation, the model with the lowest sMAPE is selected as the best model for forecasting. By considering the model with the least sMAPE, we prioritize the model that exhibits the smallest average percentage error between the predicted and actual population values. This approach ensures that the chosen model demonstrates the highest level of accuracy and reliability in predicting the population for the desired forecast horizon.

# UI Screenshots
![image](https://github.com/Sarveshsatheesh/Quarterly-Populaton-forecasting-Canada-Streamlit/assets/67963861/3840d66f-28be-4f0f-8d94-4f9007239802)
![image](https://github.com/Sarveshsatheesh/Quarterly-Populaton-forecasting-Canada-Streamlit/assets/67963861/e4aac4e0-c45d-456a-a97a-1ab1c0cbd499)





