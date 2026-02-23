# china-hk-market-data
I gathered daily stock data for each firm in the Hong Kong Stock Exchange and Shanghai Stock Exchange.

## HKEX-data-scraper
I scraped [this website](https://stockanalysis.com/list/hong-kong-stock-exchange/?__v=1771418419981) to get all the firms present, and I used the yfinance API and saved the data for each firm as `.pkl` files in the `data` folder.

## SSE-data-scraper
Similar methodology for the HKEX data, but I scraped [this website](https://english.sse.com.cn/markets/indices/data/list/constituents/index.shtml?COMPANY_CODE=000001&INDEX_Code=000001) instead.