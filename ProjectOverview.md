# Stock/Crypto Investing for Rookies

12.11.2021

## Overview
Many people hear about the new generation of retail investors that are using online trading platforms to invest in stocks and cryptocurrencies, and they’re interested in getting started with investing themselves, but they don’t know enough about investing yet to be comfortable jumping in. Suppose there existed a service that could ‘get to know’ the risk-tolerance of an investor, and based on the responses provided, could provide guidance to help them ease into their investing experience! The guidance would be based on the new investor’s investable assets, risk appetite, investment goals, and time horizon.

## Goal

Help investors with interest, but little or no knowledge of investing in publicly tradable stocks and cryptocurrencies.

## Specifications

The interface would begin by walking a potential client through a risk-tolerance questionnaire (RTQ), and based on their responses, provide a recommendation for the percentage of the client’s portfolio that would be appropriate to invest in stocks and cryptocurrency. The output shows the potential client hypothetical future valuations of the assets they invest in, based on time-series analysis and recurrent neural network modeling.
Designed as an educational tool, the output will focus on the challenges of predicting future prices, and will highlight utilizing sentiment analysis to address the question of what other market participants are interested in investing in.

## Outcomes

The interface would conclude by requesting the client to implement the proposal on their preferred online trading platform.

## Future Enhancements

-Incorporate additional predictive algorithms utilizing additional modules/libraries, such as PyCaret and Dataiku, to gain a sense of what future asset values could be.
-Offer additional cryptocurrency investments, and subject the cryptocurrency guidance to the sentiment analysis and RNN projections the stock universe is subjected to.
-Utilize algorithmic trading to implement and manage investment guidance.

## Parameters

To develop the investment portfolio, we will begin with a stock ‘universe’ of the twenty most-discussed stock investments on Twitter as of the current calendar quarter. The analysis will also utilize the Long short-term memory (LTSM) recurrent neural network (RNN) to provide the investor with a project of what their investment’s asset price might be in the days following their investment.

## Data Sources

1. Twitter API
2. Yahoo Finance API
3. Keras
4. nltk
5. sklearn
6. Nasdaq DataLink (Quandl) API

## RTQ Scoring:

*Very Aggressive - 14% Stock, 5% Crypto allocation of Investable Assets
*Aggressive - 12% Stock, 4% Crypto allocation of Investable Assets
*Moderate - 10% Stock, 3% Crypto allocation of Investable Assets
*Conservative - 5% Stock, 2% Crypto allocation of Investable Assets
*Very Conservative - 2% Stock, 1% Crypto allocation of Investable Assets