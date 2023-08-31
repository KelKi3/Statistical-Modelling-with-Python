# Final-Project-Statistical-Modelling-with-Python

## Project/Goals

The objective of this project is to enhance and apply Python skills by actively engaging with data from APIs like Yelp, Foursquare, and CityBikes. Through this process, the intention is to collect, clean, and transform the gathered data into a structured database. This database will serve as a foundation for uncovering statistical trends and comprehending the outcomes produced by the developed statistical models.

## Process

1. Conduct research and assess the selected APIs to request and acquire the necessary data from them.
2. Navigate through and parse the JSON files received from the APIs into manageable data frames using Python. During this process, become acquainted with the dataset and ensure that data cleaning is performed.
3. Perform exploratory data analysis (EDA) on the data frames, incorporating visualization techniques to uncover potential patterns within the dataset.
4. Build a regression model and identify insights from the results.

## Results

### API Coverage
- Foursquare's API generated a more extensive range of unique values across the dataset in comparison to yelp. I found some of their features, such as the 10-point rating scale, to be superior for data comparisons compared to Yelp's 5-star approach. It is also worth noting that some of yelps features for their API were only available through a paid 'premium access tier'. Over all Foursquare was my prefered source of data. You can read more here.

My intial thoughts entering into this project is that there would be a higher number of bicycles at a station surrounded in venues with higher ratings and a shorter distance from the bike station. While the R-squared numbers and low p-values make this model look promising to show a connection between the average distance, and average rating and the number of bikes. The failure of assumptions such as normality of residuals and homoscedasticity suggests that the model might not be capturing the true underlying relationships accurately. Ultimately, a more thorough analysis involving further data collection would be beneficial to ensure reliable findings.
 
 ### Model Results
![Number of Bikes, Average Rating, Average Distance Results](/images/bikes,rate,distance results.png)

## Challenges 

1. Obtaining the desired information from the APIs was not straightforward. The available information was overwhelming and the instructions for obtaining the specific information was not always easy to follow. After some trial and error, the data returned was still not what was expected.
2. The restrictions on the data retrieval from the APIs often led me to question the potential accuracy of my comparisons and models.
3. Using the venue category information proved difficult. It was not consistant between the two sites, and the chosen descriptive terms seemed arbitrary and unusable at times.
4. Working with so many interconnected notebooks was a challenge. There were many instances where I would change one thing and it would cause other things to not work. There was a lot of going back and forth between all the notebooks to make sure everything was consistent.
5. Made so many models trying to find one with a good fit. 

## Future Goals

Given additional time and a greater availability of API tokens, I would have aimed for a more extensive and comprehensive dataset to build my data frames from. With a larger dataset and a deeper understanding of Python and statistical modeling, I could have explored other avenues for this project. For instance, I would have investigated the correlation between the number of bikes and the time of day, a factor potentially pertinent to individuals using bikes for their daily commute. This analysis could encompass additional variables like population density, proximity to transit stations, and operational hours of various venues in order to obtain insights into these factors and their impact on bike usage patterns.
