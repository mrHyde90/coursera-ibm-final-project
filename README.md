# coursera-ibm-final-project
## The problem
When you are a foreign student in mexico city always you need to know where rent a room to stay. sometimes you 
only will decide the cheapest room, but sometimes the cheapest is not the best solutions, because are lonely areas
without some places to relax and forget the school, or if you are a food lover you wanna rent a room near of the restaurants.
Thats the reason that we wanna analize the areas and the prices and we will check if there have any correlation and decide what
is the best room to rent

## The Data
Our data will be recolect of a housing web page called: housinganywhere. This webpage only have the price and the addres of
the room, this 2 elements will be the data that we will use. To recolect the data of this page we will use requests and 
beautifulsoup because we need to extract the data of the elements of the web page. After we will use google geocode to
convert the addres in longitude and latitude. At last we will use the latitude and longitude in foursquare to see the places
near to the room and see if there have any correlation with the price.
