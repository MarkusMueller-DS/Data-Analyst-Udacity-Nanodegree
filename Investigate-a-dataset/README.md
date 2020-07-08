## Investigate-gun-permits
##### by Markus Müller

This analysis is part of the second project of the Data Analyst Nanodegree on Udacity.

The goal of this project is to go through the data analysis process and see how everything fits together.

In this notebook I will analyse the FBI NICS Firearm Background Check Data from 1999 till 2017 using Numpy, pandas and Matplotlib. 
More infos on the FBI NICS Firearme Background Check Data can be find in this <a href="https://github.com/BuzzFeedNews/nics-firearm-background-checks/blob/master/README.md">repo</a> and on the offical <a href="https://www.fbi.gov/services/cjis/nics">FBI</a> website.

I also used US Census data to look at per capita values for gun backgrund checks, which was provided by Udacity, and can be found in my repo.

### Final Conclusion

The overall trend of background cheks is positive and there is a high seasonality associated with it. Especially in december and march, which is most likely due to the holidays in december and the warmer temperatures in march. Generally there was an annual compound groth rate (CAGR) of 6% over the last 17 years in background checks (1999-2016). Looking at the estimated gun sales the expected seasonality was replicated but with higher mean gun sales in the winter months, which support my conclusion that people buy guns as presents for chtistmas. Inspecting the total gun sales in the analyzed time period (1999-2018) Texas, California, Pennsylvania and Florida had each over 10 million gun sales with the most sales in Texas (16 Million). In the last questiom I analyzed the gun sales per capota ratio in 2016. In that year Alaska, South Dakota, West Virginia and Montana had each over 10% of their popualation as gun sales, with the highest rate in Alaska where gun sales take 11.7% of the popualion.
Tha analyzed data had some limitations, which were taken care of in some aspects like the drop of unfinished years in the data, but other limitations like the gun sales estimates are still limited and should not be taken as 1:1 correlation with real gun sales. Therefore each calculation involving the estimated gun sales should be viewed critically.

### Files
- Investigate_gun_permit.ipynb: Jupyter Notebook with python code
- U.S. Census Data.csv: Dataset with US Census data
- nics-firearm-background-checks.csv: Dataset with the background check data from th FBI
