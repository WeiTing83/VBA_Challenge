# VBA_Challenge
## Overview of Project and Purpose
   Steve want to help his parent to analyze how often the market stock gets traded in daily basis by summarizing its daily trading volume within a year. He also want to know those stocks were grew or shrunk.


### Analysis of stocks for 2017   
![VBA_Challenge_2017](https://github.com/WeiTing83/VBA_Challenge/blob/main/resource/VBA_Challenge_2017.png)
### Analysis of stocks for 2018 
![VBA_Challenge_2018](https://github.com/WeiTing83/VBA_Challenge/blob/main/resource/VBA_Challenge_2018.png)


## Result:Compare the stocks in 2017 and 2018
Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

1.In 2017, most of stocks are growth, except for TERP. However, in the year of 2018, most of stocks are decreased in price, except for ENPH and RUN. These data can’t reflect which stock is better because we need to compare their financial conditions within two years. Total volume doesn’t have a correlation with return value. It probably needs to evaluate volatility of stock prices in the whole year.

2.Original script only spent 0.02 seconds to run its code, but it doesn’t calculate all the data. After refactored script, in each of 2017 and 2018 year spread sheet, it spends 0.67 and 0.69 seconds to output the results.


## Summary: 
1.What are the advantages or disadvantages of refactoring code?

   There are two advantages of refactoring code. First, it has a clue to writing the code. Second, it saves time to plan my coding map. The disadvantage is if the original coding is too dirty, it probably will let coder spend more time to figure out and debug the script. When computer performs this dirty code, it needs more time to process due to the many wrong direction. 

2.How do these pros and cons apply to refactoring the original VBA script?

   Like this case, the original script provides the coding map and comment so it helps me to do coding. It saved some time for me to plan my coding map. However, if the original scrip provides too many dirty codes, it might lead to different direction of coding process for persons who need to follow up. Additionally, it need spending more time to clean them.

