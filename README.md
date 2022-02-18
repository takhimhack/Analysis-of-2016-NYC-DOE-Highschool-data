# Please read [report.pdf](https://github.com/takhimhack/Analysis-of-2016-NYC-DOE-Highschool-data/blob/main/report.pdf)for a more in-depth analysis 
### Project [Notebook](https://nbviewer.org/github/takhimhack/Analysis-of-2016-NYC-DOE-Highschool-data/blob/main/takhimh_mmraja.ipynb).
**Abstract**

Yearly, the statistics released for high school graduation and college enrolment in New

York City show that graduation is a big hurdle for most high-school students. While the

challenges may vary, these statistics pale in comparison to NYC's status as one of the

world's wealthiest cities. This report details our study into the blurry lines behind these

statistics. With the aid of various Machine Learning models, we were able to test several

hypotheses to understand the reality of these challenges and draw up possible ways to

solve them. Our findings point out social mobility as one primary reason for the

challenges, and we believe that the provision of incentives can positively contribute to

solving these challenges.

**Introduction**

**"Every year, thousands of students in New York City struggle to graduate high**

**school."**

The above statement may be subject to varying debates for and against the perception

that graduating high school in New York City (NYC) is a challenging ordeal. To get a clear

picture of the reality of thousands of students in New York City, we decided to study the

available facts. We focused on getting the exact figures, and we explored how they

correlate with the challenge highlighted in the above quote.

Hence, this report covers our research and analysis of the graduation rate in New York

City on a per-school basis, and it simultaneously covers our analysis of the graduation

rates within each Borough.

We believe that this approach will help us and the readers understand any school's

performance within a given Borough. In addition to this, we also took an interest in

comparing different Boroughs' performance in terms of high school graduation and

college enrollment. Moreover, we hope that our results will highlight the problems

affecting students' graduation rates within the Boroughs where they are located.


**Inspiration for the project: https://opendata.cityofnewyork.us/projects/data-visualization-of-nyc-high-schools-college-enrollment**

**Name of our data:**

• 2016 NYC High school directory

• 2016 NYC High school performance

• 2016 income by zip code for NYC

**Background:**

• Source 1[:](https://data.world/)[ ](https://data.world/)<https://data.world/>

• Source 2[:](https://guides.newman.baruch.cuny.edu/nyc_data/nbhoods)[ ](https://guides.newman.baruch.cuny.edu/nyc_data/nbhoods)<https://guides.newman.baruch.cuny.edu/nyc_data/nbhoods>

• Source 2[:](https://data.census.gov/cedsci/)[ ](https://data.census.gov/cedsci/)<https://data.census.gov/cedsci/>

• Time Period: 2016

• Scope (if there is, please specify): New York City

• Data Unit: Statewide

**Hypothesis and conclusion**

• The Borough of Manhattan will perform better in terms of graduation rate than other

Boroughs.

• The Borough of Bronx will perform worst in terms of graduation rate than other

Boroughs.

• A higher graduation rate varies directly to a wealthy neighborhood, i.e., a wealthy

neighborhood will have a higher graduation rate, while a poor neighborhood will

have a low graduation rate.

• There is a direct relationship between geographical locations and their high school

graduation rate.

• There is a direct relationship between geographical locations and their college

enrollment rate.


**Libraries used**

• Pandas

• Numpy

• Seaborn

• Matplotlib

• Folium

• Requests: HTTP for Humans™

• Google maps sdk


**Conclusion & Recommendation**

From our EDA Analysis, we can infer that our hypothesis about the Borough of Manhattan

will perform best in terms of high school graduation rates, and this will remain true

irrespective of the Borough under comparison to it. However, our hypothesis that

suggests that the Borough of Bronx will perform worst in terms of graduation rates was

wrong.


The proviso for these inferences rests heavily on our skewed data, which does not feature

graduation rates for all schools in each Borough. Some Boroughs have better

representation than others from the data we gathered. Brooklyn, for instance, was

represented by 107 schools, the Bronx was represented by 99 schools, while 86 schools

represented Manhattan. Sixty-seven (67) schools represented Queens, and ONLY TEN

(10) schools represented Staten Island. If we had an equal amount of distribution for each

of the Borough, we could have produced better results.


Our hypothesis about higher incomes and their effects on higher graduation rates was

not wholly correct. There is no direct relationship between graduation rates and median

income. Besides, our model does not yield insightful results when we use graduation rate

as our only variable. We had to add more variables such as Borough, Zip code, and its

relative Borough high school graduation rates and college enrollment rates to get good

results.


Our hypothesis about the direct relationship between a geographical location and high

school graduation rates is not entirely correct. There is undoubtedly a relationship

between geographical variables and high school graduation rates; however, this

relationship is not a direct linear relationship. As a result, our hypothesis was only partially

correct. We can also observe the impact of these variables in our important feature plots.

To get the best results for high school graduation rates, we need to add more variables

such as relative graduation rates to the Borough and college enrollment rates to get

insightful results.


Our hypothesis about the direct relationship between a geographical location and their

college enrollment rate is not correct. There is undoubtedly a connection between

geographical variables and college enrollment rates; however, we cannot perfectly say it

is a direct relationship in the same guise as high school graduation rates. If we consider

our important feature plot, the most impacted geographical location is the Borough of

Queens, which 67 schools in our data represented. To get a more accurate result, we

need to add more variables such as our relative Borough college enrollment rates and

high school graduation rates to get more insightful results.

NYC is one of the wealthiest cities in the world. According to Business Insider, there are

113 billionaires in NYC. If one is part of the top 1%, there is a good chance that they are

not sending their kids to public schools. Our data only represents NYC public schools.

One factor that is also strongly limiting is social mobility. A poor person will have a hard

time getting into the middle class. A person in the middle class will have an even harder

time getting to be part of the wealthy class. Now, amongst the wealthy class, there are

different levels also. For example, a person who is making 100k a year can be considered

wealthy; likewise, a person who makes $1 billion in one year is also wealthy.





If we examine our mapped data for college enrollment, the schools that are in the poverty

line have a hard time with college enrollments. The rich here also have low college

enrollment figures. One can infer that since they are already wealthy, going to college

does not look attractive because they know it will not help that much, but that will only

form another hypothesis for us to test. What we can confirm is that most middle-class

students are also striving to go to college.

The government can provide incentives for poor and middle-class areas so that students

can succeed no matter their financial background. We can achieve this by taxing the ultra-

rich and those who make the most money in NYC but do not pay the most tax ratio. If we

can do that, then we can provide many incentives to help poor students and middle-class

students to increase the high school graduation and college enrollment rates for their

locality.
