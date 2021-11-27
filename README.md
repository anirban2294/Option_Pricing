# Option_Pricing

Input Files:
1. The call and put option prices (bid & offer) for three maturities:
    a. SPX_options.csv
    b. SPY_options.csv

2. The discount rate on this day
    a. zero_rates_20201201.csv


Option_Formulas:

The pricing formulas of the following European options are implemented in Python for each of the subsequent pricing models:
Option Types:
    1. Vanilla call/put
    2. Digital cash-or-nothing call/put
    3. Digital asset-or-nothing call/put
Models:
    1. Black-Scholes model
    2. Bachelier model
    3. Black76 model
    4. Displaced-diffusion model


Model Calibration:

The fitted implied volatility smile was plotted against the market data for the following models.
    1. Displaced-diffusion Model
    2. SABR Model (B = 0.7 was set)
The model parameters alpha, beta, rho and mu was reported for the calibrated model.


Static Replication:

We price the following derivative contracts for the subsequent models:
Contracts:
    (provided in the jupyter file)

Models:
    1. Black-Scholes model
    2. Bachelier model
    3. SABR model