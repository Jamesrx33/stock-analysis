# **<p align="center">Green Energy Stocks Analysis</p>**

### **<p align="center">A Data Analytics report designed to discern the best performing Green Energy Stocks of 2017 and 2018.</p>**

---
## Overview
This report is designed to enumerate the Total Daily Volume and Yearly Return of 12 individual Green Energy stocks in the years 2017 and 2018. The information below will be presented to Steve's parents to ensure they make the most prudent investment.

---
## Results
**Stock Performance - 2017:** For the exception of Ticker "TERP", every Green Energy stock saw a positive return on investment ranging from 5%-199% at year's end. The yearly total of daily stock volume ranged from $136 million to $3.2 billion, indicating this was a lucrative year. Given the percentage return on investment , the top performing stocks of this year were "DQ", "SEDG" and "ENPH"

**Stock Performance - 2018:** This was a hard year for Green Energy stocks. The total daily stock volume, ranging from $83 million to $3.3 billion, was comparable to 2017. However, the return on investment was negative for every stock except for "ENPH" and "RUN".

---
## Conclusion
Given that the return on investment was both substantial and consistent throughout 2017 and 2018, I would recommend investing in "ENPH" stock.

Refer to the tables below for a case by case analysis of the stocks provided

---
### Stocks Analysis Table - 2017
![Analysis_Table_2017](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/Analysis_Table_2017.png?raw=true)

### Stocks Analysis Table - 2018
![Analysis_Table_2018](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/Analysis_Table_2018.png?raw=true)

### Challenges and Difficulties Encountered
        >The original "launched_at" data was in written in a Unix Timestamp.
        
          - This was overcome by applying the following date conversion formula: =(((I2/60)/60)/24)+DATE(1970,1,1)
 
        >The resulting "Date Created Conversion" obtained from the Unix Timestanp needed to have the Year extracted in order to provide an applicable filter to our visualization
        
          - The Excel "Year()" formula was used to extract the Year from the converted Launch Date

        >The original data was from multiple Parent Categories that were less applicable to Louise's inquiry
        
          - The "Parent Category" data was used as a filter in our Pivot Table so we could focus solely on Theater Kickstarters
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1. Theater Kickstarter campaigns in the month of May have the highest ratio of success.
  2. The number of failed campaigns throughout the year remains roughly constant.

- What can you conclude about the Outcomes based on Goals?

  * There is an inverse relationship between a Theater Kickstarter Campaign's Goal and Ratio of Success. As the Goal increases, the chances of success decrease.

- What are some limitations of this dataset?
  
  1. There are a variety of outliers (Campaigns with goals >$1,000,000) that skew the dataset to the right.
  2. The sample set is from multiple countries and spans 10 different Kickstarter categories.
  3. The dates of the sample Campaigns are all 4+ years old, potentially rendering them less applicable to today's market.
  4. Locations within the Countries are not specified and could prove relevant (State, City, Venue, etc).
  
- What are some other possible tables and/or graphs that we could create?

  1. A Bell Curve to validate the integrity of the data per our NULL Hypothesis(s) (I.E. "The greater the goal, the less successful campaigns")
  2. A Scatter Plot that shows the correlation between Year of the Campaign and percentage of success in each category (Theater Campaigns are X-amount more/less successful than other categories)
  3. A Table that displays the number of backers and pledged amount for each Theater campaign (An analysis of Campaigns with a high volume of backers vs high average pledged amount could prove useful)

---
## Reference Documentation - [Source Code Repository](https://github.com/Jamesrx33/Kickstarter-Challenge/tree/main), [Download .xlsx project file](https://github.com/Jamesrx33/Kickstarter-Challenge/raw/main/Kickstarter_Challenge.xlsx)
