# Commodities-Dashboard

![Dashboard](Captura1.png)


## Introduction
The purpose of this report is to understand the evolution of different commodity prices and the volatility of said commodities in order to identify investment opportunities.

## Data Source
The data is collected from the [World Bank Commodity monthly prices](https://www.worldbank.org/en/research/commodity-markets) through Power BI, establishing a connection to the xls file. This file contains price data from January 1960 to July 2024 and is subject to update every month.

## Dashboard Features
- **Commodity and year Selection**: Users can select the commodity name and year to be shown.
- **Current Prices**: The dashboard displays the current prices of the commodities along with the last month's change in percentage.
- **Timeline Graph**: The center of the report features a timeline graph of the prices of the chosen commodity.
- **Volatility Gauge Plot**: On the right side of the dashboard, users will find the volatility value for the commodity for the chosen period in a Gauge plot. The minimum value represents the lowest percentage change, and the maximum value represents the highest percentage change in a month.
- **Percentage Change Timeline**: Below the gauge, there is a timeline for the percentage change during the period, allowing users to identify how volatility affected the commodity in the chosen period.

## Investment Opportunity Example
An example of using the dashboard for an investment opportunity can be seen in the Cocoa commodity. If we choose the period from 2018 to 2024, we'll see that the price in US dollars per kilogram ranges around 2.2 and 2.6 most of the time (Volatility of 5.14%). However, in 2023, the price closed over 4.21$/kg by December, peaked at 9.74 in April 2024, and closed June with 8.27$/kg (volatility 12.42%). The reason for this sudden change is "largely due to a global Cocoa shortage. Climate change-induced drought has ravaged crops in West Africa, which contributes around 80% of the world’s cocoa output. According to the International Cocoa Organization, global cocoa supply will decline by almost 11% over the 2023/2024 season" ([JP Morgan Research)](https://www.jpmorgan.com/insights/global-research/commodities/cocoa-prices#:~:text=The%20rise%20in%20cocoa%20prices%20is%20largely%20due,decline%20by%20almost%2011%25%20over%20the%202023%2F2024%20season.).

This might represent an opportunity for savvy investors to investigate further, confirm there is an actual investment opportunity, and open positions with their preferred financial instruments.

## Disclaimer
This is by no means an investment recommendation. The purpose of this project is for educational purposes and to identify opportunities. Each investor should do their due diligence before making investment decisions.
