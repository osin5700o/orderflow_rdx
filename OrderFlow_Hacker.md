# Order Flow

Order Flow


```text
[+] MODULE LOADED
```

## STEP 1 — MARKET MICROSTRUCTURE


- - Auction Market Theory (AMT) -
- - Exchanges -
- - Liquidity -
- - Dark Pools -


```text
[+] MODULE LOADED
```

## STEP 2 — ORDER TYPES


- - Market Orders -
- - Limit Orders -
- - Stop Orders -
- - Stop-Limit Orders -
- - Iceberg Orders -
- - Hidden Orders -
- - Passive Orders -
- - Aggressive Orders -


```text
[+] MODULE LOADED
```

## STEP 3 — LIMIT ORDER BOOK (LOB)


- - Bid -
- - Ask -
- - Mid Price -
- - Spread -
- - Order Book -
- - Depth of Market (DOM) -
- - Resting Orders -
- - Executed Orders -

```text
[+] MODULE LOADED
```

## STEP 4 — BID-ASK SPREAD & LIQUIDITY


- - Visible Liquidity -
- - Hidden Liquidity -
- - Liquidity Pools -
- - Liquidity Voids -

```text
[+] MODULE LOADED
```

## STEP 5 — MARKET DEPTH & IMBALANCE


- - Market Depth -
- - Order Book Imbalance -
- - Liquidity Stacking -
- - Liquidity Pulling -


```text
[+] MODULE LOADED
```

## STEP 6 — VOLUME PROFILE & MARKET PROFILE


- - Volume Profile -
- - Point of Control (POC) -
- - Value Area -
- - Value Area High (VAH) -
- - Value Area Low (VAL) -
- - High Volume Nodes (HVN) -
- - Low Volume Nodes (LVN) -
- - Acceptance -
- - Rejection -


```text
[+] MODULE LOADED
```

## STEP 7 — HEATMAP


- - Heatmaps -
- - Stacked Imbalances -
- - Heatmap Liquidity -
- - Order Flow Visualization -
- - Bookmap Concepts -
- - Stacking -
- - Pulling -


```text
[+] MODULE LOADED
```

## STEP 8 — ABSORPTION VS AGGRESSION


- - Absorption -
- - Aggression -
- - Absorption Zones -
- - Exhaustion -
- - Trapped Traders -
- - Failed Breakouts -


```text
[+] MODULE LOADED
```

## STEP 9 — ICEBERG & HIDDEN LIQUIDITY


- - Iceberg Orders -
- - Hidden Orders -
- - Hidden Liquidity -
- - Iceberg Detection -


```text
[+] MODULE LOADED
```

## STEP 10 — STOP HUNTS & LIQUIDITY POOLS


- - Stop Hunts -
- - Stop Runs -
- - Liquidity Sweeps -
- - Liquidity Grabs -
- - LIQUIDITY POOLS -
- - Liquidity voids -
- - Garbage Liquidity -
- - Buy-Side Liquidity -
- - Sell-Side Liquidity -


```text
[+] MODULE LOADED
```

## STEP 11 — TICK DATA & BOOK RECONSTRUCTION


- - Tick Data -
- - Quote Data -
- - Trade Data -
- - Tick Replay -
- - Tick Aggregation -
- - Book Reconstruction -
- - Event Processing -


```text
[+] MODULE LOADED
```

# [DATABASE] TERMS OF ORDERFLOW


