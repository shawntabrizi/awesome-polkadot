# The Polkadot Playbook

The minimum set of information you need to be able to explain Polkadot to others.

## What is Polkadot?

- Polkadot is a scaling solution for Web3[^1] applications and services.
- Polkadot scales through data and execution sharding, allowing for parallelized throughput.[^2]
- Polkadot provides shared security and secure interoperability to services build on it.[^3]
- Polkadot creates abundant, flexible, and high quality blockspace.[^4]
- Polkadot uses a novel "cynical" rollup to provide fast finality while using minimal resources.[^5]

## What unique things can you do on Polkadot?

- Build applications which execute automatically (without initial user input).
- Build applications with full control over block construction and transaction execution.[^20]
- Build applications which dynamically scale up and down execution cores.
- Build applications which execute at sub-second speeds.[^21]
- Build applications that can permissionlessly upgrade and evolve over time.[^22]

## Why choose Polkadot?

- Billions of dollars of economic security provided to itself and applications running on it.
- Fast finalization times, on average under 30 seconds.[^31]
- Executing and scaling on standard "gaming" hardware.[^32]
- Polkadot SDK is the most robust and flexible blockchain framework.[^34]
- Secure cross-chain interoperability through trustless bridging protocols.[^35]

## Where is Polkadot leading?

- 50+ active rollups live on Polkadot.[^40]
- Among the highest Nakamoto coefficients in the blockchain ecosystem.[^41]
- 2nd largest developer community after Ethereum.[^42]
- Blazing fast execution speeds compared to other blockchain VMs.[^43]
- One of the largest functioning DAOs, managing the functionality of the network and tens of millions of dollars in assets for development.[^44]

## Polkadot Comparisons

- Ethereum: Polkadot realized Ethereum's scaling vision first, conceived and delivered by co-founder Dr. Gavin Wood.[^51]
- Solana: Unlike Solana, Polkadot scales without compromising Web3 principles of decentralization and security.[^52]
- Cosmos: Unlike Cosmos, Polkadot provides shared security and secure interoperability.[^53]
- Avalanche: Subnets in Avalanche are not as flexible as applications on Polkadot, and subnets do not provide shared security or secure interoperability.[^54]
- Layer 2s: Layer 2 solutions face performance issues, unpredictable fees, and fragmented interoperability due to non-native support for rollups.[^55]

[^1]: Learn more about Web3:
	- The first time the term "Web3" was used: https://gavwood.com/dappsweb3.html
	- A blog post describing the importance of Web3: https://gavofyork.medium.com/why-we-need-web-3-0-5da4f2bf95ab

[^2]: Explanation of sharding on Polkadot: https://polkadot.com/blog/polkadot-v1-0-sharding-and-economic-security

[^3]: A high level overview of shared security: https://www.youtube.com/watch?v=uKQOSPfM-W0

[^4]: A blog post explaining the term "blockspace": https://www.rob.tech/blog/polkadot-blockspace-over-blockchains/

[^5]:
	- The ELVES paper, formally describing Polkadot's cynical rollup: https://eprint.iacr.org/2024/961
	- A tweet summary of the ELVES paper: https://x.com/rphmeier/status/1807884271157187007

[^20]: For example:
	- Build applications where end-users pay no transaction fees.
	- Build applications more resilient to MEV.
	- Build applications which can prioritize tasks and processes.

[^21]: A demo of a Polkadot SDK blockchain producing blocks every .5 seconds: https://twitter.com/bkchr/status/1818027282688352591

[^22]: Learn about forkless runtime upgrades in Polkadot: https://wiki.polkadot.network/docs/learn-runtime-upgrades

[^31]: Learn more about cynical rollups:
	- Compare that to optimistic rollups which may take up to a week to finalize!
	- Cynical rollups actively check that a block is valid, rather than waiting for someone to report it is invalid. See ELVES paper footnote above.
	- Compared to "instant finality" consensus, block production is separated from finality, reducing network stalls: https://polkadot.com/blog/polkadot-consensus-part-1-introduction

[^32]: Compared to expensive and centralized machines needed for vertical scaling or ZK provers.
	- Hardware requirements for running a Polkadot Validator: https://wiki.polkadot.network/docs/maintain-guides-how-to-validate-polkadot#requirements

[^34]: Polkadot SDK is used throughout the entire blockchain ecosystem:
	- Polkadot and Kusama are built with the Polkadot SDK.
	- All 50+ live parachains, and many more in development, all use Polkadot SDK.
	- Many projects outside of Polkadot also use the Polkadot SDK: [Avail](https://www.availproject.org/), [Cardano](https://midnight.network/), [Entropy](https://entropy.xyz/), and more...

[^35]: Bridging in Polkadot can be broken down into internal bridges and external bridges:
	- Native bridging protocol for applications secured by Polkadot: https://wiki.polkadot.network/docs/learn-xcm-transport
	- An overview of external bridges on Polkadot: https://polkadot.com/blog/the-landscape-of-trustless-bridges-on-polkadot

[^40]: A list of active parachains on Polkadot: https://polkadot.subscan.io/parachain

[^41]: The Nakamoto Coefficient is one measure of decentralization and resilience.
	- A third party service comparing the Nakamoto Coefficient: https://nakaflow.io/

[^42]: Graph of blockchain developer ecosystems: https://twitter.com/Polkadot/status/1577016988697706496
	- The raw data is being generated using this open source repo: https://github.com/electric-capital/crypto-ecosystems

[^43]: PVM and other VM benchmarks: https://github.com/koute/polkavm/blob/master/BENCHMARKS.md

[^44]: Information about the Polkadot DAO: https://polkadot.com/platform/dao
	- Polkadot Treasury Account: https://polkadot.subscan.io/account/13UVJyLnbVp9RBZYFwFGyDvVd1y27Tt8tkntv6Q7JVPhFsTB

[^51]: Polkadot comparison document to Ethereum:
	- https://wiki.polkadot.network/docs/learn-comparisons-ethereum-2

[^52]: Solana is better described as a distributed database, than a Web3 product.
	- Information about the scalability trilemma: https://ethereum.org/en/roadmap/vision/
	- Solana scales vertically while Polkadot scales horizontally.
	- Since January 2022, Solana has seen around half a dozen significant outages and 15 partial or major outage days: https://cointelegraph.com/news/solana-outage-client-diversity-beta

[^53]: Polkadot comparison document to Cosmos:
	- https://wiki.polkadot.network/docs/learn-comparisons-cosmos

[^54]: Polkadot comparison document to Avalanche:
	- https://wiki.polkadot.network/docs/learn-comparisons-avalanche

[^55]: Polkadot comparison document to Layer 2s and Rollups:
	- https://wiki.polkadot.network/docs/learn-comparisons-rollups
