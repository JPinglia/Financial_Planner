# Jas's Financial Planner with Simulations

The goal of this program is to create financial planner and analysis tool, which can be used to get current portfolio value. The program can gather values from the ownership of cryptocurrency(crypto) assets in a crypto-wallet via a free alternative API. Traditional stocks and bond portfolio values is generated though the use of an Alpaca SDK. Values are aggregated and the program recommends if you have the funds necessary for a emergency fund. 

A Monte Carlo simulation is then ran on the stock and bond portfolio based on 3 previous years of data. The simulation are run for two time intervals: 
1) 30 years
2) 10 years

Based on the simulation results, we estimate the likely hood, members of a credit union can retire based on simulation outcomes. 

# Technologies

The program is written using Jupyter notebooks, for ease of code reading and code execution via code blocks. The program lays out a step-wise reporting and program execution. The code is run in a (Dev) environment with the use of the following libraries:
1. Pandas
2. Pathlib
3. Matplotlib
4. OS – Library
5. Request Library
6. Dotenv
7. Alpaca trade api 

# Installation Guide

Python 3.7.11 - base installation is required. 
PIP install the following modules:
a) jupyterlab
b) requests
c) mcmurray json
d) python-dotenv
e) alpaca-trade-api

**A MCForecasts Tools python file will be required to allow for Monte Carlo Simulations. File is included in this repo.**

# Usage

Program generates protfolio composittion of cryptos/Bonds/Stocks portfolio based on current prices and weighting schemes. 

![portfolio_composition_pie](https://user-images.githubusercontent.com/95830866/151717055-7949afd5-08c1-4574-bbea-d644a24f7e7c.PNG)

Monte Carlo Simulation is run of the stock and bonds in the protfolio based on 3 years of historical data. This predicts future protofolio valuations 30yrs in the future.

![simulation_30yr](https://user-images.githubusercontent.com/95830866/151717096-d2b69048-3911-49a0-95b8-076bbeaf9a68.PNG)

A probability distrubition is generated based on the likelihood of outcomes. 

![probability_dist_30yr](https://user-images.githubusercontent.com/95830866/151717144-7c7d5a3a-d1d3-46a6-a9c5-c1640acd2372.PNG)

# Contributors

This program was developed with base code developed by the Rice-boot-camp. Code was created and added by JPinglia.

# License

License for this project and associated file is public.
