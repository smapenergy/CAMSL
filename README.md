# CAMSL dataset 

CAMSL is the first public dataset for a TOU tariff intervention study using smart-meter data including pre, on and post TOU intervention periods. 
We provide 1393 customers data in total, 530 as TOU customers and 863 as NON-TOU customers.

<img width="995" alt="overview" src="https://user-images.githubusercontent.com/12772049/55284843-8e1f9380-53b9-11e9-917f-ddf2a97096a0.png">

## Table of Contents
* consumption_data.zip: consumption data 
* customer_info.csv: customer information (house_type, number_of_residents, tou)
  * TOU users have tou == 1
  * Control users have tou == 2
  * Others have tou == 0 (NON-TOU customers not included in Control group)
  * As for the selection of Control users, please refer to the article.
* web_info.csv: web activity information (for TOU customers) (sessions, average_session_duration, bounce_rate)
  * already padded if the value is missing.
* temperature_Tokyo.csv: temperature data at Tokyo from 2017/6/1 to 2018/12/31 hourly
* holidays.csv: Japanese national holidays

Note that we only provide a sample data in this repository.    
If you want a full access to the dataset, please contact riku.arakawa[at]smapenergy.com .
