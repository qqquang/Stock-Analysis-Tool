# Stock Analysis Tool
 Developed a tool to analyze stock market trends and create visualizations with custom indicators.

## Usage

This project uses [TaLib](https://github.com/mrjbq7/ta-lib) library for some calculations, so [install](https://github.com/mrjbq7/ta-lib#installation) the TaLib library first.
Then, clone the project and install other requirements.

```bash
$ git clone git@github.com:SpiralDevelopment/crypto-hft-data.git
$ cd crypto-hft-data
$ pip3 install virtualenv
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

### Samples

- sample_tg_poster.py - Gets the ohlc data from local database and checks if the last candle has RSI divergence
- sample_binance.py - Gets the data from Binance API and plots ALL detected RSI divergences during that period

## Result

Here is the result of detected RSI divergences for BTCUSDT pair during 22.11.2020 - 22.03.2022 period in daily timeframe 

<p align="center"><img src="./btcusdt_divergences.PNG"></p>

- Blue lines - Regular and hidden Bullish divergences
- Red lines - Regular and hidden Bearish divergences 

## License
[MIT License](https://github.com/SpiralDevelopment/RSI-divergence-detector/blob/main/LICENSE)
