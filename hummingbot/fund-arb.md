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
- [FundingRate on coinglass](https://www.coinglass.com/FundingRate)  
  Favorites 4 coins, filter 4 CEX
- [Funding rates on arbitragescanner.io](https://arbitragescanner.io/funding-rates)
- [Crypto Arbitrage Scanner with CEX select](https://cryptoarbitragescreener.com)
- [coinank funding Rate](https://coinank.com/fundingRate/current)  
    simple, ~10 exchanges 
- [Hyperliquid Funding Comparison](https://app.hyperliquid.xyz/fundingComparison)  
  Data only for Hyperliquid, Binance, Bybit
  
## Tasks
- [ ] Need check quote on other DEX. Use Perp Dex tools  
- [ ] Multi Exchange Funding Arb(locking for script)
    The strategy aims to exploit funding rate arbitrage opportunities across multiple exchanges. It is conceptually similar to the v2_funding_rate_arb.py script, but extended and generalized. The main purpose is to capture profitability when funding discrepancies arise between exchanges, while ensuring robust execution and risk management.

## Hummingbot
```
create --script-config funding_rate_arb
```
