# Xvantage Neural Quant

A live Kalshi-style neural quant dashboard for crypto binary options and market signal monitoring.

## Features

- Live price feed from Binance.US and CoinGecko fallback
- 15-minute epoch countdown and strike tracking
- Kalshi-style binary option probability model
- Multi-signal consensus engine using MACD, RSI, Bollinger, Donchian, ATR
- Real-time synthetic neural order feed
- Dynamic chart with strike and sigma bands

## Run locally

1. Open `index.html` directly in a browser, or
2. Start a local server:

```bash
npm install
npm start
```

Then open:

- http://localhost:3000

## Notes

- This dashboard is designed as a front-end prototype.
- Live market access depends on browser CORS and external API availability.
- The app includes fallback stochastic data if the APIs are unavailable.
