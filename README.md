# citi-bike-analysis

![citi-bikelogo](citibike%20image.png)

## Process/Analysis
For Module 18, Tableau was used to visualize New York Citi Bike data.

Analysis of the citi-bike data, started with downloading the data from the citi-bike data files and creating a dataframe file in visual studio code (vsc) to get a .csv file.  I chose to use March as a starting point and collect the data from each year 2014, 2015, 2016, 2017, 2018, 2019 and 2020.  Originally I wanted to get a look at pre-covid vs. current day, but the files of data were quite different from 2020 to 2021 and beyond.  Even with the years I selected, 2015 had to be manually manipulated to get the dates in a comparable format.  2016 also had date issues, but I was able to correct that within my jupyter notebook.  Once the data was formatted and cleaned to use, I created the dataframe and output the .csv file as 2014thru2020.csv  

Reviewing the data, I created the map of start stations and end stations.  I created bar charts of the 15 most freqently used start and end stations.  I created a line chart that shows at the peak riding hours during the month of March and shows an increase in rides around the 7 am and again around the 5pm hour.  This suggests that customers are using the citi-bikes for morning and afternoon/evening commutes! 

I created a line chart showing how many trips were taken in citi-bikes in March each year 2014-2020.  In general, the trend in ridership increased over time with a minor dips in 2015, 2017 and 2020.

I created a line chart displaying trips per day during the month of March for 2014-2020 and it shows that the 9th of the month is peak riding day and the 21st of the month is the lowest ridership.

Digging further into the data, I took a look at the ride duration of long vs short rides for bike ids.  I found that bike id 16777 had the longest duration/most rides among all of the bikes.  I mapped out where it ended its routes and the distance 16777 has travelled during each year from 2016 to 2020.  It shows that 16777 has become increasingly popular and may need to be pulled out of the rotation for maintenance in the future due to its frequent and long use.  Thank you for your service citi-bike 16777!


Data was collected for years 2014-2020 from: https://www.citibikenyc.com/system-data 

## Credits
I used the red-green diverging color theme throughout the visualizations. 

Thank you to tutor, Limei Hou, who helped me with figuring out how to get the data cleaned in my jupyter notebook in order to export as a .csv file.

Thank you to Hunter Hollis, instructor, and TA's Randy and Sam.