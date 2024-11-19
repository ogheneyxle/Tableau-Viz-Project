# Tableau-Viz-Project

## Table of Content

## Project Overview
In this project, we explored data from the AirBnB industry in Seattle, Washington State, USA. Through our exploration, we were able to isolate trends indicative of what areas one might either invest in or book a stay. 

## Data Sources
AirBnB Data: The primary data source for this tableau project is the "TableauFullProject.xlsx", which holds the data on the AirBnB apartment types, customers, reviews, amongst other information.

## Tools
- Microsoft Excel
- Tableau Public

## Data Preparation
Owing to fact that our data source is an ".xlsx" file, we first had to clean it using the most appropriate application for it, Microsoft Excel. Upon reviewing the data, there wasn't much cleaning to be done, so we could load it onto Tabluea Public for the dashboard creation.

## Data Analysis
As part of this data exploration project, we set out to answer certain questions whose answers would best inform potential newcomers to the market, customers and even investors on how to proceed. Our analysis involved the following queries;
- What is the average price per zipcode?
- What is the average price per bedroom?
- What is the number of rooms per listing?
- How much revenue was generated over the course of one year (2016)?
Before we set about answering these questions using Tableau, we first had to join the two columns (called 'tabs' in tableau) that truly held the data we needed for this analysis; 'Listings' and 'Calender'.
Note that the kind of join in use here is a left join based on the 'Id (Listing) = Listing Id (Calender)'.

## Results
Below are the results from our analysis;
- What is the average price per zipcode?
Answer: ![Screenshot (5)](https://github.com/user-attachments/assets/acefd9d0-17fd-454e-9a21-96b68a2ee956) , ![Screenshot (6)](https://github.com/user-attachments/assets/6ad5013c-8bd0-4257-9a17-5cb75ea2d123)
Here you can see that the highest average cost for an apartment is $206.6 in the 98134 zipcode, while the lowest is at $64.7 in the 98125 zipcode.

- What is the average price per bedroom?
Answer: ![Screenshot (8)](https://github.com/user-attachments/assets/52e0545f-6b50-4473-9bee-01f2c4b68b99)
We can see that the average 6 bedroom cost $584.8, while $96.2 will get you a 1 bedroom on average.

- What is the number of rooms per listing?
Answer: ![Screenshot (9)](https://github.com/user-attachments/assets/e18f121f-62a1-474f-9d06-57851ea24b68)
This visualization shows that there are more one bedroom apartments in the listing (1811) in comparison to six bedroom apartments (5).

- How much revenue was generated over the course of one year (2016)?
Answer: ![Screenshot (7)](https://github.com/user-attachments/assets/c4d0a8dd-33d3-4e45-a719-6647738e8796)
This graph shows that owners can make the most money during december, as the uptick shows the year ending with $2,110,350 in revenue.

##Recommendations
Judging from the data and our findings;
- The best times to put your apartment up for use as an AirBnB apartment would be June and December.
- Try to book apartments with 2 and 3 bedrooms listed, they cost less on average and have a higher availability all year round.

## Limitations
To truly get a picture of the apartment quality, we would have to do a lot of cleaning as the customer reviews are not standardized and thus inconclusive. The incoherent id listing as well would present some trouble if you wanted to link any review with the apartment getting reviewed.

🃏