- **Tick** — The minimum price movement of a trading instrument.
- **Tick size** — The smallest allowable increment between different prices.
- **Tick value** — The monetary value of one tick for a contract.
- **Contract** — A traded instrument (e.g., futures contract, option contract).
- **Exchange** — The marketplace where instruments are listed and trades occur.
- **Bid** — The highest price a buyer is willing to pay.
- **Ask (Offer)** — The lowest price a seller is willing to accept.
- **Bid-Ask Spread** — The difference between the best ask and best bid.
- **Mid Price** — The midpoint of the best bid and best ask.
- **Last Price** — The price of the most recent trade.
- **Trade** — An executed transaction between buyer and seller.
- **Fair Value** — Where buyers and sellers are agree.
- **Volume** — The quantity of contracts/shares traded over a period.
- **Traded Volume** — Actual traded quantity at a given time or price.
- **Volume at Price (VAP)** — Total volume executed at a specific price level.
- **Time & Sales (Tape)** — Stream/list of executed trades with time, size, and price.
- **Order Flow** — The stream of incoming orders and executed trades over time.
- **Order Book** — The list of current bids and asks (resting orders) by price/size.
- **Level 1** — Best bid/ask and last trade (top-of-book data).
- **Level 2** — Market depth showing multiple price levels and sizes.
- **Depth of Market (DOM)** — Display of available quantity at multiple price levels.
- **Market Order** — An order to buy/sell immediately at the best available price.
- **Limit Order** — An order to buy/sell at a specified price or better.
- **Stop Order (Stop Loss)** — An order that becomes a market order once a price trigger is hit.
- **Stop-Limit Order** — A stop that becomes a limit order at the trigger.
- **Iceberg Order** — A large order split into visible and hidden portions to hide full size.
- **Hidden Order** — Order quantity not shown in the public order book.
- **Aggressive Order** — An order that takes liquidity (trades against resting orders).
- **Passive Order** — An order that supplies liquidity (rests in the book).
- **Maker** — A trader/order that adds liquidity (resting limit order).
- **Taker** — A trader/order that removes liquidity (market or aggressive order).
- **Liquidity** — Availability of volume at or near the current price.
- **Liquidity Provider** — Participant supplying resting orders.
- **Liquidity Taker** — Participant consuming resting liquidity.
- **Slippage** — Difference between expected and actual execution price.
- **Market Impact** — The effect of an order on subsequent prices.
- **Order Imbalance** — Unequal aggregate buy vs. sell interest at a price/time.
- **Volume Imbalance** — Difference in volume between bid-side and ask-side trades.
- **Bid/Ask Delta** — Difference between buy-side and sell-side executed volume.
- **Cumulative Delta** — Running total of signed volume (buy minus sell) over time.
- **Execution** — Process of matching and filling an order.
- **Matching Engine** — Exchange component that matches incoming orders with resting orders.
- **Market Depth** — Aggregate visible size at each price level.
- **Book Pressure** — Net resting size pressure on one side of the book (buy/sell).
- **Spoofing** — Illegal practice of placing orders to mislead then cancelling them.
- **Layering** — Placing multiple deceptive orders at different prices (illegal practice).
- **Price Ladder** — Vertical display of price levels with size (used in DOM).
- **Heatmap** — Visual display of liquidity accumulation or trade intensity over price/time.
- **Volume Profile** — Histogram of volume traded at each price over a time range.
- **VWAP (Volume Weighted Average Price)** — Average price weighted by volume over a period.
- **TWAP (Time Weighted Average Price)** — Average price evenly weighted over time.
- **Order Size** — Quantity of contracts/shares in an order.
- **Block Trade** — Very large, often negotiated trade executed off-exchange or with special reporting.
- **Order Slicing** — Breaking a large order into smaller pieces to reduce impact.
- **POV (Percent of Volume)** — Execution algorithm that targets a set percentage of market volume.
- **Rebate / Maker-Taker Fee** — Fee/rebate structure rewarding makers or charging takers.
- **Price Discovery** — Process by which markets arrive at fair price through trades/quotes.
- **Opening Auction** — Matching mechanism at market open to determine starting price.
- **Closing Auction** — Auction at session close for final price discovery.
- **Continuous Auction** — Normal continuous trading outside auction periods.
- **Matched Trade** — Trade executed by a matching engine between two orders.
- **Settlement** — Transfer of security ownership and payment after a trade.
- **NOII (Net Order Imbalance Indicator)** — Indicator of buy/sell imbalance before auction.
- **Market Data Feed** — Stream of quotes and trades from an exchange or aggregator.
- **Feed Handler** — Software component parsing exchange market data.
- **Latency** — Delay between an event and its visibility to participants.
- **Exchange Latency** — Time delay inside an exchange or across networks.
- **Latency Arbitrage** — Exploiting speed differences to profit from stale quotes.
- **Timestamp** — Time recorded for quotes/trades (important for sequencing).
- **Trade Size** — Size of an executed trade.
- **Resting Order** — Order present in the book waiting to be matched.
- **Aggressor Side** — Side (buy or sell) that initiated the trade (took liquidity).
- **Passive Side** — Side that provided the liquidity which got taken.
- **Price Level** — Specific price row in the order book.
- **Best Bid / Best Ask** — Highest bid and lowest ask at top of book.
- **Stacking** — Adding multiple orders at the same price level to create depth.
- **pulling** - Reducing multiple orders at the same price level to create light.
- **Dark Pool** — Private trading venue where order details are not displayed publicly.
- **On-Exchange vs Off-Exchange** — Whether trade occurs on the public exchange or elsewhere.
- **Aggressive Volume** — Volume that resulted from taker/aggressive orders.
- **Passive Volume** — Volume resulting from makers/resting orders being taken.


---

# [CORE TARGETS] MAIN CONCEPT


- *Liqudity area Ditection*
- *Liqudity Grab & sweep by heatmap*


---

# [TOOLS] BEST SOFTWARE

- *Bookmap*
- *Deepcharts*
- *ATAS or Motivewave*
