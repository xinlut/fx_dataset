# fx_dataset
20-Year Historical Foreign Exchange Data (5-Second Intervals) for Artificial Intelligence Research

# Introduction
Welcome to our repository, which hosts a comprehensive dataset of foreign exchange (Forex) market data spanning the last 20 years, captured at 5-second intervals. This rich dataset is designed to serve as a foundational resource for artificial intelligence developers, researchers, and enthusiasts interested in developing, testing, and trading strategies in the Forex market.

# Why another forex dataset?
Our dataset offers second-level granularity for 24/5 market analysis, a feature rare among other data providers. It enables tracking of rapid price movements and allows users to easily aggregate data for broader analysis. Covering 20 years, it captures major currency trends, essential for developing robust trading strategies. I plan to use them in the transform model to glean deeper insights and make more accurate market predictions. This integration will boost trading strategies and decision-making, keeping traders and researchers ahead in the fast-paced Forex market. 

# About the Dataset
The dataset includes:

* Time Range: 20 years of historical data.
* Granularity: Data captured every 5 seconds.
* Included Currencies:
  *   USD/JPY, (since 2005)
  *   EUR/USD, (since 2005)
  *   GBP/USD, (since 2005)
  *   USD/CNH. (since 2011)
  *   will be further expandded to USD/CHF, USD/CAD, AUD/USD, NZD/USD ....
* Data Points: timestamp, Open, high, low, close prices, and volume for each interval.

# Purpose
This dataset is tailored for those looking to:

* Develop and test AI-driven trading algorithms.
* Analyze high-frequency Forex market dynamics.
* Explore machine learning models in financial contexts.

# How to Use This Dataset

* Data Structure: the data is stored in csv file for seperate years. 
* Example Use-Cases: simply unzip the files contains the trading history data, and start to label and train your autonomouse forex algorithms, using LSTM, transformer, time serious AI, timeGPT....
* Notice: if there is no transaction in the 5 second time interval, there will be no record in the dataset. Therefore, checking the timestamp is not unformally spaced in light trading hours.
* When you develop auto trading program, be aware of the none uniformly spaced time stamp！
  
# Disclaimer
This dataset is provided for educational and research purposes only.
Users should be aware of the risks involved in Forex trading.

# Acknowledgments

# License
MIT

# Contact Information
For further inquiries or support, please contact xinlut007@gmail.com.

# Donation
A $5 donation will encorage me to maintain and upgrade to this repository up-to-date. 

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=BBEQ6LQ4M736N)
Thank you for your support!
