# Energy_Exploration
This repository contains data exploration for VVC electrical meter usage and billing from July 2019 - June 2020. 

## Plots

Located in `Resources/Plots/Bill Amount by Account` we have individual accounts' billing by month plotted using an interactive bar charts. Shown below is a screenshot of one of these charts.

<img width="600" alt="hvPlotBars" src="Resources\Images\IndividualBillAmtPlot.PNG">

Shown below is all of the accounts billing per month.

<img width="600" alt="hvPlotLinesAllBill" src="Resources\Images\AllAccBillMonth.PNG">

Since one account is much larger than the rest, it is harder to see what is happening with most of the accounts. Shown below is the same plot, but without the largest account.

<img width="600" alt="hvPlotLinesAllButLargestBill" src="Resources\Images\AllButLargestBillMonth.PNG">

Similarly, we've plotted the Kwh usage per month per account with and without the largest account, shown below, respectively.

<img width="600" alt="hvPlotLinesAllKwh" src="Resources\Images\AllAccKwhMonth.PNG">
<img width="600" alt="hvPlotLinesAllButLargestKwh" src="Resources\Images\AllButLargestKwhMonth.PNG">

Creating a new column of data, `Cost per Kwh` found by diving the `Bill Amt` columns by the `Kwh Usage` columns, we graphed `Bill Amt vs Cost per Kwh` and `Kwh Usage vs Cost per Kwh` shown below, respectively.

<img width="600" alt="hvPlotLinesAllButLargestKwh" src="Resources\Plots\Bill_Amt_Cost_per_Kwh_per_month.png">
<img width="600" alt="hvPlotLinesAllButLargestKwh" src="Resources\Plots\Kwh_Usage_Cost_per_Kwh_per_month.png">

## Tables

Throughout the data exploration, we have created three new csv files located in `Resources/csv_files`.

- The `usage_df.csv`: 
    - <img width="300" alt="usage_df" src="Resources\Images\usage_df_csv.PNG">
- The `monthly_bill_usage.csv`: 
    - <img width="300" alt="usage_df" src="Resources\Images\monthly_bill_usage_csv.PNG">
- The `high_low_bills.csv`: 
    - <img width="300" alt="usage_df" src="Resources\Images\high_low_bills_csv.PNG">
