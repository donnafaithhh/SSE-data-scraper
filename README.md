# china-hk-market-data
## HKEX-data-scraper
I gathered daily stock data for each firm in the Hong Kong Stock Exchange.

First, I scraped the [this website](https://stockanalysis.com/list/hong-kong-stock-exchange/?__v=1771418419981) to get all the firms present.

## SSE-data-scraper
I gathered daily stock data for each firm in the Shanghai Stock Exchange.

First, I scraped the Shanghai Stock Exchange Website to get all the firms present.
Then, I gathered daily data for each firm from the yfinance API and saved them as `.pkl` files. 
This should be in the `data` folder. 
