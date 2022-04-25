# CAMSL dataset

## What's this?
CAMSL is the first public dataset for a TOU tariff intervention study using smart-meter data including pre, on and post TOU intervention periods.

We provide 1423 customers data in total, 1023 as TOU customers and 400 as NON-TOU customers.
The dataset also includes raw data of 3337 customers who did not participate in the TOU trial.

You can download the full dataset from here: https://data.mendeley.com/datasets/cmpsyncmmk/1

If you use the dataset for your research purpose, cite the following article.
```
Kiguchi Y, Weeks M, Arakawa R. Predicting winners and losers under time-of-use tariffs using smart meter data. Energy. 2021 Dec 1;236:121438.

https://www.sciencedirect.com/science/article/abs/pii/S0360544221016868
```

## Table of Contents
* consumption_data.zip: consumption data
* customer_info.csv: customer information (house_type, number_of_residents, tou)
  * TOU users == 1
  * Control users == 0
  * As for the selection of Control users, please refer to the article.
* web_info.csv: web activity information (for TOU customers) (sessions, average_session_duration, bounce_rate)
  * already padded if the value is missing.
* temperature_Tokyo.csv: temperature data at Tokyo from 2017/6/1 to 2018/12/31 hourly
* holidays.csv: Japanese national holidays
* non_tou.csv.gz: raw data of consumption of total 3337 customers who did not participate in the TOU trial

## Questions
If you have any questions about the dataset, feel free to reach out to `riku.arakawa1996 [at] gmail.com`
