Project Overview

This project involves analyzing stock data from major telecom companies: AT&T, T-Mobile, and Verizon. The analysis focuses on understanding stock performance trends, volume changes, and volatility over a specified period. Below are the detailed steps taken to prepare and analyze the data.

Steps Taken
=======
This project involves analyzing stock data from major telecom and oil companies: AT&T, T-Mobile, and Verizon, Chevron, Conoco and Exxon. The analysis focuses on understanding stock performance trends, volume changes, volatility and Return of Investment over a specified period. Below are the detailed steps taken to prepare and analyze the data.

Steps Taken

1. Loading the Necessary Libraries and Packages
The analysis begins by loading essential libraries for data manipulation and visualization.

2. Importing the Dataset
The stock data for AT&T, T-Mobile, and Verizon was fetched using the Nasdaq API and stored in a pandas DataFrame. The data was combined into a single DataFrame for easier analysis.

3. Cleaning and Preparing the Data
Data cleaning involved:

Converting date columns to datetime format.
Sorting the data by company and date.
Handling missing values using forward fill and backward fill methods to ensure completeness.

4. Filtering the Data
The dataset was filtered to include data from January 1, 2017, to December 12, 2017. Additional columns for year and quarter were extracted to facilitate quarterly analysis.

5. Feature Engineering and Selection
New features were engineered to enhance the analysis:

Calculation of the percentage change in adjusted close prices for each quarter.
Calculation of the total stock volume for each quarter.
Calculation of daily returns and their standard deviation to measure volatility.

6. Data Visualization
Several visualizations were created to provide insights into the stock data:

Quarterly Percentage Change per Company

This plot shows the percentage change in stock prices for each company on a quarterly basis.

Measures the growth or decline in stock prices over a period, helping to identify trends and compare performance across different time frames.

  TELECOM:
1. T-mobile and Verizon were on opposite ends of the spectrum at just about 10% above and below initial buy price, respectively in Q1.
2. Q2 Saw a loss across all companies especially for T-Mobile with a loss of 15% from Q1. 
3. In Q3 Verizon had a huge bounce back, climbing 16% from Q2.
4. End of year highest return was Verizon finishing at 6% above initial buy price.
5. Telecom was the only industry of the two observed that saw a company finsih with a loss with ATT finishing the year at 4% below the intial buy price

  Oil:
1. Q1 saw a loss across all 3 companies observed.
2. Q2 ConocoPhillips continued to decline while Exxon and Chevron got to within 2% of the initial buy price.
3. Q3 had the greatest percentage increases with ConocoPhillips climbing almost 20% from Q2 and Exxon also increasing to just over 11% of initial buy price.
4. By end of year all 3 oil companies finished within 5% of their initial buy price.

Quarterly Stock Volume per Company

Analyzing the change in stock volume of a company provides several key insights into the company's market activity and investor behavior.

1. Market Interest and Liquidity:

High Trading Volume: Indicates strong market interest and high liquidity, meaning that a large number of shares are being bought and sold. This can be due to various reasons such as positive news, earnings reports, or other significant company events.

Low Trading Volume: Indicates lower market interest and lower liquidity, meaning fewer shares are being traded. This can result in higher volatility and larger price swings due to the reduced ability to buy or sell shares without affecting the stock price.

2. Price Movement Predictors:

Volume and Price Relationship: A significant change in stock volume can often precede or accompany a price movement. For example, an increase in volume often indicates a potential price breakout, either upwards or downwards, as it reflects increased trader activity.

Confirmation of Trends: An increase in volume can confirm a price trend. For instance, in a bullish trend, increasing volume reinforces the strength of the trend. Conversely, decreasing volume might indicate a potential reversal.

For the Oil industry we can see that:

1. Conoco: 4.8 to 5 to 4.2 to 3.9

Shows a decrease in price in the first quarter, but an increase in stock volume in Q2 most likely showing a positive sentiment from investor that expected an increase in the stock price and resulting in a massive increase for Q3 but a lower price and decrease of more stock volume in Q4.

2. Chevron: 4.2 to 3.4 to 3.2 to 2.5

Is a good example for the Bearish sentiment, since it had a decrease in volume stocks but the market value kept increasing due to a market believe that the company will be giving better results and even tho it skyrocketed in Q3 ended up following again in Q4.

3. Exxon: 8 to 7.1 to 6.3 to 4.3

Showed a pretty abnormal analysis since it's volume decrease significaly during the year but had an small and consistent increase in stock price due to the companies strong position in the industry.

For the Telecom industry the data shows:

1. AT&T consistently had the highest trading volumes, indicating high liquidity. Despite the increase in stock we could see how the price fluctued it across the year.

2. T-Mobile had the lowest trading volumes, suggesting lower investor interest. When the stock diminished so did the price and then got stable.

3. Verizon showed moderate trading volumes, reflecting steady investor interest. Same as T-Mobile consistent amount of stock volume that change accordingly with the market value.

Quarterly Volatility per Company

Some of the key reasons to study the volatiliy of a company are:

1. Investment Strategy:
Short-Term Trading: Traders may seek high-volatility stocks to capitalize on significant price swings and short-term gains. However, this approach comes with higher risk.
Long-Term Investment: Investors may prefer low-volatility stocks for long-term investments as they offer more stable returns and lower risk.

2. High Volatility: Indicates that the stock's price experiences significant fluctuations over a short period. High volatility is often associated with higher risk as the stock price can swing dramatically in either direction.
Low Volatility: Indicates that the stock's price is relatively stable and experiences smaller fluctuations. Low volatility is associated with lower risk as the stock price tends to change more gradually.

For the Oil industry the data shows:

1. Chevron: Showed a moderate volatility during the year, only going abruptly up in Q3 but stabilizing again by the end of the year. 
2. Exxon: Dispite changes in volume and price kept a pretty low volatility.
3. Conoco: Conoco perform pretty well despite the price changes, their stock volume was pretty consisten helping to with the volatility 

For the Telecom industry the data shows:

1. AT&T: Exhibited the lowest volatility, indicating a more stable stock.
2. T-Mobile: showed the highest volatility, indicating higher risk and also higher returns.
3. Verizon: had similar volatility, offering a big reward for a big risk.

Return on Investment per Company

Analyzing the cumulative ROI on $1500 for the six companies in 2017 reveals distinct performance trends across telecommunications and energy sectors:
1. Telecom Sector:
T-Mobile was the clear winner, ending 2017 with a positive cumulative ROI of $106.63. Despite some quarterly fluctuations, it consistently generated gains, making it the best investment in the telecom sector.
Both AT&T and Verizon faced challenges throughout the year, finishing with negative cumulative ROIs of -$72.68 and -$74.96, respectively. Although Verizon showed some recovery in the later quarters, neither company managed to produce a positive ROI by year-end.

2. Energy Sector:
Chevron performed the best in the energy sector, ending the year with a cumulative ROI of $56.08. Despite early losses, Chevron recovered strongly in the latter half of the year.
ConocoPhillips also showed significant recovery after a challenging first half, finishing the year with a positive cumulative ROI of $17.12. Though the gains were modest, it outperformed  Exxon Mobile that has a consistent Losses or -$95.25, making the company the weakest performer in the energy sector.

Conclusion:
Both sectors showed varying degrees of volatility, with T-Mobile and Chevron managing to turn around early losses, while companies like AT&T, Verizon, and Exxon Mobile struggled to recover fully.
T-Mobile and Chevron were the top performers in their respective sectors, providing the most favorable returns for investors in 2017.