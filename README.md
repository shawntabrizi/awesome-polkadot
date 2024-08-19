# awesome-polkadot

An opinionated list of awesome resources in the Polkadot ecosystem.

## Goal

The problem I found with other awesome lists is that there are so many links and resources, that quality is lost to the noise, and approachability becomes overwhelming.

Unlike other awesome lists, this is NOT meant to be a comprehensive list for all options available in the Polkadot ecosystem. Instead, this will be a very opinionated and unapologetic list of resources which I find useful and that I use myself.

You can feel confident that if you use these same resources, they will work and provide a great experience.

If you find any problems with any of the resources in this list, please [open an issue](https://github.com/shawntabrizi/awesome-polkadot/issues).

## Education

Here are my favorite resources to get you caught up with all things Polkadot.

Developer educational resources can be found in the [Developer](#developer) section below.

### The Basics

If you are just getting started in the Polkadot ecosystem, the following resources will be super useful to begin your journey to learn about and understand Polkadot.

- [The Polkadot Homepage](https://polkadot.com/)

	This is the official homepage for the Polkadot Network. Follow the story of Polkadot told by this site and learn the basics.

- [The Decisions of Polkadot](https://www.youtube.com/watch?v=mQckxpMUBo8)

	This is a presentation that I gave describing the philosphies, goals, and decisions of developing the Polkadot Network. Obviously there is little bit of bias here, but I think this is a great resource, not to understand what Polkadot is today, but what Polkadot is in general.

### More Advance Resources

Now that you have covered the basics of Polkadot, it's time to dive a deeper.

- [Demystifying JAM](https://blog.kianenigma.nl/posts/tech/demystifying-jam/)

	[JAM](https://graypaper.com/) is the next evolution of the Polkadot protocol, which is still under heavy development at the time of writing. This blog post was written by Polkadot Core Developer, [Kian Paimani](https://twitter.com/kianenigma) and will walk you through the evolution of the Polkadot protocol from Polkadot 1.0, 2.0, and finally the future plans with JAM.

- [Plaza - Smart Contracts on Polkadot](https://www.rob.tech/blog/plaza/)

	In this blog post, Polkadot's co-founder [Rob Habermeier](https://twitter.com/rphmeier/) outlines his vision for a scalable Polkadot system chain, which includes key resources of the Polkadot network like Assets, Staking, and Governance, with an additional programmability layer of EVM smart contracts.

## Community

If you are looking to immerse yourself with the best parts of the Polkadot community, check out these resources.

The terms Circles, Catalysts, and Champions, comes from the book [The Starfish and the Spider](https://faith2share.net/perch/resources/starfish-spider-book-summary.pdf).

### Circles

Circles are the decentralized communities where you can directly participate in discussions about the past, present, and future of Polkadot.

- [The Polkadot Forum](https://forum.polkadot.network/)

	A space for long form and long term discussions about the Polkadot network.

- [Polkadot StackExchange](https://substrate.stackexchange.com/)

	A space for technical questions and answers about Polkadot and the Polkadot SDK.

- [Polkadot SubSquare](https://polkadot.subsquare.io/)

	A space for discussions about Polkadot Governance and Treasury Spending.

- [Polkadot Watercooler](https://matrix.to/#/#polkadot-watercooler:parity.io)

	A [Matrix](https://matrix.org/) chat room for general discussion of Polkadot.

### Catalysts

You should follow these high quality core contributors to keep up to date with the latest developments of the Polkadot protocol.

- https://twitter.com/rphmeier
- https://twitter.com/bkchr
- https://twitter.com/kianenigma
- https://twitter.com/OliverTaleYazdi
- https://twitter.com/XiliangChen
- https://twitter.com/joepetrowski
- https://twitter.com/GehrleinJonas

### Champions

You should follow these high quality ecosystem agents to keep up to date with what is going on in the Polkadot ecosystem.

- https://twitter.com/alice_und_bob
- https://twitter.com/LeemoXD
- https://twitter.com/itsbirdo_
- https://twitter.com/ParaNodes
- https://twitter.com/GldnCalf
- https://twitter.com/BillLaboon

## Users

Are you looking to be an end user of Polkadot or services built on Polkadot?

Check out these resources to get yourself Onboarded.

### Wallets

My favorite Wallets in the Polkadot Ecosystem:

- Mobile Wallet: [Nova Wallet](https://novawallet.io/)
- Web Extension: [Talisman](https://www.talisman.xyz/)
- Hardware Wallet: [Ledger](https://www.ledger.com/coin/wallet/polkadot)

## Developer

Are you a software developer interested in building in the Polkadot ecosystem?

These resources are for you.

### Tooling

- [The Polkadot SDK](https://github.com/paritytech/polkadot-sdk)

	All development in Polkadot basically revolves around the Polkadot SDK. This project is composed of sub-projects: Substrate, Polkadot, Cumulus. The Polkadot SDK includes useful binaries for doing development.

	Install those binaries locally by running:

	```sh
	cargo install --git https://github.com/paritytech/polkadot-sdk/ polkadot polkadot-parachain-bin staging-chain-spec-builder polkadot-execute-worker polkadot-prepare-worker
	```

- [Zombienet](https://github.com/paritytech/zombienet)

	In order to run a parachain, you must simulate a Polkadot network with a relay chain and multiple validators. Zombienet can do this for you with a simple CLI and config. Very useful for doing local testing on a "live network" starting from genesis.

- [Chopsticks](https://github.com/AcalaNetwork/chopsticks)

	Chopsticks is a tool that allows developers to simulate and test complex blockchain scenarios without deploying to a "live network" (i.e. no need for a relay chain). It is particularly useful at forking any already-live chain, modifying it, and then testing the affects of your modifications.

- [Polkadot SDK Version Manager](https://github.com/paritytech/psvm)

	The Polkadot SDK exports hundreds of different crates which all maintain their own semantic versioning. To keep your project compatible with Polkadot, you need to make sure all of these crates are using the same versions as the Polkadot network itself. PSVM is a tool which will go through your rust project, and make sure that all versions of all crates are correct for your targeted Polkadot SDK version.

- [Zepter](https://github.com/ggwpez/zepter)

	A common problem for new developers building a Polkadot SDK project is correctly importing new crates and handling all the feature flags for their newly imported crates. Zepter is a tool which can automatically detect and fix and format feature flags across your Polkadot SDK project.

### Tutorials

- [Rust State Machine](https://dotcodeschool.com/courses/rust-state-machine)

	Onboard yourself to the Rust programming language with this tutorial specifically tuned for teaching the basics of Rust and Blockchain development.

- [Substrate Kitties](https://dotcodeschool.com/courses/substrate-kitties)

	Build your first Polkadot SDK Pallet which functions as a simple NFT Marketplace where you can create, transfer, buy, and sell NFT Kitties.

### Courses

- [The Polkadot Blockchain Academy](https://github.com/Polkadot-Blockchain-Academy)

	The PBA is an 5-week in person course designed onboard existing software developers into the Polkadot and broader blockchain ecosystem. All resources for the academy are available online for free.

	- Course Content: https://polkadot-blockchain-academy.github.io/pba-book/
	- Video Recordings: https://www.youtube.com/@polkadotblockchainacademy/

### Contributing

Here are resources you can use to help you make your first contributions to the Polkadot SDK.

- [Polkadot SDK Mentor Issues](https://github.com/paritytech/polkadot-sdk/issues?q=is%3Aopen+is%3Aissue+label%3AC1-mentor)
- [Developer Wishlist](https://github.com/paritytech/polkadot-sdk/issues/3900)
