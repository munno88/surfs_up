# Surf's Up
![surf'sup](https://user-images.githubusercontent.com/103727169/182683054-a02038bf-1bbc-4a94-bc87-6e31e7d9dd5a.png)

Surf's Up with Advanced Data Storage and Retrieval

## Purpose :

1.	Explain the structures, interactions, and types of data of a provided dataset.
2.	Differentiate between SQLite and PostgreSQL databases.
3.	Use SQLAlchemy to connect to and query a SQLite database.
4.	Use statistics like minimum, maximum, and average to analyze data.
5.	Design a Flask application using data.

## Overview:

An investor wants to learn more about the weather before committing to build a Surf and Ice Cream shop in Oahu, Hawaii. The investor's main concern is the precipitation forcing the shop to close too frequently. To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.

## Results:

### June Statistics for the Temperature :
![june_temps](https://user-images.githubusercontent.com/103727169/182663348-634b7510-b306-47e0-8cf6-7085af711c66.png)

### Decembr Statistics for the Temperature :
![dec_temps](https://user-images.githubusercontent.com/103727169/182663400-8d590901-b279-48b5-acb1-b97bfc4dd232.png)

### June Statistics for the Temperature and Precipitation:
![june_temp_precip](https://user-images.githubusercontent.com/103727169/182663473-2928d025-f74f-41cb-8ccd-0a861b8db9fc.png)

### December Statistics for the Temperature and Precipitation :
![dec_temps_precip](https://user-images.githubusercontent.com/103727169/182663522-669aa3a7-2dc1-4382-9bde-cc1727be9147.png)

The mean temperature of 75°F for June is higher than the mean temperature of 71°F for December. However, the opposite is true for precipitation. December had the higher precipitation of .22 inches while June had .14 inches.

![june_temps_graph](https://user-images.githubusercontent.com/103727169/182663591-3fab2db3-3145-4c9b-b304-8c1e63cf83d1.png)

![dec_temps_graph](https://user-images.githubusercontent.com/103727169/182663635-237e6fde-b11c-465a-af76-5ac5551e34c6.png)

 
## Summary:
The investor's main concern was getting rained out too frequently. Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close. The temperature data is not strongly skewed for either month. The ratio of the temperatures to the precipitation for the two months is also reasonably similar. The data supports opening a Surf and Ice Cream shop year-round.

