# surfs_up
Module 9
Advanced Data Storage and Retrieval with Jupyter Notebook, SQLite and SQLAlchemy

## CHALLENGE OVERVIEW

This research examines how Advanced Data Storage and Retrieval may be used to efficiently construct a temperature trend analysis in Oahu, Hawaii. In particular, summary statistics of temperature data for the months of June and December were needed in order to establish whether a potential surf and ice cream shop might operate year-round rather than seasonally.

DATA SOURCES AND FEATURES

* Data Source: hawaii.sqlite
* Programming Files: climate_analysis.ipynb, SurfsUp_Challenge.ipynb
* Data Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper, pandas, numpy
* Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

## Challenge Deliverables

* Deliverable 1: Determine the Summary Statistics for June 
* Deliverable 2: Determine the Summary Statistics for December 
* Deliverable 3: A written report for the statistical analysis (README.md)

## Results

* Temperatures in June vs. December (Summary Statistics DataFrame)

![june_temp_summary_stats](https://user-images.githubusercontent.com/93852380/149631625-cf8c947c-1a9c-4f27-8e43-cdac191bc5dc.png)   ![dec_temp_summary_stats](https://user-images.githubusercontent.com/93852380/149632871-0a29091a-c06e-40a7-9e3c-fd9d4406b582.png)


* June and December Recorded Temps Visualization (Temperature and Frequency)
* ![June_temps_hist](https://user-images.githubusercontent.com/93852380/149632975-ed652a17-cd53-41b3-ba08-f388b3dd77e1.png)  ![December_temps_hist](https://user-images.githubusercontent.com/93852380/149632981-be0e283d-5a03-4331-95c0-8900ed1ce0a5.png)


## Key Weather Differences: Oahu, Hawaii

* In June, the average recorded temperature is around 75 degrees Fahrenheit, which is 4 degrees higher than the average temperature in December.
This corresponds to a -5 percent drop in average temperature between June and December.
* The frequency of temperatures reported in June has a far more typical, tight bell curve distribution, which is backed up by the fact that the standard deviation of June temperatures is lower than that of December temperatures.
* Given the broader range of observed temperatures, December temperatures appear to be more volatile than June temperatures (comparing the max vs min temp of each month)
When we look at the plotted distribution of December temperatures, we can see that the median temperature is closer to the average, and there aren't as many outliers skewing the average temperature higher or lower than the actual recorded frequency.

# Summary
* To summarize, despite the fact that December temperatures appear to vary more than June temperatures, December would still provide suitable weather for both surfing and ice cream demand. The average temperature difference between June and December is only 4 degrees, and looking at the December histogram gives me more confidence in my decision—median December's temperature, with the highest frequency recorded over a period of years, is about 72 degrees, more than double the frequency of the next highest recorded temperatures, 75 and 67 degrees, respectively. It would be a bad idea to close the surf and ice cream shop because of the low temperatures at the start of the season.

 
