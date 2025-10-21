# Funding Arbitrage
dYdX quoted in hourly rates. Others (CEX) quoted in 8 hourly rates.  

## Path
1. Find opportunity
2. Check funding diff > min profit
3. Validate trade PNL before start
4. Execute long/short
5. collect funding payments and executors PNL
6. Close the positions when total PNL > min profitable PNL

## Resources
- [Android. Coingapp](https://play.google.com/store/apps/details?id=com.coingapp.android)
- [FundingRate on coinglass](https://www.coinglass.com/FundingRate)  
  Favorites 4 coins, filter 4 CEX
- [Funding rates on arbitragescanner.io](https://arbitragescanner.io/funding-rates)
- [Crypto Arbitrage Scanner with CEX select](https://cryptoarbitragescreener.com)
- [coinank funding Rate](https://coinank.com/fundingRate/current)  
    Only ~10 exchange, simple 
- [Perp Dex tools](https://ghzperpdextools.vercel.app)
- [hyperliquid Funding Comparison](https://app.hyperliquid.xyz/fundingComparison)  
  Data only for Hyperliquid, Binance, Bybit
- [connect hyperliquid_perpetual, Hummingbot](https://hummingbot.org/blog/funding-rate-arbitrage-and-creating-vaults-on-hyperliquid/#trading-with-hummingbot)

## Tasks
- [ ] Need check quote on other DEX. Use Perp Dex tools  

## Hummingbot
```
create --script-config funding_rate_arb
```
