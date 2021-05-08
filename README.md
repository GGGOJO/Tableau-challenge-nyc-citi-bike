# Tableau-challenge-nyc-citi-bike
Tell a Data Story Using April 2021 New York City (NYC) Bike Share Data in Tableau

Using the Desktop version of Tableau (trial period), I used the NYC citibike trip data (public data https://www.citibikenyc.com/system-data) from April 2021, the most recent data made available. The csv file is over 138MB, but Tableau was able to process and load it quickly. 

The data file has the following: 
* Trip Duration (seconds)
* Start Time and Date
* Stop Time and Date
* Start Station Name
* End Station Name
* Station ID
* Station Lat/Long
* Bike ID
* User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
* Gender (Zero=unknown; 1=male; 2=female)
* Year of Birth

There is also data for Jersey City (JC), which I learned about through the Google Group (https://groups.google.com/g/citibike-hackers/about) that plays with this data. I suppose that the main page that houses the data should have made that clarification in the first place. It's not clear why it is not. 

Tableau is super fun and easy to create fast visualizations, dashboards, and storyboards. However, there are concerns about the price and why the Microsoft BI is a strong rival, but I digress. 

The major takeaway is NYC Citi Bike program appears to be growing strong. If I had more time, I would have looked at the first data file made public (2013) to compare the number of shared bikes then compared to now. I looked at the Google Group and it seems that 2013, there were not as many bike stations in the outskirts of Manhattan or other boroughs. 

I would say that data cleaning is a must with this data. Subscriber data provides more detailed data on gender and date of birth compared to Customer data. However, the Subscriber data had some questionable data where riders were born in the 19th century!
