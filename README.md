# prophet-challenge
Utilize activities from previous Modules
Worked some of code in JupyterGoogel Colab for practice, then transferred info in VS Code
Assisted by prompts from Google Colab
Assisted by prompts form both Amazon Q and GitHub MS CoPilot
Verified and streamlined Code with ChatGPT

# Questions and Answers

**Question:** Did the Google search traffic increase during the month that MercadoLibre released its financial results?

**Answer:** Yes, the Google search traffic increased during the month that MercadoLibre released its financial results. The search traffic for May 2020 was about 1.09 times higher than the monthly median across all months, indicating a significant increase in searches during that time. 

**Question:** Are there any time based trends that you can see in the data?

**Answer:** Hourly Trends: Clear pattern in the search traffic by the hour of the day, with peaks occurring during certain hours, reflecting periods of higher user activity. Which indicates that users tend to search for MercadoLibre later in the day.

Daily Trends: The average search by day indicates Monday-Friday heavier searching than over the weekend.

Weekly Trends: Noticeable patterns indicating a higher search during the holiday season, weeks 40-52, possibly corresponding with shopping trends during the holidays. 

**Question:** Do both time series indicate a common trend that’s consistent with this narrative?

**Answer:** Yes, Stock Price (Close): The stock price shows a significant increase over the first half of 2020, Indicates also a reflection of market shock in March but regained and continue to climb. 

The Google Search Trends: Search traffic follows a similar pattern with a dip in March then a steady increase. 

This suggests that the narrative is consistent with both time series, Stock Price and Google Search Trends. 

**Question:** Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?

**Answer:** Based on the results, there does not appear to be a predictable relationship between the Lagged Search Traffic, Stock Volatility or Hourly Stock Return. 

Lagged Search Trends and Stock Volatility: The correlation is -0.1489, which is not significant. 
Lagged Search Trends and Hourly Stock Return: The correlation is 0.0179, which is close to zero, indicating almost no relationship between them.
Stock Volatility and Hourly Stock Return: The correlation is 0.0614. which is shows a weak relationship.

**Question:**  How's the near-term forecast for the popularity of MercadoLibre?

**Answer:** The near forecast for MercadoLibre is positive. The forecast indicates that search traffic is expected to remain constant, yet with seasonal fluctuations. This indicates that model has a good level of certainty in the short-term forecast. 

**Question:** What time of day exhibits the greatest popularity?

**Answer:** Based on the daily component of time series model, MercadoLibre is most popular from 2PM to 3PM. This is when the search traffic is the highest. 

**Question:** Which day of week gets the most search traffic?
   
**Answer:** The weekly component indicates that Monday has the highest search traffic for MercadoLibre. This appears to suggest user engagement is at the beginning of the work week. 

**Question:** What's the lowest point for search traffic in the calendar year?

**Answer:** According to the yearly component of the time series model, the lowest point for search traffic usually occurs in late December as the holiday season is winding down. 
