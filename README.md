# surfs_up


## Overview of the analysis:

Explain the purpose of this analysis.
I am planning to open a Surf and Shake shop in Oahu. W. Avy, a potential investor has requested I analyze weather datasets to ensure the surf and ice cream shop will be sustainable. I will be using Python, Pandas, and SQLAlchemy to analyze a weather dataset for Oahu. In this challenge, I will specifically analyze the temperature data for the months of June and December in Oahu to determine if the surf and ice cream shop business is sustainable year-round. 

#### Deliverable 1: Determine the Summary Statistics for June

Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

![img1](https://github.com/Soniaprogram/surfs_up/blob/main/images/del1.PNG)

***Summary Statistics for June Temperatures***

#### Deliverable 2: Determine the Summary Statistics for December

![img2](https://github.com/Soniaprogram/surfs_up/blob/main/images/del2.PNG)

***Summary Statistics for December Temperatures***

Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. I then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

## Results:

Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.
- The mean temperature in June is 74.9 degrees Farhenheit which is relatively warm, indicating that the business would be sustainable in this month
- The mean temperature in December is 71.0 degrees Farhenheit which is also warm, indicating that the business would be sustainable in this month
- The min temperature for June was 64 and the min for December was 56. These are slightly chilly, however, still within the range of what would be considered sustainable.

## Summary:

Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
In summary, based on the temperatures in June and December over all the years, it seems promising that the business would be sustainable all year-round. It would be beneficial to query precipitation in June and December as well to see how rainy it gets. It would also be advantageous to 
