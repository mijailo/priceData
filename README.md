# priceData

Repository with financial data.

## Description

1. `SP500_N322_T4431_adjclose.csv`: A subset of S&P500 companies' daily prices (adjusted close) quoting without interruption, from `'2006-01-03'` to `'2023-08-10'`. Each column has the syntax `${ticker}_${sector}`, where `${ticker}` identifies a company and `${sector}` indicates its sector according to the [GICS standard](https://www.investopedia.com/terms/g/gics.asp).
2. `SP500_Index_T4431_adjclose.csv`: The daily prices (adjusted close) of the S&P500 Index, from `'2006-01-03'` to `'2023-08-10'`.
3. `sp500_N322_T4431_metaData.csv`: The metadata describing the companies included in the `SP500_N322_T4431_adjclose.csv` file, such as company name, sector, industry and exchange.
