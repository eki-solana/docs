# Traditional Continuous Trading

Most markets operate on a continuous, first-come-first-served basis through Central Limit Order Books [(CLOBs)](https://en.wikipedia.org/wiki/Central_limit_order_book) or Automated Market Makers [(AMMs)](https://chain.link/education-hub/what-is-an-automated-market-maker-amm). Orders are processed one at a time, immediately as they arrive.

### Toxic MEV

In a blockchain however, transactions are batched into blocks. These transactions are typically processed sequentially inside a block. But transaction ordering within blocks becomes a playground for extracting value. Block producers can include, exclude and reorder transactions which allows for sandwich attacks or other extractive strategies which [extract hundreds of thousands of dollars per day from Solana users](https://x.com/jarxiao/status/1802759996020547734).

### Introducing a new market structure

Mato combines two powerful mechanisms to mitigate toxic MEV and removes the need for liquidity providers:

- Frequent batch auctions that ensure fair price discovery
- Continuous swap streaming that maintains market efficiency
