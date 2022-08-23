# 3_Stock_Monty

This jupyter notebook will look at the future value of a portfolio of $15,000 invested 
in differently weighted combinations of 'NKE', 'T' and 'XON' stocks. The Monte Carlo
Simulation will be used for forecasting and the Alpaca API will pull the historical data
of the stocks of interest. Finally, a conclusion will be made about what distribution
of stocks should yield the highest return.

To Run this you will need your own API key and API secret key for the Alpaca API.
Set up an account at [Alpaca](https://alpaca.markets/) for free and go to your
paper account to find the keys for the API. Save these in a **.env** file in the
same directory as this jupyter notebook and title them,
ALPACA_API_KEY = '>Your Key Here<'
ALPACA_SECRET_KEY = '>Your Key Here<'

---

## Technologies

Language: Python 3.9.12

Libraries used:

[Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - For the creation and visualization of Data Frames

[Jupyter Labs](https://jupyter.org/) - An ipython kernel for interactive computing in python

[OS]()

[Dotenv]()

[Alpaca Trade API]()

[MC Forecast Tools]()



---

## Installation Guide

If you are using an anaconda or a conda environment chances are pandas, os and jupyter labs are already installed in your virtual environment 

If they are not then run:
```python
    pip install pandas
    pip install jupyterlab
    pip install os
```

dotenv and alpaca_trade_api need to be installed separately as they do not come in the anaconda environment.
You will need to run:
```python
    pip install dotenv
    pip install alpaca-trade-api

A copy of the **'MCForecastTools.py'** file is included in this repository.

---

## Usage

To run this jupyter lab notebook you will need to use GitBash and navigate to where you have exported the files associated with this project.

Next you will need to perform the following

![Activate](images/activate_lab.png)

This will open a jupyter lab notebook in your default browser. 

Next open **'risk_return_analysis.ipynb'** and click ![double_arrow](images/doube_arrow.png)

This will run the entire notebook. Make sure to follow the pseudocode to see what has been coded and what is being displayed. 

---

## Highlights:

Here are a few snippets of what you can find in this project

### Cumulative Returns:

![whale_overaly](images/whale_overlay.png)

### Volatility:

![volatility](images/volatility.png)

### Sharpe Ratios:

![sharpe_ratios](images/sharpe_ratios.png)

---

## Contributors

Created by Silvano Ross while in the UW FinTech Bootcamp
> Contact Info:
> email: silvanoross3@gmail.com |
> [GitHub](https://github.com/silvanoross) |
> [LinkedIn](https://www.linkedin.com/in/silvano-ross-b6a15a93/)

---

## License

[MIT](LICENSE)



