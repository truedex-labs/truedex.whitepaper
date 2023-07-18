`TrueDEX White Paper`

# True DEX
**an order-book based pure decentralized exchange**


# Motivation
Most DEXes exist today run on top of EVM type of blockchains and thus require traders to pay gas fees and have to suffer low on-chain and transaction speed. In order to improve the trading experience, automatic market maker (`AMM`) type of DEXes have been thus introduced to achieve a simple trading experience to both traders and market makers. However they still suffer from the aforementioned issues. In addition, traders are deprived of their rights in choosing the side and price of their orders due to lack of order-book feature support.

There are some other DEXes that offer an order-book feature to mimic the traditional centralized exchange. However due to their underlying networks are still mostly clones of Ethereum and adoption of EVM smart contract technology, their on-chain processing speed is still very much limited. In order to circumvent the technology limitations imposed by the underlying layer-1 network, these DEXes switch to either central limit order book (CLOB) or so-called layer-2 network which is also very much centralized.

Therefore, it has been much needed for the general crypto community for a truly decentralized technology stack that can meet the following technical traits:

- decentralized: booking, matching and settlement fully on-chain
- high performance: can support matching of up to 1000 orders in one second in a single shard; The more shards, the higher matching speed;
- gas free: front-running cannot be tolerated
## Supported Trading Pairs

For a start, following trading pairs will be first supported:

- BTC/USDT
- ETH/USDT
- BNB/USDT
- TRX/USDT

There can be more to be added and it will be open to the community to decided which trading pairs to be supported in future.

## Transaction Fees

`TrueDEX` founding team decides not to issue a new token as most `DeFi` platforms would do. Instead, `TrueDEX` will solely rely on transaction fees as the sole source of revenue. Only in a very late stage as requested and approved by the community will a new token to be issued to convert the value of transaction fees into the new token.

The transaction fees will be charged of `0.3%` of each transaction volume from the taker only and the fees will be further splitted/shared with the following parties:

- `40%` goes to the counter-party order makers (maker will be rewarded instead of charged of the fees);
- `10%` goes to the account referrer or creator;
- `50%` goes to the team for system operation support and continuous development of the technology stack;
## Underlying blockchains

[Armonia blockchain](https://amax.network) will be first adopted for its native support of WASM smart contract technology. In future, other WASM chains like EOS, WAS etc will be also considered for deployment to embrace their corresponding communities.

## Cross-chain bridge