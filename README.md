# cryptocurrencyeda

This is a Python package to analyze historical cryptocurrency prices and performance through simple exploratory data analysis including calculations and plotting. Data is sourced from Yahoo Finance. There are four functions that are included in this python package which are described in more detail below. Cryptocurrency investors and enthusiasts can use this package to analyze cryptocurrencies of interest.


There are existing Python libraries to access information of cryptocurrency such as [cryptocompare](https://github.com/lagerfeuer/cryptocompare) and [cryptofeed](https://github.com/bmoscon/cryptofeed). There are also existing Python libraries to visualize financial data such as [mplfinance](https://github.com/matplotlib/mplfinance).
However, there is no integrated Python library for accessing, analyzing, and visualizing cryptocurrency data altogether. Therefore, we want to build a simple tool that can facilitate simple cryptocurrency data analysis all at once.

## Function List

The package contains the following four functions:

- `retrieve_historical_data`: downloads historical data from a cryptocurrency exchange using an an http request from a cryptocurrency exchange.

- `plot_price`: generates and visualizes a plot of the price of the cryptocurrenty inputted over a period of time.

- `growth_rate`: performs calculation of daily growth rate on historical cryptocurrency price time series data.

- `avg_daily_return`: performs calculation of the average daily return of the inputted cryptocurrency price.
## Installation

```bash
$ pip install cryptocurrencyeda
```

## Usage

- TODO

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`cryptocurrencyeda` was created by MDS Students from Group-11 for course 524. It is licensed under the terms of the MIT license.

## Credits

`cryptocurrencyeda` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
