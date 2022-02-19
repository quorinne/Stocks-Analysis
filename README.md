# Stocks-Analysis

##Deliverable 2: Written Analysis of Results 


### Overview of Project

The purpose of this analysis was to compare the stock value of green energy businesses for our client Steve and his parents. Steve’s parents were interested in a company called Daqo or DQ.


### Results


Our first step in this project was to compare the value of DQ's stock across the years 2017 and 2018. In 2017 the total Daily Volume of DQ's stock was 35,796,200 with a return of 199.4%, which was the lowest stock value of all listed green energy stocks in the analysis. In 2018 the Total Daily Volume was 107,873,900 with a -62.6% return, which was still among the lowest value. Prior to refactoring the script, the original code ran in .734 seconds for 2018 and .707 for 2017. 


2017





2018




### Summary

Refactoring code in VBA has many benefits and a few cons. In general, refactored VBA code can improve the design and make software easier to understand. It can also improve performance and speed of programs. These benefits are not without downsides however, including time and a certain level of risk with larger codes. Refactoring takes a lot of time to start with and if mistakes re made it takes even longer to fix, especially with longer codes. 

In this case the pros have outweighed the cons. While these run times of .734 and .707 were great for our small sample of data it would have been next to useless when used for a larger number of tickers, taking far too long to be practical. Therefore, we refactored the script, getting rid of redundant code and limiting the number of loops over tickers to just the one. The new and improved version ran in just .054 for 2018 and .0625 for 2017.





2017 Refactored



2018 Refactored


The biggest issue with refactoring the code was in time consumption and the complexity. Not only did I spend a longer period on refactoring but I also spent more time correcting any mistakes I made.








