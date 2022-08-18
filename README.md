# EXPLORATORY-DATA-ANALYSIS---MEDICAL-PLANS

Exploring Medical Plans data, understanding and analysing its patterns, recording beneficiaries behaviour and assesing the nature of the plans.

PROJECT OBJECTIVE :

The data set provided is a snippet of the Landscape data. It tells us how many plans, commonly known as bid id, are present in that year. It also tells us the various attributes of these plans like cost, benefits covered etc.

The following are the important variables that are closely with : 
Bid_ID  -	we use this to identify a unique plan. It may be present in multiple state counties.
plan_name - self explanatory
Organization_Name -	self explanatory
Monthly_Consolidated_Premium_C_D - this is the monthly amount a person will have to pay for their plan
Annual_drug_deductible - 	a deductible is the amount you pay before you plan kicks in. In this case you must first pay up the value here before your plans start paying for your drugs
star_rating -	how good is the plan. In an ideal world your plan is a 5 star plan
In_network_MOOP_Amount - MOOP stand for Maximum Out of Pocket. It's the max amount you need to pay from your pocket after which you plan will literally pay everything above this value.
Special_Needs_Plan_Type - This is an important variable. In short we use this to segregate plans.
plan_type -	This is an important variable. In short we use this to segregate plans.
Dec Enr -	this is number of beneficiaries enrolled to this plan the previous year December.
Jan Enr - this is number of beneficiaries enrolled to this plan the current year Jan.
Net Enr -	Jan Enr - Dec Enr. Defined as the jump in enrollments from the last year to this year.
feb enr - this is number of beneficiaries enrolled to this plan the current year Feb.

DESCRIPTIVE STATISTICS : 

•	One of the major steps to fine-tune the given data set in a different form of analysis to understand the insights of the key characteristics of various entities of the data set like column, rows by applying Statistical Methods and Data visualization packages. 

•	The given dataset is of 218960 rows and 70 columns. It contains discrete, 
 categorical and continuous variables.

•	On further analysis, it is clear that the data set doesn’t have any anomalies like 
missing values, outliers and duplicates. (Refer source code)

•	There is a high positive correlation between January Enrollment, December Enrollment and February Enrollment.

UNIVARIATE ANALYSIS :

•	The frequency count of the year 2020 is 31%, 2019 is 26%, 2018 is 22% and 2017 is 20%. The plans keep on incrementing year over year. Over all the years 2018, 2019 and 2020 shows a steady increase in plans where 2020 is in the highest position, which shows that more people are inclined towards enrolling into the plan. It proves the market sentiment is heading towards positive direction.

•	Among the States, the following is the statistic of top 5 states which shows higher values of enrollment.

![image](https://user-images.githubusercontent.com/81927278/185422430-5e5d8216-ec50-4621-a832-341eeb1b4ace.png)

•	Among the Counties, the first 5 which has the highest frequency of plans is shown below.

![image](https://user-images.githubusercontent.com/81927278/185422774-09e8fff6-5dc8-463d-bd39-958ecee6f74c.png)

•	On Organization level, the below table furnishes the top 5 positions whose counts of plans are actively more.

![image](https://user-images.githubusercontent.com/81927278/185424050-52fbc3a0-32c8-4f44-b995-0717de0ffa93.png)

•	The Monthly Consolidated Premium ranges between an average of 43 dollars to maximum 375 dollars per month. Also, Annual Drug deductible ranges between an average of 211 dollars to maximum 435 dollars per annum.

•	As the graph depicts (Refer Report), 37% people had given 4-star ratings to the plans and only 2% people had given full 5-star ratings, which means somewhere in the borderline, deep analysis is needed on what goes missing with the plans to impress the customers.

![image](https://user-images.githubusercontent.com/81927278/185424882-57358065-c875-410c-abe0-92298d73745d.png)

•	The Annual MOOP Value ranges between an average of 5418 dollars to maximum 6700 dollars. 

•	Overall, 77% of people had availed Non-SNP plan type, whereas 16% for Dual Eligible, 3% for Chronic or Disabling Condition and only 2% for Institutional type. It is clearly shown in the above bar plot.

•	The following table shows the type of plan and percentage enrolled for the same. According to the data, Local HMO seems to be in the highest position.

![image](https://user-images.githubusercontent.com/81927278/185425398-364435b5-4e52-403f-b4f1-fef61920b80e.png)

BIVARIATE & MULTIVARIATE ANALYSIS :

•	Local HMO Plans shows a steady increase in star ratings from the year 2017 to 2020 and is the topmost rated plan.

•	More or less the other plans too converge closely up until 2020.But Cost Plan type shows a heavy decrease after the year 2018 and constantly declines thereafter. Further inspection is needed to figure out the fall of ratings in Cost Plan type.

•	Though Texas shows the high percentage of plans enrolled (7%), with respect to January Enrollment, California tops the other States with the high percentage for Local HMO plan type.

•	Monthly Consolidated Premium is high for Local HMO plan type, followed by Local PPO plan type.

![image](https://user-images.githubusercontent.com/81927278/185427129-0d937132-bd97-45b2-9b65-285ee7e6da82.png)

•	The enrollment trend graph seems to be steadily increasing from month over month (Jan- Feb) and also from year over year (2017-2020). More number of beneficiaries are adding up year over year.

•	From the geoplot (Refer report), it is evident that the beneficiaries count percentage is more for Non-SNP Plan Types when compared to the other specific plans. The State of North Dakota and Williams County shows the maximum count of Non-SNP plan.

BUSINESS RECOMMENDATIONS :

•	Proper groundwork should be carried out to analyze why there is a sudden decrease in Cost Plan type Enrollment over the four-year interval. Necessary
actions and ideal plan for transitioning  it to be a WIN-WIN scenario should be in the track.

•	Though there are few special needs plan types, beneficiaries are more pitched towards the non-SNP plan type. On par with non- SNP type, the other special types of plans can be reviewed and refactored in such a way that it too reaches more audience.

•	The overall market sentiment seems to be moving towards the positive direction year over year, but close monitoring and analysis is needed to figure out for any anomalies in the future trend.


•	On the other hand, marketing campaigns, referral program, video testimonial share, contests shall be organized to promote the Plan types which are declining from its original position, to capture larger market area.

•	When needs arise, new Partner branding can help in a long way to create hype over the plans, but in longer run it is only the elements of any plan which keeps itself intact with the beneficiary needs. Hence it is always better to design a plan in such a way it reaches more people.

•	Hence, we sometimes need to analyze the other type of plans, the neighboring countries and other brands follow, and try to leverage ours from it. Constant upgradation of any plans with respect to the people sentiment analysis is always directly proportional to the highest success rate.


NOTE : The size of the dataset is 57.5 MB, even the compressed file is greater than the allowed limit of 25 MB, hence it is impossible to upload the spreadsheet.



















