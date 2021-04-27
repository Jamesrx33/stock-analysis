# **<p align="center">Green Energy Stocks Analysis</p>**

### **<p align="center">A Data Analytics report designed to discern the best performing Green Energy Stocks of 2017 and 2018.</p>**

---
## Overview
This report is designed to enumerate the Total Daily Volume and Yearly Return of 12 individual Green Energy stocks in the years 2017 and 2018. The information below will be presented to Steve's parents to ensure they make the most prudent investment.

---
## Results
**Stock Performance - 2017:** For the exception of Ticker "TERP", every Green Energy stock saw a positive return on investment ranging from 5%-199% at year's end. The yearly total of daily stock volume ranged from $136 million to $3.2 billion, indicating this was a lucrative year. Given the percentage return on investment , the top performing stocks of this year were "DQ", "SEDG" and "ENPH"

**Stock Performance - 2018:** This was a hard year for Green Energy stocks. The total daily stock volume in 2018, ranging from $83 million to $3.3 billion, was comparable to 2017. However, the return on investment was negative for every stock except for "ENPH" and "RUN".

**Code Performance Testing:** Utilizing the original code from this module, the performance times were .67s and .70s for the anylsis of the years 2017 and 2018 respectively.

![Original Code 2017](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/VBA_Challenge_2017_Original_Code.png?raw=true) ![Original Code 2018](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/VBA_Challenge_2018_Original_Code.png?raw=true)

After refactoring the code, these times were reduced to .09s(rounded) for the analysis of both 2017 and 2018

![Refactored Code 2017](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png?raw=true) ![Refactored Code 2018](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png?raw=true)

---
## Conclusion
Given that the return on investment was both substantial and consistent throughout 2017 and 2018, I would recommend that Steve's parents **invest in "ENPH" stock.**

Refer to the tables below for a case by case analysis of the stocks provided

---
### Stocks Analysis Table - 2017
![Analysis_Table_2017](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/Analysis_Table_2017.png?raw=true)

### Stocks Analysis Table - 2018
![Analysis_Table_2018](https://github.com/Jamesrx33/stock-analysis/blob/main/Resources/Analysis_Table_2018.png?raw=true)

---
## Summary
Refactoring code has a variety of costs and benefits. The process of refactoring can be time-consuming and involve the use of advanced data structures, many of which are difficult to grasp and implement. However, the use of code refactoring can lead to more fluent applications that are easier for a third part to interpret. Most importantly, refactored code can exponentially improve the run-time and performance of your code. This can be a vital practice when working with large-scale projects that run thousands of processes across a vast array of databases. Additionally, the benefits of refactoring code can be evident even in small projects like the script in this VBA module. With the use of multiple arrays, we were able to reduce the number of For loop iterations and ultimately increase the worst-case performance of the script from .7s to .09s (An improvement of 678%!).

---
## Reference Documentation - [Source Code Repository](https://github.com/Jamesrx33/stock-analysis), [Download .xlsm project file](https://github.com/Jamesrx33/stock-analysis/raw/main/VBA_Challenge.xlsm)
