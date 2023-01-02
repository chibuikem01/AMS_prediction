# AMS_prediction

1.1  **Overview**
The repository forms the processes followed in predicting the average monthly sales of items at a given depot. It hosts codes contained in diferent files. 

<a href = 'https://chibuikem01-ams-prediction-app-xicroh.streamlit.app/'>Link to API Endpoint<a/>

2.1 **app.py**
The app.py contains in details the API codes by calling the model.py. The app.py hosts codes used to deploy a basic Streamlit web application(a simple and powerful app model that lets you build rich UIs incredibly quickly). 

3.1 **model.py**
 The model.py contains the codes used in the data preprocessing and modeling stage. The variables used to predict the the Average monthly sales are the months,item_no and depot. The random forest model among all other models trained appeared to be the best performing model with lower root mean square values(rmse) when compared to the rest.
 
4.1 **model deployment**
The model's api was deployed on Heroku to retrieve a url where predictions could be make for the average monthly sales. Heroku is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.
Below is the api interface where the various inputs are required for a prediction.

<p align='center'>
   <img src="images/streamlit_outpt.jpg"
   alt='API prediction UI'
   width=700px/>
   <br>
</p>


Th
