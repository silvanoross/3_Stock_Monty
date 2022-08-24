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

[OS](https://docs.python.org/3/library/os.html) - Miscellaneous operating system interface

[Dotenv](https://github.com/motdotla/dotenv) - Module to load environment variables 

[Alpaca Trade API](https://alpaca.markets/docs/) - API for the Alpaca trading platform

**MC Forecast Tools** - A copy of this module is included in the downloadable files for this project

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
```

A copy of the **'MCForecastTools.py'** file is included in this repository.

---

## Usage

To run this jupyter lab notebook you will need to use GitBash and navigate to where you have exported the files associated with this project.

Next you will need to type the following:

```python
    jupyter lab --ContentsManager.allow_hidden=True
```

This will launch a Jupyter Labs notebook containing the working files with the **allow_hidden** permission to view **.env** files.

This notebook uses the Alpaca API and you will need the two keys stated above in the description: 'ALPACA_API_KEY' AND 'ALPACA_SECRET_KEY'. Create a new **.env** file and store the values here.

It should look something like this:

```python
    ALPACA_API_KEY = '<YOUR KEY HERE>'
    ALPACA_SECRET_KEY = '<YOUR SECRET KEY HERE>'
```

Next open **'financial_planning_tools.ipynb'** and click the double arrow to run the notebook. Alternatively you can run each cell individually.

Make sure to follow the pseudocode to see the coding logic and fully understand what is being displayed.

Note - This may take a while to run as the Monte Carlo Simulation typically has a faily long run time. Expect around 1-2 minutes of waiting before notebook is complete.

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



