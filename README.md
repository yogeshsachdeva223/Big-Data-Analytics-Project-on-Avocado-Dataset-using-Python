<h1>Big Data & Data Analytics Project on Avocado Price Prediction</h1>
<p>By Yogesh Sachdeva, Akhil Sharma and Dhruv Khosla</p>
<h2>Introduction</h2>
<p>In this project we tried to explore and visualize the historical data of Avocado Prices dataset using python to test and train our machine leanring model.</p>
<h2>Objectives of the Project:</h2>
<p>1. Exploration & Visualizion the data <br>2. To examine if data has any structure<br>3. To do the Feature Engineering of data<br>4. To create the Data Pipelining<br>5. Perform the Hyperparameter tuning</p>
<h2>About Dataset</h2>
<p>In this study, we tried to see if we can predict the Avocado’s Average Price based on different features. The features are different (Total Bags,Date,Type,Year,Region…).

The variables of the dataset are the following:
Categorical: ‘region’,’type’
Date: ‘Date’
Numerical:’Total Volume’, ‘4046’, ‘4225’, ‘4770’, ‘Total Bags’, ‘Small Bags’,’Large Bags’,’XLarge Bags’,’Year’
Target:‘AveragePrice’.</p>


# This dataset is composed by the following variables:

Data Loading and Description
This data was downloaded and provided by INSAID, from the Hass Avocado Board website in May of 2018 & compiled into a single CSV.

Represents weekly 2018 retail scan data for National retail volume (units) and price.

The dataset comprises of 18249 observations of 14 columns. Below is a table showing names of all the columns and their description.

The unclear numerical variables terminology is explained in the next section:

Features	Description
‘Unamed: 0’	Its just a useless index feature that will be removed later
‘Total Volume’	Total sales volume of avocados
‘4046’	Total sales volume of Small/Medium Hass Avocado
‘4225’	Total sales volume of Large Hass Avocado
‘4770’	Total sales volume of Extra Large Hass Avocado
‘Total Bags’	Total number of Bags sold
‘Small Bags’	Total number of Small Bags sold
‘Large Bags’	Total number of Large Bags sold
‘XLarge Bags’	Total number of XLarge Bags sold

