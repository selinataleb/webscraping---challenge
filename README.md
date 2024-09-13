
The goal of this project is to use Python and web scraping techniques to extract, analyze, and visualize data from Mars-related websites. This project is structured into two Jupyter notebooks
Part 1 focuses on scraping news data from the Mars news website 
Part 2 focuses on scraping and analyzing the Mars weather data. 


PART 1: SCRAPE TITLES AND PREVIEW TEXT FROM MARS NEWS 

We used automated browsing to visit the Mars news site. We began by creating a Beautiful Soup object and used it to extract all the text elements from the website. 
Then we scrape the Mars news titles and their previews. The purpose was to extract the latest headlines and preview texts from Mars-related news. 

PART 2: SCRAPE AND ANALYZE MARS WEATHER DATA 

This part is centered on scraping and analyzing Mars weather data collected by NASA's Curiosity rover. 
Our first step we visit the website, then we crape the table by creating a beautiful soup object and extracting the rows from the data. Moving on, we store the data into a Pandas DataFrame. 

ANALYZING THE DATA

There are 12 months on Mars.
There are 1867 sols (Martian days) worth of data. 

We calculated the average minimum temperature by month and plottted a bar chart. This allowed us to identify the hottest and coldest month. 
Month #8 is the hotttest with an average temperature of -68.382978 Degrees Celsius 
Month #3 is the coldest with an average temperature of -83.30729 Degrees Ceslius.

Following that, we calculate the average pressure by month and plotted a bar chart to represent the results. We found that:
The highest pressure is in month # 9 with an average pressure of 913.3059701492538 
The lowest pressure is in month # 6 with an average pressure of 745.0544217687075 

Year Length
We plotted a graph first and used the peak-to-peak method in the graph to get the number  of days in a full Martian Year. Peak-to-Peak represents the max temperature. From the graph, we identified 150,800, and 1500 terrestrial days to be the highest points in the cycle. 

Then we got the difference between 800 and 150 which is equivalent to 650 days, and between 1500 and 800 which is equivalent to 700 days. Averaging both these values we got 675 days. 

After looking on the Website, Martian days are called sols – short for "solar day." A year on Mars lasts 669.6 sols, which is the same as 687 Earth days.
We can conclude that we are close to the actual 687 Terrestrial Days in a Martian Year.
