
# Exploratory Data Analysis On Airbnb Bookings Analysis using Python

For this project, we will be analyzing Airbnb’s New York City(NYC) data of 2019. This dataset contains listings information such as listing name, host name, minimum night stays, availability, area, reviews etc.

The main objective behind this project is to explore and analyze the data to discover the key understandings. For this, we will explore and visualize the dataset from Airbnb in NYC using basic exploratory data analysis techniques.

## Dataset
Download the dataset for this project from following Link
https://github.com/ahmedshaik982/EDA_On_Airbnb_Bookings_Analysis/blob/main/Airbnb%20NYC%202019.csv

## Exploratory Data Analysis
The dataset has 48895 rows and 16 columns
* id - Unique id of listing
* name - Name of the listing
* host_id - Unique id of host
* host_name - Name of the host
* neighbourhood_group - Location
* neighbourhood - Area
* latitude - Latitude of listing
* longitude - Longitude of listing
* room_type - Type of rooms
* price - Price of listing
* minimum_nights - Minumum number of nights people stay
* number_of_reviews - No. of reviews given for listing
* last_review - Latest review given for listing
* reviews_per_month - No.of review given per month
* calculated_host_listings_count - Total No. of listings for host
* availability_365 - No. of days listing available
Out of 16 features, only 7 features are numerical features and remaining are categorical features.

## Approach
![image](https://user-images.githubusercontent.com/117965293/209427425-8219e16b-5547-4c04-96eb-70e03ce3ba5b.png)
## Tools used
* Google colab notebook
* Pandas library
* Numpy
* Matplotlib and Seaborn for data visualization

## Some Visualizations
![image](https://user-images.githubusercontent.com/117965293/209428021-c14bd605-2ef2-48a1-baa5-69d4ac56fb36.png)

## Conclusions
From the Exploratory data analysis, we can conclude that

* Most people are prefering Manhattan and Brooklyn, and the least is Staten Island

* The areas with most number of listings are ['Williamsburg' 'Bedford-Stuyvesant' 'Harlem' 'Bushwick' 'Upper West Side'

"Hell's Kitchen" 'East Village' 'Upper East Side' 'Crown Heights' 'Midtown']

* Most people are prefering Entire home/apt followed by Private room and least is Shared room

* The price of listings are mostly in the range of 0 to 1000 and a few listings are in range of 1000 to 10000

* The number of listings with price less than 1000 are 48619

* The number of listings with price more than 1000 are 239

* Manhattan area has the highest average price and the least is Bronx

* Entire home/apt has highest average price than others

* Manhattan has the high count of listings and the least is Staten Island.

* Brooklyn has the highest number of reviews and the least is Staten Island

* Entire home/apt has the highest number of reviews

* Manhattan has more night stays and the least is Staten Island

* Entire home/apt has more night stays and the least is Shared room

* The top hosts with most number_of_reviews are Dona, Maya, Carol, Danielle, Asa, Wanda

* The top hosts with most minimum_nights are Genevieve, Glenn H., Angie, Meg, Aliya, John, Laura, Amanda, Meg, Shining

* The top hosts with most price are Kathrine, Erin, Jelena, Olson, Amy, Matt, Rum, Jessica, Sally, Jack

* The top host with most calculated_host_listings_count are Sonder (NYC).

* The busiest hosts are Blueground, Sonder (NYC), Kara, Michael, Jeremy & Laura, Sonder, Corporate Housing, Ken, Kazuya, Pranjal

* There are total of 1294 listings that are available for 365 days.

* The shared room category has availability of rooms with more number of days

* Staten Island has availability of rooms with more number of days
