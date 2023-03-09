# Equity Derivatives Pricing Tools


Link to functioning app: https://gdelacruzv-option-pricing-ap-streamlit-option-pricing-v2-vr4d6r.streamlit.app/

## Introduction  
This repository represents simple web app for calculating option prices (European Options). It uses three different methods for option pricing:  
1. Black-Scholes model    
2. Monte Carlo simulation    
3. Binomial model    

Each model has various parameters that user needs to import:  

- Ticker  
- Strike price  
- Expiry date  
- Risk-free rate  
- Volatilit

Option pricing models are implemented in Python 3.7. Latest spot price, for specified ticker, is fetched from Yahoo Finance API using pandas-datareader. Visualization of the models through simple web app is implemented using streamlit library.

This implementation was done as project work on the course Financial MAthematics for Mssters in Quantitative Economics.
