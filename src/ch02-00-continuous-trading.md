# Traditional Continuous Trading

Markets that use Automated Market Makers [(AMMs)](https://chain.link/education-hub/what-is-an-automated-market-maker-amm) or Central Limit Order Books [(CLOBs)](https://en.wikipedia.org/wiki/Central_limit_order_book) are called continuous markets as trades can happen at any moment. Orders are processed one at a time, immediately as they arrive.

### Toxic MEV

In a blockchain however, transactions are batched into blocks. These transactions are typically processed sequentially inside a block. But block producers can include and reorder transactions which allows for sandwich attacks or other extractive strategies which [extract hundreds of thousands of dollars per day from Solana users](https://x.com/jarxiao/status/1802759996020547734).

### Mato is the most continuous market

As we will explain later, you will see that Mato is the most continuous market by introducing the concept of a streaming swap which not only mitigates MEV but also removes the need for liquidity providers.
