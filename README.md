# Spatial-analysis
# GeoSpatial Analysis - Zomato Data Analysis Project 🔥

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/Lokesh-Attarde/Geospatial-Analysis-Project)
  ![GitHub forks](https://img.shields.io/github/forks/Lokesh-Attarde/Geospatial-Analysis-Project)
  [![GitHub contributors](https://img.shields.io/github/contributors/Lokesh-Attarde/Geospatial-Analysis-Project.svg)](https://GitHub.com/Lokesh-Attarde/Geospatial-Analysis-Project/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
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
* [Zomato Bangalore Restaurants](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants/download)

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
![Glimpse 1](https://user-images.githubusercontent.com/84115928/140026074-61d742db-5909-43bf-ae6f-b1586e9d73eb.gif)
![Final Glimpse 2](https://user-images.githubusercontent.com/84115928/140026135-7d40a13e-4c76-47fc-b26b-81e4ab2bdefe.gif)
![Final Glimpse 3](https://user-images.githubusercontent.com/84115928/140026180-d24ef4d3-c492-43f0-95f4-5f4cb65a0ea8.gif)
  
<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/140026316-9a502e15-e4b6-4e02-9a89-c09cde6776a3.gif">
  <img width="533" height="320" src="https://user-images.githubusercontent.com/84115928/140026350-99fa7833-3959-4cb4-8ca9-c1817522d9f1.gif">
</p>

For more details, please go through the Jupyter Notebook attached above.

# 📋 Challenges Faced during this Project:
* To know about What are the different kinds of challenges encountered during this project, do connect with me for more details.

# 💡 Conclusions

* "Cafe Coffee Day" is on Peak. Next, We have "Onesta", followed by "Empire Restaurant" and so on.
* "64.4%" Restaurants accepts Online Order whereas around "35.6%" Restaurants does not accepts Online Order.
* Highest Voted Restaurant is "Onesta", followed by "Truffles" and "Empire Restaurant".
* Widefield and BTM has the Maximum Number of Restaurants.
* Most of the Highest Rated Restaurants Accepts "Online Order" and they are, of course, affordable whereas there are some Highest Rated Restaurants who do not Accepts "Online Order" and they are Expensive.
* Average number of Votes for both Categories Varies because the Restaurant who's Accepting "Online Orders", get More "Votes" from Customers as there is a "Rating" window popping-up after each 'Order Place' from the "Zomato" Application.
  That's Why Restaurants having 'Online Order' faciliy has "Maximum Number of Votes" compared to do not ones.
* More than 50% of Restaurants having approximate cost for 2 people is less than "1000 Rs." and they are Affordable too in Bangalore.
* Around "372" Restaurants are "Affordable" as well as they have good "Rating" I.e. greater than 4 out of 5.
* "BTM", "5th Block", and "HSR" has the Most Number of Restaurants/Most Foodie Areas. "BTM" dominates the section by having around "5K" Restaurants.
* In "South-East" Bangalore Region, We have "Maximum Number of North Indian Restaurants". Again in that Zone, We might have a "Maximum Number of North Indian People".
* In "South-West" Bangalore Region, We have "Maximum Number of "South Indian Restaurants" followed by "Central" and "South-East" Bangalore.
* Now, In terms of "Biryani", in "South" Bangalore Region, We have "Maximum Number of "Biryani cuisines Restaurants" followed by "South-West" and "Central" Bangalore.

And so many more!!

# 🎉 Help Me Improve
Hello Mr. Reader, if you find any bug or anything else that could add more value in this project then please consider raising it to me I will address them asap.
  
# 📫 Feedback
If you have any feedback, please reach out to me via [LinkedIn](https://www.linkedin.com/in/lokesh-attarde-145086141/)
