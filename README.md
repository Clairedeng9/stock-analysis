# Stock-Analysis by using Excel VBA script
## Overview of Project
The purpose of this project to refactor the original codes to use less steps, less memories and user friendly, and achieve the same goal to analysis the year 2017 and 2018 for some specific stock tickers' returns. Then we will measure stock performances and determine they are worth to invest. 
## Results
By creating a ```tickerIndex``` variable and use this variable to access across the different setting arrays (```ticker```, ```tickerVolumes```, ```tickerStartingPrices```, and ```tickerEndingPrices```), then use for loop to loop from row 2 to the end of row. In this case, we do not need to define different variable and activate sheet back and forth, which makes the running codes more efficient

**VBA_Challenge_2017**

![VBA_Challenge_2017](https://user-images.githubusercontent.com/103073631/165007524-f2c0b131-6e6b-484f-8e95-e5b80c341804.png)

- From above 2017 analysis generated by VBA script, we will know the performances for most of stocks are relatively good, since they all have positive returns. The highest return stock is DQ, which reached to 199.4% with a relatively small daily stock volume. The TERP stock is the only one in 12 of the stocks had the negative return.


**VBA_Challenge_2018**

![VBA_Challenge_2018](https://user-images.githubusercontent.com/103073631/165007530-5c7913f7-7388-4d5d-9a97-c08aeb76e5c6.png)

- From above 2018 analysis generated by VBA script, we will know the performances for most of stocks are changed to negative returns. The Run and ENPH are both stayed positive in 2017 and 2018 but RUN had an increase in return in 2018 and ENPH had a decrease in return comparing with 2018. By comparing with 2017 and 2018, we can say in overall, the whole performance in 2017 is better than 2018.
## Summary
#### 1. What are the advantages or disadvantages of refactoring code?

  **Disadvantages:**

    - Refactoring process may cause the result is different than the original.
    - Time consuming to build up the logic and big picture to improve the codes.
    - Potentials bugs to invest more time to debugs

  **Advantages:**

    - Make codes clearer and more organized to understand and operate.
    - Make the whole project running faster.
    - Refactoring is improving the logic of the code and user friendly.

#### 2. How do these pros and cons apply to refactoring the original VBA script?

  **Pros:**
  - The first and biggest pros of this refactoring is to make the VBA script run faster than the original VBA script. From the above Results section, we knew that the improved script was taking 0.234375 seconds to run the analysis in year 2017 and 0.21875 seconds to run the analysis in year 2018.

  **Cons:**
  - The cons for me are taking time to build up my logic of how to make the refactoring one more faster. I was building a nested loop at the first time, that one was still saving time on running this project, but that processing somehow did not follow by hints steps, then I was rethinking and following the hints step by step to build the current one, which made a big improve. 

