# Awesome-Last
Awesome Last is a community-driven public repository designed to be a resource people can use to familiarize themselves with Last ⬛️ 

All are welcome to contribute! 

You will find more readings about Last here 

## About Last

# Table of Contents
- [Introduction to Web3 development]()
- [DeFi Content]()
- [Last Custody Network]()
-   [Cosmosm SDK]()
-   [Validators]()
-   [Churn mechanism on Cosmos]()
-   [Block rewards]()
-   [ThorChain]()
-   [Run node infrastructure for Last]()
- [Last L2 EVM Execution Environment]()
-   [Data Availability markets]()
-   [Native swap market]()
-   [User fee reinbursement]()
-   [L2 overview]()
- [Governance]()
-   [Vote-escrowed governance pools]()
-   [Gauge systems]()
-   [Bribe-based voting mechanism]()
- [Revenue Sources]()
- [Awesome DeFi publications & Tutorials](https://github.com/LastL2/Awesome-Last?tab=readme-ov-file#awesome-defi-publications--tutorials)
- [Official Last channels and links](https://github.com/LastL2/Awesome-Last/blob/main/README.md#last-channels-and-links)
------

# Introduction to Web3 development
Developer Introduction into development and starting your Web3 developer journey: 
- If you are new to development [Zero to One Web Dev Guide](https://ravi0.notion.site/Zero-to-One-Web-Dev-Guide-0b9dcd9c77b249ca8af4b9e5bd6b676e) is a place to start your journey
- [How does Ethereum work](https://preethikasireddy.medium.com/how-does-ethereum-work-anyway-22d1df506369) required reading to understand how Ethereum blockchain works
-  [Web2 to Web3 🚀 — Week 2, Day 1: Scripting and Smart Contracts! Providers, Signers, and Wallets](https://www.youtube.com/watch?v=m2AJAcWk394&ab_channel=AustinGriffith) from Austin Griffith
- [Introduction to Ethereum development](https://www.youtube.com/watch?v=MlJPjJQZtC8&t=458s&ab_channel=AustinGriffith) tutorial by Austin Griffith
- [The Complete Guide to Full Stack Web3 Development](https://dev.to/edge-and-node/the-complete-guide-to-full-stack-web3-development-4g74) by Nader Dabit
- [Blockchain Developer | How to learn everything you need to become one](https://patrickalphac.medium.com/blockchain-developer-how-to-learn-everything-you-need-to-become-one-1df2c2121e34)
- [Foundation of Ethereum Development stack](https://ethereum.org/en/developers/docs/) Ethereum.org
- [Learn Solidity, Blockchain Development, & Smart Contracts | Powered By AI - Full Course (0 - 6)](https://www.youtube.com/watch?v=umepbfKp5rI) by Patrick Collins
- [devpill.me](https://www.devpill.me/docs/introduction/foreword/) huge resource for all things Ethereum and Go by DCBuilder
- [SpeedRunEthereum](https://speedrunethereum.com/) quests on building on Ethereum by Austin Griffith
- [Worry-free Web3: Getting started with Web3 Development](https://anettrolikova.medium.com/worry-free-web3-getting-started-with-web3-development-d6ea1fa945ae) blog post where you can find much more tutorials and basic tools!

## Developer Tools
Ethereum Development environments:
- [Hardhat](https://hardhat.org/tutorial) for developing Ethereum Contracts and dApps in JavaScript
- [Foundry](https://book.getfoundry.sh/) manages your dependencies, compiles your project, runs tests, deploys, and lets you interact with the chain from the command line and via Solidity scripts. Supports Rust and Solidity
Solidity: 
- [Solidity lang](https://soliditylang.org/) official website
- [Introduction to smart contracts](https://docs.soliditylang.org/en/v0.8.24/introduction-to-smart-contracts.html) in Solidity
Golang: 
- [Install Go](https://go.dev/doc/install)
- [Ethereum for Go developers](https://ethereum.org/en/developers/docs/programming-languages/golang/) huge resource of tutorials, tools and further reading
- [Introduction into Go language](https://go.dev/doc/effective_go)
- [Tour of Go](https://go.dev/tour/welcome/1) is an interactive way to try programming in Go. This is an interactive window that lets you play with Go and test commands
Cosmos:
- [ELI5: What is IBC](https://medium.com/the-interchain-foundation/eli5-what-is-ibc-def44d7b5b4c)
- [Spawn](https://github.com/rollchains/spawn) development platform for building custom modular Cosmos-SDK blockchains
  
## Build Ethereum based contracts
Interactive Development Environments - Write, test, and deploy smart contracts
- [Remix](https://remix.ethereum.org/)
- [Altlas IDE](https://www.atlaszk.com/)
- [ETH Build](https://eth.build/) - Educational sandbox for Web3
- [Scaffold ETH](https://scaffoldeth.io/) - Start building contracts, play with Solidity
- [Smart contract libraries, APIs, SDKs](https://www.cookbook.dev/)

## Cosmos Developer Education - Learn CosmWasm
- [CosmWasm](https://academy.cosmwasm.com/) Academy
- [Cosmwasm Zero to Hero](https://github.com/Callum-A/cosmwasm-zero-to-hero) Learn CosmWasm so you can build Cosmos contracts
- [Cosmwasm lectures](https://www.inflearn.com/course/dsrv-dev-playground) in Korean
- **[Area-52](https://area-52.io/) Master CosmWasm and smart contracts in Rust. Learn how to build your own multichain applications! Similar to Cryptozombies, fun and interactive coding lessons**
- [Cosmology](https://cosmology.zone/) developer tools to help you build in the Cosmos ecosystem
- [Cosmos tutorials](https://cosmology.zone/learn) to learn how to build Cosmos app
- 

### Cosmos Education 
- [Osmosis educational library](https://support.osmosis.zone/library) great source of cosmos education materials

# Understand DeFi and EVM Blochains
- [How to Become a DeFi Developer](https://kermankohli.substack.com/p/how-to-become-a-defi-developer) primer on what you should understand in DeFi ecosystem to consider yourself as a DeFi developer
- [Ethereum beige paper](https://github.com/chronaeon/beigepaper/blob/master/beigepaper.pdf) simplified version of Ethereum's yellow paper
- [How to Build a Crypto Project like an Aerospace Engineer](https://mirror.xyz/apeworx.eth/XOagKK6ZweD256uc2YsRIkCp5rWChAeEzkPVNOuD4M8) Mirror blog post

## DeFi Tools
- [DeFi Adapter Library ](https://github.com/consensys-vertical-apps/mmi-defi-adapters/tree/main) designed to simplify and standardize the process of fetching and interacting with data from various DeFi protocols, which often have unique interfaces and data structures. By MetaMask

# Last Custody Network
LCN acts as the accounting vault of the LAST protocol. LCN utilizes Cosmos, Ethereum and Bitcoin as multichain yield-bearing protocol. Initial protocol design is utilising EigenPod contracts that Node operators utilize. Consensus-based Network acts as accounting vault for Last L2.
# LCN Infrastructure

## Cosmos SDK
LCN is using CosmosSDK as state machine for LCN 
CosmosSDK is a framework for building blockchain applications in Go programming language. Cosmos SDK is used to build [Gaia](https://hub.cosmos.network/getting-started/what-is-gaia), the application implementation build for the Cosmos Hub.

"Cosmos SDK modules can be seen as little state-machines within the state-machine. They generally define a subset of the state using one or more KVStores in the main multistore, as well as a subset of message types. These messages are routed by one of the main components of Cosmos SDK core, BaseApp, to a module Protobuf Msg service that defines them." - [CosmosSDK Modules](https://docs.cosmos.network/v0.50/build/building-modules/intro)
- [Understand SDK Modules](https://tutorials.cosmos.network/tutorials/8-understand-sdk-modules/)
- [Learn to build via Cosmos SDK](https://docs.cosmos.network/main/learn/intro/overview)
- Last is [application-specific blockchain, here is introduction to app specific blockchains](https://docs.cosmos.network/v0.50/learn/intro/why-app-specific)
- [Anatomy of a Cosmos SDK Application](https://docs.cosmos.network/v0.50/learn/beginner/app-anatomy)
- [Transaction Lifecycle of CosmosSDK Application](https://docs.cosmos.network/v0.50/learn/beginner/tx-lifecycle)
- [Building Scalable Applications with the Cosmos SDK](https://medium.com/@jefferyokesamuel1/building-scalable-applications-with-the-cosmos-sdk-6dc56ae28643) introduction alike post about Cosmos SDK

## CometBFT
CometBFT handles consensus and networking in the LCN. CometBFT is the a Byzantine Fault Tolerant (BFT) middleware that takes a state transition machine - written in any programming language - and securely replicates it on many machines. It is a fork of [Tendermint Core](https://github.com/tendermint/tendermint) and implements the Tendermint consensus algorithm.

CometBFT is the most (and only) mature BFT consensus engine in existence. It is widely used across the industry and is considered the gold standard consensus engine for building Proof-of-Stake systems.

BTF stands for Byzantine-Fault Tolerant 
CometBFT is [ABCI = Application Blockchain Interface](https://tutorials.cosmos.network/academy/2-cosmos-concepts/1-architecture.html) package for networking and consensus layers of blockchain
- Introduction to CometBFT [CometBFT: The consensus engine that fuels the cosmos ecosystem](https://medium.com/@ali-the-curious/cometbft-the-consensus-engine-that-fuels-the-cosmos-ecosystem-ff778fcba809) blog post by Allisgar Merchant
- CometBFT is essential component of Cosmos blockchain app architecture. It is CometBFT is a blockchain application platform which supports state machines in any language. The language-agnostic CometBFT helps developers securely and consistently replicate deterministic, finite-state machines.
- [Explore CometBFT into the details](https://docs.cometbft.com/v0.37/) via documentation intoruction
- [Blockchain architecture explaining state machine, CometBFT, ABCI](https://docs.cosmos.network/main/learn/intro/sdk-app-architecture)

### Interested in diving deeper into the Cosmos ecosystem explore: 
- [Cosmos Hub](https://hub.cosmos.network/) is the first of thousands of interconnected blockchains that will eventually comprise the Cosmos Network. The primary token of the Cosmos Hub is the ATOM, but the Hub will support many tokens in the future.
- Build applications on CosmosSDK via [Ignite CLI](https://github.com/ignite/cli) platform to build, launch, and maintain any crypto application on a sovereign and secured blockchain. It is a developer-friendly interface to the Cosmos SDK, this CLI generates boilerplate code for you, so you can focus on writing business logic.

### Last Custody Network (LCN) is leveraging the Bifroest module for its twin chain communication module:
- [Bifroest signer](https://docs.thorchain.org/how-it-works/technology#signer-bifroest)

### Last Custody Network (LCN) is leveraging TSS for key management: 
- [Threshold Signature Schemes](https://medium.com/nethermind-eth/threshold-signature-schemes-36f40bc42aca)

## Staked assets on LCN
- [EigenLayer: How Restaking Will Transform Security for Ethereum-Based Protocols](https://medium.com/@mustafa.hourani/eigenlayer-how-restaking-will-transform-security-for-ethereum-based-protocols-fd37c01be44e)
- [EigenPods](https://docs.eigenlayer.xyz/eigenlayer/restaking-guides/restaking-user-guide/native-restaking/create-eigenpod-and-set-withdrawal-credentials/)


## LCN Node Operators
The Last Custody Network is leveraging the THORNode service of the THORChain network, which communicates and operates in cooperation to create a cross-chain swapping network. We will be utilising THORChain minimally in the LAST Protocol design. 
- [THORNode overview](https://docs.thorchain.org/thornodes/overview) docs page
- [Churn mechanism of validators](https://docs.thorchain.org/thornodes/overview) LCN will have 1 week epoch for validator


## Node provides
Run node for Last ⬛️ 
Guidelines:
- [Spin up your own Ethereum node](https://ethereum.org/en/developers/docs/nodes-and-clients/run-a-node/) by @nhsz
- [How to deploy a ThorChain node on Linux](https://www.blockmeadow.com/how-to-deploy-a-thorchain-node-on-linux/) by BlockMeadow
- [Run Thorchain node](https://gitlab.com/thorchain/thornode/-/blob/develop/README.md#setup) by Official Thorchain node repo. Tutorial is Linux and Mac OS compatible
- [Run Bitcoin node](https://bitcoin.org/en/full-node#setup-a-full-node) by Bitcoin.org

### Recommendation from our community to run the Ethereum node: 
- Input from Brian, Co-founder @ Ansybl.io
here are a few things to keep in mind: 
1. SSD choice is the most important from a hardware perspective. An NVMe drive is preferred. 2TB minimum, but the more, the better (especially now that we’ve got blobs live on the mainnet). If you're running in a cloud environment, most drives are network-attached and will most likely be your bottleneck when it comes to sync times/rpc response time.
2. Reth is fast becoming my favorite execution client. Fast, configurable, and takes less disk space
3. Take advantage of performance monitoring endpoints that come with nodes. It’s easy to spin up a Grafana dashboard for most clients, and it’ll make your life so much easier when debugging any issues
- [Nimbus node guide](https://nimbus.guide/index.html)
  
### Recommendation from our community to run THORNode:
We will utilize THORNode protocol designs for our LCN infrastructure
- Input from Andro, Co-founder @ Last: 
you need good bandwidth, and a fair amount of HDD space,  with a decent processor. The node requirements aren't like your typical cosmos chains where they are fairly light(minus bandwidth)

# Last L2 
Is utilizing Arbitrum Nitro stack
- [Arbitrum Nitro: one small step for L2, one giant leap for Ethereum](https://medium.com/offchainlabs/arbitrum-nitro-one-small-step-for-l2-one-giant-leap-for-ethereum-bc9108047450) blog post
- [Arbitrum Nitro Introduction](https://docs.arbitrum.io/why-nitro) docs page 
- [Shorter introduction of Arbitrum Nitro](https://docs.arbitrum.io/for-devs/concepts/public-chains#nitro) docs page

## Stylus framework 
Last is utilizing the Stylus framework by Arbitrum, which is a bit more efficient than other frameworks. They call Stylus EVM+ as everything is entirely additive and is not replacing the Ethereum Virtual Machine (EVM). Stylus allows smart contracts to be written in languages like Rust, C, and C++, which can be more efficient than Solidity, which can lead to faster and cheaper smart contracts.
 Learn more about Stylus:
- [Hello, Stylus](https://medium.com/offchainlabs/hello-stylus-6b18fecc3a22)
- [Introduction to Stylus](https://docs.arbitrum.io/stylus/stylus-gentle-introduction#whats-stylus)
- [Stylus VM and Fraud Prover](https://github.com/OffchainLabs/stylus)
- [Arbitrum Stylus Paradigm Shift](https://medium.com/@estheraladioche569/arbitrum-stylus-paradigm-shift-95e62c035a95)

# veGovernance
Last is using ve style Governance system based on Gauges and Bribes for its governance. 

Last is utilising ve(3,3) system which is composed of 3 parts = 
- Gauge system
- Bribe for votes 
- and some emissions paid out to the stakes of the gauges

Last will sorta use 3,3 mechanism. Here is outline of 3,3 voting mechanism. We will create a page in docs on this. Here is just a brief introduction: 

The idea behind ve(3,3) governance model is that you (as user & developer) can influence the will of the voters with a direct incentive, to direct the value(emissions) to the party providing something of want. In case of Curve, it means liquidity. In case of Last, it means deposited assets into the chain = yield-bearing assets. 

- [ve(3,3](https://andrecronje.medium.com/ve-3-3-44466eaa088b)
- [Gauges: The Foundational Governance Innovation of DeFi](https://yourcryptolibrary.com/blockchain/gauges-the-foundational-governance-innovation-of-defi/) Blog post by yourcryptolibrary
- - [Solidly — A High-Level Overview](https://medium.com/@seraph333/solidly-a-high-level-overview-aa5420a79acc)
- [on Solidly](https://medium.com/@vedao.alt/on-solidly-60f6481b26fd) blog post outlining how Solidly works, it highly influenced how LAST ve Governance works

Different protocols have its own explanations of these terms:
- [Gauges overview](https://docs.curve.fi/curve_dao/liquidity-gauge-and-minting-crv/gauges/overview/) by Curve docs
- [Gauges for EVM sidechains](https://docs.curve.fi/curve_dao/liquidity-gauge-and-minting-crv/evm-sidechains/overview/) by Curve docs
- [ve(3,3)](https://andrecronje.medium.com/ve-3-3-44466eaa088b) blog post by Andre Cronje
- [Voting and Gauge Weights](https://docs.convexfinance.com/convexfinance/general-information/why-convex/voting-and-gauge-weights) Convex Finance docs
- [Gauge](https://docs.frax.finance/vefxs/gauge) Frax Finance docs explaining in more depths how Gauge works
- [Options Liquidity Mining](https://docs.poolshark.fi/token/why-ofin) Poolshark docs, Last is utilizing OLM mechanism design for its governance
- [Deploying a gauge](https://docs.bunni.pro/docs/guides/deploy-gauge) Bunni docs, this is an example of how to deploy gauge by Bunni. Bunni is using very similar governance model to Curve.
- [A Closer Look at ve(3,3)](https://medium.com/vesperfinance/a-closer-look-at-ve-3-3-522add01b4b5) by Vesper Finance
- 

# DeFi primitives and applications ecosystem


# Education Hub
## Introduction into DeFi 
List of amazing DeFi introduction articles and videos: 
- [What is DEFI? Decentralized Finance Explained (Ethereum, MakerDAO, Compound, Uniswap, Kyber)](https://www.youtube.com/watch?v=k9HYC0EJU6E&ab_channel=Finematics) YouTube video
- [What is DeFi and How it works](https://chain.link/education/defi) blog post
  
## Awesome DeFi publications & Tutorials
List of amazing DeFi and Last related publications:
- [Stuffed Blocks](https://tonysheng.substack.com/archive) Substack by Tony Sheng
- [Kerman Kohli](https://kermankohli.substack.com/) Substack full of amazing DeFi resources!
- [Kerman Kohli YouTube](https://www.youtube.com/@DeFiWeekly/videos) short video explanations
- [Wrong a lot](https://wrongalot.substack.com/archive) Substack by Matti from ZeePrime capital
- [THORChain University](https://crypto-university.medium.com/) Great blog posts about THORChain which is apart of Last protocol design
- [Layer 2 Weekly Roundup](https://layer2roundup.substack.com/) Substack by Scroll community manager of updates about L2s out there
- [The Daily Gwei](https://www.youtube.com/thedailygwei) Daily YouTube podcast about the ecosystem
- [Evaluating Ethereum L2 Scaling Solutions: A Comparison Framework](https://blog.matter-labs.io/evaluating-ethereum-l2-scaling-solutions-a-comparison-framework-b6b2f410f955) blog post by Matter Labs, a bit older post but still interesting to understand the progress we've made in past years!

List of amazing L2 and Scaling related blogs: 
- [The Scaling wars](https://thedailygwei.substack.com/p/the-scaling-wars-the-daily-gwei-518) quick read on the The Daily Gwei Substack
- [Governance Decides Where Ethereum Transacts: The L2 Governance Race](https://tally.mirror.xyz/QZNVKjupNZmSUsY9R2sV5_vA-qe1fsCMW2hlnZ-5lEg) Blog post by Tally

# Last channels and links
Official Last social media channels
- [Twitter](https://twitter.com/lastdotnet)
- [Farcaster channel](https://warpcast.com/~/channel/last)
- [Discord](https://last.community/)
