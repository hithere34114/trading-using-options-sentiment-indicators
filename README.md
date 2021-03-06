<p align="center">
  <img align="center" width="200" src="https://quantra.quantinsti.com/images/img_logo.svg">
</p>
<p align="center">Learn A to Z of Algorithmic and Quantitative Trading</p>
<p align="center">Quantra<sup>&reg;</sup> is an e-learning portal by QuantInsti<sup>&reg;</sup> that specializes in Algorithmic &amp; Quantitative Trading. Quantra offers the best self-paced courses that are a mix of videos, audios, presentations, multiple choice questions and highly interactive exercises.</p>

<br>

<div align="center">
  <h3>
    <a href="https://quantra.quantinsti.com/">
      Website
    </a>
    <span> | </span>
    <a href="https://quantra.quantinsti.com/course/trading-using-options-sentiment-indicators">
      Course
    </a>
       <span> | </span>
    <a href="https://quantra.quantinsti.com/community">
      Community
    </a>
    <span> | </span>
    <a href="https://quantra.quantinsti.com/glossary">
      Glossary
    </a>
    <span> | </span>
    <a href="https://www.quantinsti.com/blog/">
      Blog
    </a>
  </h3>
</div>
<div align="center">
  <img align="center" src="https://user-images.githubusercontent.com/16116886/41084441-d6b2d30c-6a51-11e8-8b5e-24cd923592c1.png">
</div>

<br/>

> Made on Python version 2.7

### Table of contents
 -   [About the course](#about-the-course)
 -   [Breadth Measures](#breadth-measures)
 -   [Option Trading Measures](#option-trading-measures)
 -   [Volatility Measures](#volatility-measures)
 -   [Download](#download)
 -   [Contact Us](#contact-us)

## About the course
[(Back to top)](#table-of-contents)

This course will help you to understand the two major emotions that drive the entire market - Fear and Greed and help you to  capitalize on these emotions to make profits.

#### Highlights of the course are:

1.  Creation of a strong foundation for the concepts on sentiment trading, sentiment indicators such as TRIN or Arms index or Short term Trading Index, Put/Call ratio and Volatility Index.
2.  How to interpret the sentiment indicators and devise trading strategies using sentiment indicators.
3.  Develop a trading logic by using signals from the sentiment indicators and code it using Python programming language.
4.  Analyze the strategy in Microsoft Excel using 2 years of historical data for backtesting.
5.  Unserstand the various risks involved in while trading using sentiment indicators.

#### What do I learn in this course
-   Market sentiments and how they influence your trade
-   About sentiment indicators, how to interpret them and devise trading strategies based on these interpretations
-   Code trading strategies in Python using sentiment indicators and analyze the trading signals generated by the strategy in Microsoft Excel
-   Understand how to think logically about the entry and exit points in a trade, while creating an algorithm for trading
-   Code trading strategies algorithmically and backtest on historical data to gauge your strategy’s performance in markets
-   The Various risks which can influence your trade and how to mitigate them

Want to know more? Check out the course [here](https://quantra.quantinsti.com/course/trading-using-options-sentiment-indicators).

## Breadth Measures
[(Back to top)](#table-of-contents)

The folder contains the following topics:

**Fetching data:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=2&unit_no=11) where you will learn how to fetch data for S&amp;P 500 futures contracts, advancing stocks and declining stocks on NYSE from Quandl.

**Defining Bollinger Bands:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=2&unit_no=12) where you will learn to define the upper and lower Bollinger bands.

**Identifying crossovers:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=2&unit_no=13) where you will learn to set values for flags/boolean variables (variables storing either True or False) for moving average and stop loss band crossovers.

**Generating Buy Signals:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=2&unit_no=14) where you will learn to check the condition for opening a Buy position when the upper Bollinger band is crossed and assign an appropriate value to the variable ‘flag’.


## Option Trading Measures
[(Back to top)](#table-of-contents)

The folder contains the following topics:

**Generating a Sell Signal:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=3&unit_no=13) where you will learn how to place a 'SELL' order if PCR crosses below the lower Bollinger band since it is a sign of an overbought market. We will take a contrarian position amid this bullish sentiment.

**Closing an open sell position 1:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=3&unit_no=14) where you will learn to place a buy order to close the open short position.

**Closing an open sell position 2:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=3&unit_no=15) where you will learn to close the open short position if PCR crosses the Lower Stoploss Band, i.e. PCR continues to fall after crossing the LBB, by placing a 'BUY' order, booking a loss.

**Closing an open sell position 3:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=3&unit_no=16) where you will learn to close an open short position by placing a buy order if the absolute stop loss value triggers a signal to close the position.

**Closing an open Buy position:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=3&unit_no=17) where you will learn to place a sell order to close the open buy position.


## Volatility Measures
[(Back to top)](#table-of-contents)


**Generating a buy order:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=4&unit_no=11) where you will learn how to generate an order to buy S&amp;P 500 futures contracts, if the value of VIX exceeds the threshold value (i.e. thresh = 22).

**Closing an open Buy position 1:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=4&unit_no=12) where you will learn to check if the value of VIX exceeds the threshold value (i.e. thresh = 22); we will buy S&amp;P 500 futures. In this exercise, if the S&amp;P 500 futures contract value is trading 5% above its bought price, we will sell the contract and book a profit. We will then update the required fields and flags to avoid conflicts in our codes.

**Closing an open Buy position 2:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=4&unit_no=13) where you will learn to check if the value of VIX exceeds the threshold value (i.e. thresh = 22); then we will buy S&amp;P 500 futures. If the S&amp;P 500 futures value is 5% above its bought price, we will sell the futures contract and book a profit. In this exercise, if the S&amp;P 500 futures value is 5% below its bought price, we will sell the futures contract and book a loss (our stoploss condition). We will then update the required fields and flags to avoid conflicts in our codes.

**Appending trade data:**
An [exercise](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=4&unit_no=14) where you will learn to use the append() method. The append() method adds a single item to an existing list. It does not return a new list, but it rather modifies the original list. We will modify the ‘stoploss' and ‘mtm’ list in this exercise.

You can understand the concepts by accessing the full [course](https://quantra.quantinsti.com/course/trading-using-options-sentiment-indicators).

## Download
[(Back to top)](#table-of-contents)

You can download the resources [here](https://quantra.quantinsti.com/startCourseDetails?cid=39&section_no=6&unit_no=3).


## Contact Us
[(Back to top)](#table-of-contents)

You can get in touch with us at [quantra@quantinsti.com](mailto:quantra@quantinsti.com)

<span>Alternatively, get in touch on: </span> <a href="https://www.facebook.com/quantinsti"><img width="24" src="https://user-images.githubusercontent.com/16116886/40958262-42153650-68b6-11e8-860e-d79237a89247.png"/></a>	<a href="https://twitter.com/quantinsti/"><img width="24" src="https://user-images.githubusercontent.com/16116886/40958261-41ee1d0e-68b6-11e8-8d65-c07c52758aee.png"/></a>	<a href="https://www.linkedin.com/company/quantinsti"><img width="24" src="https://user-images.githubusercontent.com/16116886/40958260-41c596a4-68b6-11e8-9bef-1420ea381b26.png"/></a>	<a href="https://plus.google.com/110772715968756646442/"><img width="24" src="https://user-images.githubusercontent.com/16116886/40958259-419ddd1c-68b6-11e8-94eb-306ff4f6d104.png"/></a>	<a href="https://www.youtube.com/user/quantinsti"><img width="24" src="https://user-images.githubusercontent.com/16116886/40958257-415647ea-68b6-11e8-892d-8a1425e79e58.png"/></a>
