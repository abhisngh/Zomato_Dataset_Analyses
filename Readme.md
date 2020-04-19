# Zomato Funding
This Project is for the Analysis Purpose where the Dataset is provided with some questions and that need to answer from the
the same Dataset.

# Dataset
Due to Zomato API Basic Plan restriction, we cannot collect enough data for analysis. To overcome this problem ‘Zomato.csv’ file is provided to analyses the data deeply and to get useful inference.
Data has been collected from the Zomato API in the form of .json files(raw data) using the following url and stored in CSV file -
https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20

1.Restaurant Id : Unique id of every restaurant across various cities of the world
2.Restaurant Name : Name of the restaurant
3.Country Code : Country in which restaurant is located
4.City : City in which restaurant is located
5.Address : Address of the restaurant
6.Locality : Location in the city
7.Locality Verbose : Detailed description of the locality
8.Longitude : Longitude coordinate of the restaurant's location
9.Latitude : Latitude coordinate of the restaurant's location
10.Cuisines : Cuisines offered by the restaurant
11.Average Cost for two : Cost for two people in different currencies
12.Currency : Currency of the country
13.Has Table booking : yes/no
14.Has Online delivery : yes/ no
15.Is delivering : yes/ no
16.Switch to order menu : yes/no
17.Price range : range of price of food
18.Aggregate Rating : Average rating out of 5
19.Rating color : depending upon the average rating color
20.Rating text : text on the basis of rating of rating
21.Votes : Number of ratings casted by people

| Country Code | #1 | #14 | #30 | #37 | #94 | #148 | #162 | #166 | #184 | #189 | #191 | #208 | #214 | #215 | #216
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | | :---: | | :---: | | :---: |
| Country | India | Australia | Brazil | Canada | Indonesia | New Zealand | Philippines | Qatar | Singapore | South Africa | Sri Lanka | Turkey | UAE | United Kingdom | United States

# Install
Supported Python version
     - Python version used in this project: 3.5+

# Libraries used
      Pandas 0.18.0
      Numpy 1.10.4
      Matplotlib 1.5.1

# Code
The code used in this project is inside Zomato_analyses.ipynb.

# Run
To run this project you will need some software, like Anaconda, which provides support for running .ipynb files (Jupyter Notebook).
After making sure you have that, you can run from a terminal or cmd next lines:
ipython notebook Zomato_analyses.ipynb or jupyter notebook Zomato_analyses.ipynb
