# GeoSpatial Analysis - Zomato Data Analysis Project 🔥

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
 
</p>  

![zomato](https://user-images.githubusercontent.com/84115928/139818260-1d656ae6-8abb-455f-9c1a-5b036734e484.jpg)

# 📝Problem Statement
Analysis of the following is required by the Sales Director of Zomato Food Chain:

    1. Most famous Restaurant Chains in Bangalore.
    2. Analyse Restaurants which are Accepts Online Order and do not ones.
    3. Highest Voted Restaurant.
    4. Places with Maximum Number of Restaurants / Total Restaurants at different locations of Bangalore.
    5. Total Number of variety of Cuisine Restaurants in Bangalore.
    6. Relationship between "Approx Cost of 2 People" vs "Rating" for those Restaurant that Accepts "Online Order" and for those Restaurants that doesn't Accept "Online Order".
    7. Is there any difference b/w 'Votes' and 'Restaurants' Accepting and Not Accepting "Online_Orders".
    8. Identify Restaurants that are Budgeted Hotels as well as Affordable.
    9. Restaurants having good Rating and Budgeted/Affordable too.
    10. Most Foodie Areas of Bangalore.
    11. Clutter of particular Cuisines in Bangalore. North Indian Restaurants, South Indian Restaurants, Biryani Cuisines.
    12. Analyze where are the Restaurants with Most Average Ratings.

And so many more!!

# ⏳ Dataset
Download the dataset for this project from following Link -
* [Zomato Bangalore Restaurants](https://drive.google.com/file/d/1TKrIHvWzE6mzX_zgm4tETNw1TctjLtEA/view?usp=sharing)

# 📚 Data Analysis
In the datasets, we are provided with 17 columns(Features) of data.

* **url** : Contains the url of the restaurant on the Zomato Website.
* **address** : Contains the Address of the restaurant in Bangalore.
* **name** : Contains the Name of the restaurant.
* **online_order** : Whether Online Ordering is available in the restaurant or not.
* **book_table** : Table book option available or not.
* **rate** : Contains the Overall Rating of the restaurant out of 5.
* **votes** : Contains total number of ratings given for the restaurant.
* **location** : Contains the neighborhood where the restaurant is located.
* **rest_type** : Restaurant type.
* **dish_liked** Dishes people liked in the restaurant.
* **cuisines** : Food styles.
* **approx_cost(for two people)** : Contains the approximate cost for the meal of two people.
* **reviews_list** : Containing rating and review given by the customer.
* **listed_in(city)** : Contains the neighborhood in which the restaurant is listed.

Out of the 17 features given in the datasets, 04 are Continuous and 13 (including the target variable) are Categorical features.

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE.
* Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* Geopy and Folium libraies were used to perform Spatial Analysis.
* GitHub is used as version control system

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/139908931-11089695-88cf-4e78-8a7a-44bc8d75a560.png">
</p>

# 🎉 Tasks performed under Spatial Analysis:
* Extract the **"Latitude"** and **"Longitude"** w.r.t. different Locations using Python's ***Geopy*** Library.
* Generated a **"BaseMap"** of Bangalore using Python's ***Folium*** Library.
* Plotted a HeatMap based of variety of Use Cases with the help of Python's ***Folium "HeatMap" Plugins.***
* Performed **"Marker Cluster Analysis"** on top of the **"HeatMap"** using Python's ***Folium "FastMarkerCluster" Plugins.***

# 🌱 Some Exciting Glimpse of the Visuals:
  
<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/140026316-9a502e15-e4b6-4e02-9a89-c09cde6776a3.gif">
  <img width="533" height="320" src="https://user-images.githubusercontent.com/84115928/140026350-99fa7833-3959-4cb4-8ca9-c1817522d9f1.gif">
</p>

For more details, please go through the Jupyter Notebook attached above.
