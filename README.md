# Black Scholes Maluation

Black Scholes is a popular options pricing model. It assumes logonormal distribution and derives the price of an option. 
This model is suitable to value only European style option and its not fit to value American Options, as it does not consider the option of exercise before the expiration date.
Thee following information is used in the valuation:
+ a. Strike price
+ b. Current price
+ c. Time to expiration
+ d. Expected dividend yield
+ e. Expected interest rate
+ f. Expected volatility

This model follows a series of assumptions. (Its these assumptions that make the formula not so handy in a practicle scenario. The derivations may look good on a theoratical note as most of the assumptions are very rigid in nature and are barely seen in a practicle scenario)
+ a. Consider European style options
+ b. No dividend payments occur during the option life span
+ c. Markets are efficent
+ d. Volatility and risk free rate remains constant
+ e. Returns of the asset follow a normal distribution

By inputing the factors in the formula, the value of the options cam be derived. The model makes options less of a gamble as it gives it a mathematical value. It assumes that stock prices follow a logonormal distribution as asset prices cannpot be negative as its bound by 0. 
