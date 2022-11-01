# surfs_up
Tools used: SQLite, Python

# Overview of the analysis: 
In this project, I analyze the feasibility of a surf and ice cream shop in Oahu, Hawaii. The success of this business would be contingent on warm weather. Thus, the purpose of the analysis is to determine the weather variability in the city during the months of June and December, given 7 years of historical data, to assess if the project would be sustainable year-round. For this exercise, I use SQLAlchemy to link the SQLite database to Python. I retrieve the weather data for the months of June and July in 2 separate queries, in list format. I then use Pandas to create dataframes for both datasets and the .describe() method to generate general temperature statistics.

# Results: 
* Temperatures in June oscillate between 64F and 85F, with an average monthly temperature of 74F

!['June']!(/Resouces/June_temps.png)

* Temperatures in December oscillate between 56F and 83F, with an average monthly temperature of 71F

!['Dec']!(/Resouces/Dec_temps.png)

* Temperature oscillation isn't very brutal as standard deviation is only only around 3F

# Summary: 
To sum up, temperatures in Oahu do not get colder than 56F around the year with very little variability throughout the months of December and June. Additional queries would include the precipitation data and any other data that could be gathered in addition to the given database, for the region, such as : prevalence of natural disasters, number of tourists, and competitor information. 

