# Order Streaming

Trades can be settled in one slot like in other DEXs but in addition, Mato allows the streaming of swaps over a time horizon.

Here’s how it works:

1. User specifies a trade amount and a duration. (e.g., 10 tokens streamed over 50 slots.)
2. Each slot gets an equal portion of the total trade (e.g., 0.2 tokens per slot).
3. At the end of each slot:
   - A market-clearing price is recalculated based on all active orders.
   - Assets are swapped at this price.

This approach ensures:

- **Fair Markets:** As trades are distributed across many slots, reducing the likelihood of price manipulation.
- **Better Prices:** Streaming allows you to average out prices over time, reducing volatility and reducing your price impact.
