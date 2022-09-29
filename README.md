# Capital Bike Share 

* This project analyses data from the bike-share company Capital Bike Share, based in Washington DC. 
* The project comprises the following parts

### 1) Data wrangling
* Please see the notebook **data_wrangling.ipynb**

### 2) EDA 
* Please see the notebook **EDA.ipynb**

#### EDA Part 1: User behaviour analysis
* Covers the years 2011–2012
* Analyse number of rides in relation to date-time and weather conditions

#### EDA Part 2: Time series analysis
* Covers the years 2011–2019
* Analyse trend and seasonality in the number of rides by registered and non-registered customers

### 3) Interactive maps
* Please see the notebook **interactive_map.ipynb**
* Here I use the package folium to create interactive maps that visualise the most popular docking stations over the years

#### Map 1
* Please follow this [link] (http://nbviewer.org/github/kyungoh22/bike_analysis/blob/main/interactive_maps/top_20_stations.html)
* Map showing top 20 docking stations for each of the years 2011–2019
* The map differentiates between registered and non-registered customers
* On the top right, you can choose the year and registered vs casual customers

#### Map 2
* Please follow this [link] (http://nbviewer.org/github/kyungoh22/bike_analysis/blob/main/interactive_maps/heat_map_with_time.html)
* Heat map with time, showing the density of rides per station during the years 2011–2019
* Please click the "play" button on the bottom left
* You can also freeze the time using the slider

### 4) Linear regression: predict number of rides

* Please see the notebook **linear_regression.ipynb**

* Feature selection / reduction using VIF and p-value
* Alternate feature selection using common sense and domain knowledge
* Building linear regression model to predict number of users based on selected features
* Regularisation
