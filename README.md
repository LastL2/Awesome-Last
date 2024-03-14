# Awesome-Last
Awesome Last is a community-driven public repository designed to be a resource people can use to familiarize themselves with Last ⬛️ 

All are welcome to contribute! 

You will find more readings about Last here 

## About Last

# Table of Contents
- [Last channels and links](https://github.com/LastL2/Awesome-Last/blob/main/README.md#last-channels-and-links)
- [Developer tool introduction](https://github.com/LastL2/Awesome-Last/blob/main/README.md#developer-tools)
- [Start building on Last](https://github.com/LastL2/Awesome-Last/blob/main/README.md#start-building-on-last)
- [Node providers](https://github.com/LastL2/Awesome-Last/blob/main/README.md#node-provides)
- [Governance](https://github.com/LastL2/Awesome-Last/blob/main/README.md#governance)
- [Awesome DeFi publications & Tutorials](https://github.com/LastL2/Awesome-Last?tab=readme-ov-file#awesome-defi-publications--tutorials)


# Last channels and links
Official Last social media channels
- [Twitter](https://twitter.com/lastdotnet)
- [Farcaster channel](https://warpcast.com/~/channel/last)
- [Discord](https://last.community/)

# Developer tools 
Start building on Last. Everything you need to know as a developer before building with the Last stack:

### General reads on DeFi and Ethereum
- [How to Become a DeFi Developer](https://kermankohli.substack.com/p/how-to-become-a-defi-developer) primer on what you should understand in DeFi ecosystem to consider yourself as a DeFi developer
- [Ethereum beige paper](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf) simplified version of Ethereum's yellow paper
- [How to Build a Crypto Project like an Aerospace Engineer](https://mirror.xyz/apeworx.eth/XOagKK6ZweD256uc2YsRIkCp5rWChAeEzkPVNOuD4M8) Mirror blog post

  
### Solidity is a great place to start! 
- [Solidity lang](https://soliditylang.org/) official website
- [Introduction to smart contracts](https://docs.soliditylang.org/en/v0.8.24/introduction-to-smart-contracts.html) in Solidity

Start building on Last via [Hardhat](https://hardhat.org/tutorial) and/or [Foundry](https://book.getfoundry.sh/). You might want to try out [Altlas IDE](https://www.atlaszk.com/) to build and interact with Last contracts.

### General Ethereum tutorials and courses
- [Foundation of Ethereum Development stack](https://ethereum.org/en/developers/docs/) Ethereum.org
- [Learn Solidity, Blockchain Development, & Smart Contracts | Powered By AI - Full Course (0 - 6)](https://www.youtube.com/watch?v=umepbfKp5rI) by Patrick Collins
- [devpill.me](https://www.devpill.me/docs/introduction/foreword/) huge resource for all things Ethereum and Go by DCBuilder
- [SpeedRunEthereum](https://speedrunethereum.com/) quests on building on Ethereum by Austin Griffith
- [Worry-free Web3: Getting started with Web3 Development](https://anettrolikova.medium.com/worry-free-web3-getting-started-with-web3-development-d6ea1fa945ae)

### DeFi Tutorials and courses
- [DeFi Adapter Library ](https://github.com/consensys-vertical-apps/mmi-defi-adapters/tree/main) designed to simplify and standardize the process of fetching and interacting with data from various DeFi protocols, which often have unique interfaces and data structures. By MetaMask

# Start building on Last
### Last L2 is utilizing Arbitrum Nitro: 
- [Arbitrum Nitro: one small step for L2, one giant leap for Ethereum](https://medium.com/offchainlabs/arbitrum-nitro-one-small-step-for-l2-one-giant-leap-for-ethereum-bc9108047450) blog post
- [Arbitrum Nitro Introduction](https://docs.arbitrum.io/why-nitro) docs page 
- [Shorter introduction of Arbitrum Nitro](https://docs.arbitrum.io/for-devs/concepts/public-chains#nitro) docs page

Last is utilizing the Stylus framework by Arbitrum, which is a bit more efficient compared to other frameworks. Learn more about Stylus:
- [Hello, Stylus](https://medium.com/offchainlabs/hello-stylus-6b18fecc3a22)
- [Introduction to Stylus](https://docs.arbitrum.io/stylus/stylus-gentle-introduction#whats-stylus)

### Last Custody Network (LCN) is leveraging Go, a great place to start with Go:
- [Install Go](https://go.dev/doc/install)
- [Ethereum for Go developers](https://ethereum.org/en/developers/docs/programming-languages/golang/) huge resource of tutorials, tools and further reading

### Last Custody Network (LCN) is leveraging Cosmos SDK. Dive into Cosmos SDK:
- [Understand SDK Modules](https://tutorials.cosmos.network/tutorials/8-understand-sdk-modules/)
- [Learn to build via Cosmos SDK](https://docs.cosmos.network/)
- [Overview of the Cosmos SDK](https://docs.cosmos.network/v0.50/learn/intro/overview)
- Last is [application specific blockchain](https://docs.cosmos.network/v0.50/learn/intro/why-app-specific)


### Last Custody Network (LCN) is leveraging the Bifroest module for its twinchain communication module:
- [Bifroest signer](https://docs.thorchain.org/how-it-works/technology#signer-bifroest)


### Last Custody Network (LCN) is leveraging TSS for key management: 
- [Threshold Signature Schemes](https://medium.com/nethermind-eth/threshold-signature-schemes-36f40bc42aca)


# Node provides
Run node for Last ⬛️ 

Guidelines:
- [Spin up your own Ethereum node](https://ethereum.org/en/developers/docs/nodes-and-clients/run-a-node/) by @nhsz
- [How to deploy a ThorChain node on Linux](https://www.blockmeadow.com/how-to-deploy-a-thorchain-node-on-linux/) by BlockMeadow
- [Run Thorchain node](https://gitlab.com/thorchain/thornode/-/blob/develop/README.md#setup) by Official Thorchain node repo. Tutorial is Linux and Mac OS compatible
- [Run Bitcoin node](https://bitcoin.org/en/full-node#setup-a-full-node) by Bitcoin.org

### Recommendation from our community to run Ethereum node: 
- Input from Brian, Co-founder @ Ansybl.io
here are a few things to keep in mind: 
1. SSD choice is the most important from a hardware perspective. An NVMe drive is preferred. 2TB minimum but the more the better (especially now that we’ve got blobs live on mainnet). If you're running in a cloud environment, most drives are network-attached and will most likely be your bottleneck when it comes to sync times/rpc response time.
2. Reth is fast becoming my favorite execution client. Fast, configurable and takes less disk space
3. Take advantage of performance monitoring endpoints that come with nodes. It’s easy to spin up a Grafana dashboard for most clients, and it’ll make your life so much easier when debugging any issues
- [Nimbus node guide](https://nimbus.guide/index.html)
  
### Recommendation from our community to run ThorChain node:
- Input from Andro, Co-founder @ Last: 
you need good bandwidth, and a fair amount of HDD space,  with a decent processor. The node requirements aren't like your typical cosmos chains where they are fairly light(minus bandwidth)

# Governance
Last is using the Gauge and Bribe system for its governance. You can learn more about Gauge and Bribes here:

Last is utilising ve(3,3) system which is composed of 3 parts = 
- Gauge system
- Bribe for votes 
- and some emissions paid out to the stakers of the gauges

The idea behind ve(3,3) governance model is that you (as user & developer) can influence the will of the voters with a direct incentive, to direct the value(emissions) to the party providing something of want. In case of Curve, it means liquidity. In case of Last, it means deposited assets into the chain = yield-bearing assets. 

- [Gauges: The Foundational Governance Innovation of DeFi](https://yourcryptolibrary.com/blockchain/gauges-the-foundational-governance-innovation-of-defi/) Blog post by yourcryptolibrary
- [Gauges overview](https://docs.curve.fi/curve_dao/liquidity-gauge-and-minting-crv/gauges/overview/) by Curve docs
- [Gauges for EVM sidechains](https://docs.curve.fi/curve_dao/liquidity-gauge-and-minting-crv/evm-sidechains/overview/) by Curve docs
- [ve(3,3)](https://andrecronje.medium.com/ve-3-3-44466eaa088b) blog post by Andre Cronje
- [Voting and Gauge Weights](https://docs.convexfinance.com/convexfinance/general-information/why-convex/voting-and-gauge-weights) Convex Finance docs
- [Gauge](https://docs.frax.finance/vefxs/gauge) Frax Finance docs explaining more into depths how Gauge works

More great reads related to L2 Governance (these are not fully related to Gauge and Bribe, but are worth to dive into): 
- [Governance Decides Where Ethereum Transacts: The L2 Governance Race](https://tally.mirror.xyz/QZNVKjupNZmSUsY9R2sV5_vA-qe1fsCMW2hlnZ-5lEg) Blog post by Tally

# Awesome DeFi publications & Tutorials
List of amazing DeFi and Last related publications:

- [Stuffed Blocks](https://tonysheng.substack.com/archive) Substack by Tony Sheng
- [Kerman Kohli](https://kermankohli.substack.com/) Substack full of amazing DeFi resources!
- [Kerman Kohli YouTube](https://www.youtube.com/@DeFiWeekly/videos) short video explanations
- [Wrong a lot](https://wrongalot.substack.com/archive) Substack by Matti from ZeePrime capital
- [THORChain University](https://crypto-university.medium.com/) Great blog posts about THORChain which is apart of Last protocol design
- [Layer 2 Weekly Roundup](https://layer2roundup.substack.com/) Substack by Scroll community manager of updates about L2s out there

