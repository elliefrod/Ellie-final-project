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

I did statistical analysis in the rest of my project, but there were three descriptive statistics that I wanted to highlight. To make some of my analysis cleaner, I used my "hd" data set and then made two new data sets as well. I made a set called "ninety" where it was just the data from 1990. I also made a set called "twentyone" where it was only data from 2021. This helped me to look at differences in patterns across that 30-year period. For examples, the coefficient for human inequality mean was 23.204339	in hd, null in ninety, and 21.770279 in twentyone. This probably explains that the inequality coefficients were not calculated for a couple years after 1990!

DATA VIZUALIZATIONS

For statistical analysis and visualizations, I formatted my understanding into 5 categories: 

1. Human Development Index (HDI) over time 

I tried to look at different aspects of changed from HDI over time. For example, I made histograms of the ranks of HDI in 1990 and 2021. I also looked at the change in HDI over time. Additionally I examined the best and worst regions for HDI in 1990 and 2021. Here is a histogram of HDI in 2021: 

<img width="563" height="455" alt="histhd" src="https://github.com/user-attachments/assets/fe83e286-4d7a-4818-9bbb-53bb43379f05" />

2. Life expectancy and health

I looked at the trends of average life expectancy from 1990 and 2021. There was a dip in the last two years of the data set, which made me curious about if that was related to covid. I also looked and there was a consistent decline in life expectancy and a change in overall loss for those two years as well. My final visualization was the correlation between average life expectancy and overall loss, which ended up being a weak correlation. 

Here is the trend of average life expectancy over time: 

<img width="563" height="455" alt="image" src="https://github.com/user-attachments/assets/814323b5-3f57-4f6c-abca-75f931781ed7" />

3. Education and income

For education and income, I first looked at the different regions and their average years of schooling. Here is that bar chart: 

<img width="562" height="534" alt="image" src="https://github.com/user-attachments/assets/87a91a37-5443-4f7e-ab6a-a97f14b263e5" />

Additionally, I also wanted to narrow down my search to see which countries had the lowest on average amount of schooling through 1990-2021, and who had the highest average amount of schooling. Finally, I looked at Guniea, who had the highest inequality in education index average. I decided to look at that inequality throughout 1990 to 2021. Here is that line chart: 

<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/be7e882c-8878-48ce-b889-b223e05f3e59" />

4. Gender inequality and human development

For my main graph in gender inequality, I made a bar chart that seperated male and females and their labor force participation per region. I also made a line chart of the gender inequality index throughout time. Here is that labor force bar chart: 

<img width="1590" height="690" alt="image" src="https://github.com/user-attachments/assets/622361d8-74a6-451f-a18a-8874d00a9d30" />

5. Environmental impact and sustainable development

My final analysis was on environmental impact and sustainable development. To do statistical analysis, I looked at what country had the worst carbon emissions per capita on average. After finding out that information, I wanted to see more. I made a bar chart of the top 15 countries that had the highest amount of carbon emissions per capita on average. Here is that bar chart: 

<img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/f99c9fe0-8647-49bc-b2eb-b74b19d49d3f" />

Finally, I wanted to see the correlation between carbon emissions per capital and material footprint. The r value ended up being 0.64, which is a medium strength correlation. Here is that scatter plot:

<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/4b015e65-6465-4068-b0d0-8fd0f4798aea" />

I loved this dataset. Even though it was a huge one to start off with, it was really interesting to analyze. There are so many variables in this data set, so I could have made 100 more statistical analyses and graphs, but I didn't have the time. I love human development studies!
