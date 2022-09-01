# module-5-financial-planner

This application You’ll create two financial analysis tools by using a single Jupyter notebook:

1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.



USAGE
--
clone repository and run in jupyter notebook

libraries needed to import:
import os,
import requests,
import json,
import pandas as pd,
from dotenv import load_dotenv,
import alpaca_trade_api as tradeapi,
from MCForecastTools import MCSimulation,

%matplotlib inline


EXAMPLES
--
Simulation line plot of 30 years 


Contributers
--
David Hutsell

Licenses
--
UW fintech bootcamp


![image](https://user-images.githubusercontent.com/107014664/187589688-8051671b-7ab8-4ec7-85b5-2eec27e8a634.png)

Pie chart that shows total holding of cyrpto and stocks/bonds holdings


![image](https://user-images.githubusercontent.com/107014664/187589791-e6d8afb7-65e3-453d-b61b-cdc01a9eedc2.png)

