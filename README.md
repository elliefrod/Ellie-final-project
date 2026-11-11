Ellie-final-project

This is my README file for my final project!

I decided to do a data analysis of the Human Development Index dataset from Kaggle. This means a lot to me because I graduated in Human Development at BYU. I did so many studies when I was a student there about the different aspects of Human Development. When I found this dataset, I thought it was the perfect use of my knowledge and to learn more about Human Development on a larger scale. 

The main limitation with the data I found was that it was only from 1990 to 2021. So I would have loved to evaluate more of that data from 2021 to 2026, but I worked with what I had. The order in which I did my project was actually data manipulation, data cleaning, statistical analysis, and visualizations. But in the end, I also combined the statistical analysis with visualizations anyway. 

DATA MANIPULATION

This was the most confusion and complex part of this project. The original Human Development dataset was 195 rows and 880 columns. That is because every type of Human Development variable that was measured was a different column for every single year. So That was impossible to read and I needed to melt and manipulate the data. I first figured out that some columns could stay the same that didn't have years assigned to them. After that I melted the dataset first so that the human development variables were put into one column. That new data set was called long_df. Once I had that long data frame, I also melted the data so that year had its own column and each type of human development variable had it's own column. That final data set was called hd. 

DATA CLEANING

Once I had the dataset I wanted to use, which was "hd", I cleaned that data. I made sure there was no duplicated values, and found that there were some missing values. While I could have imputed those missing values, I didn't think of doing that just yet. But once I looked at how many things were missing and decided which values I wanted to analyze and which were fine to leave alone. The variables with null values that I decided to fill with their medians were Inequality in education, Inequality in life expectancy, Material footprint per capita, Overall loss (%). I also looked and there were no duplicated values. 

Something else I did to clean the data was to make a Region column to correlate with every country. This was helpful for me because there were so many countries listed in the data set that It would have made it hard to see patterns as a whole. Instead, I defined every country for a specific region. I made sure the data had no missing variables or duplicates. I was cleaned! I will be showing which countries were sorted and where they were sorted into, in my google document. 

STATISTICAL ANALYSIS

I did statistical analysis in the rest of my 

DATA VIZUALIZATIONS
