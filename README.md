# Capital Bike Share

<p align="center">
  <img width="600" height="300" src="https://dcist.com/wp-content/uploads/sites/3/2019/02/cabi_web-900x600.jpg">
</p>

This dataset contains the hourly and daily count of rental bikes between different years in Capital bikeshare system with the corresponding weather and seasonal information. Please refer to the website for further reference: https://www.capitalbikeshare.com/

# Data Set Information:
Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.

Apart from interesting real world applications of bike sharing systems, the characteristics of data being generated by these systems make them attractive for the research. Opposed to other transport services such as bus or subway, the duration of travel, departure and arrival position is explicitly recorded in these systems. This feature turns bike sharing system into a virtual sensor network that can be used for sensing mobility in the city. Hence, it is expected that most of important events in the city could be detected via monitoring these data.

# Exploratory Analysis:
In the segmant of exploratory analysis, I analyzed data from 2011-12 using barplots, boxplots, pairplots, lineplots and scatterplots. While doing this analyze I used several metrics such as, average number of bike rentals in day/hour, average rental duration, average distance and average speed. Member type, season, month, weekday and weather these are the main dimensions used in analysis.

# Facebook Prophet:
Facebook’s Prophet library is designed to do Time Series forecasting and supports R and Python. In this stage, The full 2018-20 data from the company website were used to give a forecast using Facebook Prophet. We used this library:

to predict What the future bike sharing demand will look like for the next 3 months.

to investigate Factors that contribute to demand.

to find out the hidden opportunities for increasing demand.

# FlaskApp:
Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. In this stage, we made an app with Flask to get a prediction of rented bikes per hour by using AdaBoostRegressor as regression. It takes an input of weekday, hour, month, member type and is a holiday or not, and gives a prediction of bike usage within the hour. The app can be found on https://bike-share-count.herokuapp.com.

<p align="center">
  <img width="700" height="150" src="https://user-images.githubusercontent.com/73485296/110383888-40a80880-805d-11eb-956f-7047c176a4a1.png">
</p>


For Further analysis please refer https://www.capitalbikeshare.com/.
