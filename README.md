# Data Analysis of Housing Rental Prices in Berlin Using Python and Tableau
Data Analysis of AirBnB Rental Data available for Berlin, Germany using Python and Tableau. 

# Objective 

Airbnb is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based in San Francisco, California, the platform is accessible via website and mobile app. Airbnb does not own any of the listed properties; instead, it profits by receiving commission from each booking. The objective of this project is to analyze what variables may impact the price of housing and search for any noticable patterns.

# Data
The dataset contains the following key parameters that were measured to analyze any trends in prices of accommodations: 
1. price
2. neighborhood_group
3. neighborhood
4. latitude
5. longitude
6. room_type
7. minimum_nights
8. number_of_reviews
9. reviers_per_month
10. host_listings_count
11. availability_365
12. num_reviews_ltm
13. price_category 

Full details of the data is available [here](http://insideairbnb.com/get-the-data/) & [here](http://insideairbnb.com/berlin). 

# Tools 
The following Python libraries were used:
1. numpy - for working with arrays
2. pandas - for data analytics
3. scipy - to calculate mathematical problems
4. matplotlib - for visualization and graphical plotting
5. seaborn - for visualization
6. sklearn - for data analytics
7. folium - for geographical visualization

# Analysis

1. Sourcing Open Data

* Used Open Source Airbnb Berlin data.
* Completed preparatory steps before moving on to analysis (e.g., cleaning).
* Based on a comprehension of the contents of the data, defined questions.
* The code for the analysis can be found here: [Sourcing Open Data](https://github.com/ritik8801/Data-Analysis-of-Rental-Prices-in-Berlin-Using-Python-and-Tableau/blob/main/Project%20Code/Sourcing%20Open%20Data.ipynb).

2. Exploring Relationships

* Conducted exploratory visual analysis using relevant Python libraries.
* Used the questions, defined in the previous task to guide the data exploration.
* Defined possible hypothesis to test.
* The code for the analysis can be found here: [Exploring Relationships](https://github.com/ritik8801/Data-Analysis-of-Rental-Prices-in-Berlin-Using-Python-and-Tableau/blob/main/Project%20Code/Exploring%20Relationships.ipynb).

3. Geographical Visualizations with Python

* Sourced a shapefile containing location data.
* Wrangled, cleaned, and merged data files for preparation of analysis.
* Conducted a geospatial analysis by creating a choropleth map using relevant Python libraries.
* The code for the analysis can be found here: [Geographical Visualizations with Python](https://github.com/ritik8801/Data-Analysis-of-Rental-Prices-in-Berlin-Using-Python-and-Tableau/blob/main/Project%20Code/Geographical%20Visualizations.ipynb).
* Results from the Geographical Visualizations Analysis can be found here: [Analysis](https://github.com/ritik8801/Data-Analysis-of-Rental-Prices-in-Berlin-Using-Python-and-Tableau/tree/main/Analysis).

# Tableau Dashboard
[Data Analysis of Housing Rental Prices in Berlin](https://public.tableau.com/app/profile/ritik.mishra/viz/DataAnalysisofRentalPricesinBerlin/AirBnBBerlin?publish=yes)
