# fx_dataset
20-Year Historical Foreign Exchange Data (5-Second Intervals) for Artificial Intelligence Research

# Introduction
Welcome to our repository, which hosts a comprehensive dataset of foreign exchange (Forex) market data spanning the last 20 years, captured at 5-second intervals. This rich dataset is designed to serve as a foundational resource for artificial intelligence developers, researchers, and enthusiasts interested in developing, testing, and trading strategies in the Forex market.

# Why another forex dataset?
Our newly offered dataset stands out in the realm of Forex trading, catering specifically to the dynamic and incessant nature of the global foreign exchange market that operates 24/7 without pause. Recognizing the critical need for machine trading in this continuously evolving market, our dataset provides a unique advantage with its second-level granularity. This feature is particularly designed for accurately tracking rapid price movements, a capability not commonly offered by other data providers. Moreover, users have the flexibility to merge and aggregate this granular data into higher time frames as per their requirements, using simple programming techniques. This dataset spans across the last 20 years, a duration meticulously chosen to encompass a complete cycle of major currency appreciations and depreciations. It offers invaluable insights and a comprehensive perspective for both historical analysis and the development of future-proof trading strategies in the Forex market.

The recent advancements in Large Language Models (LLMs) have ushered in a new era of artificial intelligence, surpassing traditional models like LTSM in handling extensive time series data. Our dataset is particularly poised to benefit from this evolution. By leveraging the power of LLMs, users are equipped not just to track rapid price movements in the Forex market, but also to unearth deeper, more nuanced insights and make accurate predictions that were previously unattainable. This capability dramatically enhances trading strategies, elevates risk assessment accuracy, and refines decision-making processes. As LLM technology continues its rapid development, its application in analyzing our comprehensive dataset is expected to lead to the creation of even more advanced, AI-driven trading algorithms. This represents an invaluable tool for traders and researchers seeking to maintain a competitive edge in the dynamic and fast-paced global Forex market. Embrace our dataset to harness the full potential of LLMs, propelling your Forex trading strategies into the future.

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
