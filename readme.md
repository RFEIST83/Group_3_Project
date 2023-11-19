# Data Analytics Boot Camp - Group 3 - Project 1

## Formula 1 Race Results and Driver Performance Over The Years
 
### Group Members:

Himali Wijeratne, Alexander Hodgins, Rowan Feist, Shenae Pepper

### Description/Outline:

This project analyses Formula 1 race results and driver performances from 1950 – 2023 to gain insights into the sport. By exploring the dataset, we will identify trends, patterns, and statistics related to race outcomes, as well as evaluate the performance of individual drivers over time. Through visualizations and analysis, we will present key findings and potentially uncover interesting facts about Formula 1 history.

### Dataset Used:

[https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2023](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2023)

### Research Questions:

**Do better qualifying results contribute to a more successful race? - Rowan Feist**

Using the dataset we attempted to make find the correlation between qualifying results and final race position in a race. We did this by comparing the qualifying results 26,080 starting positions with the mean of 15,207 race finishes for 857 different drivers. By merging the datasets together to get this information we then built a scatter plot to display the results. This showed some outliers in the data but still clearly showed a correlation between the two. To confirm this a linear regression was done which provided a R-Squared result of 0.70. While not a R-Squared of 1, with the amount of data analysed and the unpredictability of a Formula 1 race this still showed a very strong correlation between the two.

![Screenshot 2023-11-19 174409](https://github.com/RFEIST83/Group_3_Project/assets/145405658/9403db5c-2ee1-408b-bc9f-0a66b2fc08d1)

Looking in to this further we decided to investigate 2 specific drivers, Alain Prost and Ayrton Senna. Building the same scatter plot and doing another linear regression with these specific drivers actually showed that despite being extremely successful they are actually outliers to the rule with a R-Squared of 0.13 and 0.06 respectively. 

![Screenshot 2023-11-16 212814](https://github.com/RFEIST83/Group_3_Project/assets/145405658/55b17064-a985-444c-8257-18f486e6d2c2)

Building a bar plot to look specifically at all there qualifying and race results you can see that they are almost he complete opposite of each other with Alain Prost have worse qualifying results but better at converting it in to a winning result Ayrton Senna is better at qualifying while not as good at turning it in to a win.

![Screenshot 2023-11-16 193628](https://github.com/RFEIST83/Group_3_Project/assets/145405658/600ac901-77b1-4c63-bbdd-d2883ff6a869)

From looking at all the data for this particular question we can see that while there is definitely a very strong correlation between qualifying and final race results there are some exceptions to the rule which also happen to be some of the most successful drivers of all time. While qualifying on pole is always best thing you can do to maximise your race results it’s not always necessary.

**Are there any correlations between certain driver characteristics and race results? - Shenae Pepper**

Looking at the data we attempted to find if there was any correlation between a drivers character and their race results. Two things that were looked at specifically are a drivers nationality and age. With nationality we created a bar plot to compare the nationalities of 857 different drivers with their average fastest times. What this showed that of all the drivers Colombians had the fastest average times while on the opposite end of the spectrum Americans had the worst.

![Screenshot 2023-11-19 180239](https://github.com/RFEIST83/Group_3_Project/assets/145405658/d4b2c852-859a-4843-9a96-058d7e3cb700)

Doing the ANOVA and T-Test on these results showed a p-value of 2.75 which showed the average fastest times between the two nationalities is statistically significant. Doing a Pearson correlation coefficient of 0.44 which indicates a moderate positive correlation. As the nationality changes, there is a tendency for the average fastest lap time to increase, but the relationship is not extremely strong. It suggests a moderate strength, meaning there is a discernible trend, but it's not as strong as a perfect correlation

With age we took date of births of each of the 857 drivers throughout the history of Formula 1 and calculated what their age would of been at the time of each race. We then plotted this on a scatter graph comparing the age to the their average fastest times. 

![Screenshot 2023-11-19 182551](https://github.com/RFEIST83/Group_3_Project/assets/145405658/27a52bd2-e50f-452b-8ca0-ca08785639fc)

We then completed another Pearson correlation coefficient which showed a correlation coefficient of 0.18 which indicates a weak positive correlation between age and average fastest lap time. The data showed that between the ages of 26 and 34 would be the age that results in the fastest time you can also see that as you get older the faster the times become and then declines again as you get older again which shows experience does play a part in achieving success but only up to a certain point.

**Has the evolution of pit stops effected constructors results? - Alex Hodgins**

To investigate how the changes in times of pit stops have effected constructors results we first built a scatter plot for the average pitstops across all constructors who raced in the seasons from 2011 to 2022. The cluster of datapoints shows the average times and the outliers. The outliers below the average show the teams who excel in pitstops and the outliers above the clustered average shows which teams do not excel in pitstops.

![Screenshot 2023-11-20 090118](https://github.com/RFEIST83/Group_3_Project/assets/145405658/dd2c5c18-f818-42de-ba2b-cad0c13fe48a)

We then decided to make a bar plot, upon review the years where new rules and car designs were introduced appear to have greatly effected pitstop times. An R-squared value closer to 0 indicates that the linear regression doesn't explain much of the variance in the Pitstop Time. A higher standard deviation also means that the data points are spread out over a wider range from the mean value. These results reflect the potential changes in both rules and cars and how they have effected pitstop times. Some notable changes were Teams were allowed to use both dry and wet tires during races, and they had to make mandatory pit stops to use both compounds in a race. Pirelli introduced wider tires (front and rear) in 2017 to provide more grip and increase the speed of the cars. Teams were given a choice of multiple compounds (ultrasoft, supersoft, soft, medium, hard, etc.) for each race weekend, and they had to use at least two different compounds during the race. Formula 1 introduced 18-inch tires to replace the 13-inch tires, marking a significant change in the tire size.

![Screenshot 2023-11-20 090253](https://github.com/RFEIST83/Group_3_Project/assets/145405658/6947acb6-0f23-4546-b8ef-02f226d11d42)

Finally we decided to look at if faster pit stop times equalled more points for a particular constructor. We did this by choosing two constructors over a single year to looks at. We choose both Wiliams and Mercedes from the year 2011 and plotted this on a bar graph. 

![Screenshot 2023-11-20 090311](https://github.com/RFEIST83/Group_3_Project/assets/145405658/1dbbdc81-fae5-423d-b620-105d175b42a3)

Using the dataset we identified Williams as a constructor with the fastest pitstop time of 2011 and compared their time with the Mercedes team. Their average pitstop time is very similar but Williams fastest pitstop time is quicker than Mercedes

![Screenshot 2023-11-20 095850](https://github.com/RFEIST83/Group_3_Project/assets/145405658/8694b4a9-2d09-40a0-aef7-54a44c5c3bac)

On a second bar graph we plotted points earned in the same season and compared that to pitstop times. Although Williams may have had faster pitstop times it doesn't result in their points tally being similar. As we can see Mercedes accumulated more points over the 2011 season.


