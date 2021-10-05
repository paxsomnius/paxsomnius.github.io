---
title: The state of the Top DEFI protocols and their pros and cons for a beginner crypto developer. 
date: 2021-10-05 12:52:23 +0100
categories: [Blockchain Development, Blog]
tags: [blockchain development,defi, radix, algorand, ether, beginner,]     # TAG names should always be lowercase
---
Due to the interest of my first reddit post on why I chose Algorand as the platform for my initial foray into blockchain development and a few comments asking for my impressions of other DeFi protocols (smart contract platforms) and the realization that I didn't actually research much after I discovered Algorand and identified it as my starting point for when I get to the blockchain phase of the small project I'm developing.

So I decided to dive into all of the heavily invested/ hyped TOP MCAP DeFi protocols to identify the most appropriate protocol for a beginner crypto dev with the intention of building then deploying a custom DeFi DAPP to said blockchain and share my findings with the community!

## Ethereum

- The state of the Ethereum blockchain and its inadequate gas fees and slow tx speed whatever you develop beyond a simple DEX like Uniswap will be useless until they upgrade and fix the scalability issues lower the gas fees + speed up the tx speed, lets say you make a simple escrow app it'll take 5min and 50$ for a user to add funds to that escrow app and 5min and 50$ for a user to receive funds from that escrow app every time they use it! and that's just a basic Dapp lets say we add verification via NFT to validate someone as the owner of said escrow account to mimic a real world Trust Fund it'll then cost 50$ to create an owner token and 50 to transfer ownership and 5min + 50 every time the user wants to prove/validate ownership via the blockchain.

### Ether Pros

- OG Firstmover

- Invented smartcontracts and the overall direction blockchains are taking AKA Market Leader

- Dev Docs are the most developed of any DeFi protocol in existence

- Dev Ecosystem is vast and well mapped for DAPP production

- Dev Tooling

- Lead by a solid Team

- Controlled via a core organization which is a dealbreaker for me I for one will not trust my time and effort to a completely decentralized blockchain with no serious group leadership or direction.

- Solidity is a well received language with many tutorials and resources for a beginner.

- Solidity is used by Avalanche

### Ether Issues

- GAS Fees!

- Congestion = Scalability catastrophic failure

- TX speed is abysmal

- Rollups

- 10tps ~ finality

In combination the above issues make Ethereum unsuitable for developing a complex DeFi DAPP intended to be used by billions, and difficult, expensive and slow for users to use even simple DAPPS like UniSwap hence it is pointless to pursue until they upgrade their blockchain and fix their issues.

### Ether Summary

- Ether- can possibly dominate the future if the get their shit together by the end of 2022 and increase TX speeds/ Decrease GAS costs by a some orders of magnitude, and increase/maintain blockchain security somehow with out bottlenecking, as they do have firstmover advantage in the form of a vast Ecosystem and a well mapped/tooled Dev environment with Solidity etc., currently IMO spending time and effort to learn Solidity thoroughly then being limited to basic DAPPS is pointless because of Ethers current scaling problems.

As I am writing this after discovering Radix and attempting to invest in their token, which will be exchangeable 1 to 1 Radix tokens when the first MainNet launches soon, via Uniswap the gas fees are 180$-200$ Ether = unfit for purpose!

## Algorand

- I started here instead of ether, it is fast robust and the dev docs are top notch, also it has JavaScript/PyTeal/Python SDK's and many developer resources, the biggest draw for me was the JavaScript SDK for creating ASA's and its custom assembly language TEAL it is easy for me to understand and with the PyTeal compiler easy to manipulate /create smartcontracts with, it is lead by an MIT professor and has institutional backers, its not perfect but as of today it's blockchain is superior over Ether's and ADA's non-existent smartcontracts,

### Algorand Pros

- Dev Docs are prime real estate

- Lead by a solid team

- Controlled via a core organization which is a dealbreaker for me I for one will not trust my time and effort to a completely decentralized blockchain with no serious group leadership or direction.

- The technology is production ready, IE you can create a complex DAPP and not have it's scalability limited by its native blockchain.

- SDK's/Compilers are available in common coding languages Java/JavaScript/Python/PyTeal

- Founder is a accomplished

- No Forking or Sharding which maximises the security of the blockchain by minimizing soft points

- 1k tps 4s finality

- Atomic Swaps/Composability - Very Important for complex DeFi DAPPs to effectively interact with each other.

### Algorand Issues //

- I would say Ethers ecosystem is larger and has more dev resources but Algorand mostly has everything you need to create unique DAPP's and clones, and this is the drawback of Algorand because it is fairly new you will have to trailblaze if you smartcontract/ASA requires something that hasn't been done before in PyTeal/TEAL.

- TX Speed - 1000tps on Layer-1 Its is a major improvement over Ethereum but This is not enough for a future globally scaled DEFI solution (VISA is doing 3000tps average)

- Dev Ecosystem is lacking in comparison to the market leader Ether

- Dev Tooling has room for expansion

- Dev code Mapping

### Algorand Summary

Algorand - I am not sure if Algorand is aiming to dominate the entire DeFi industry but they can if they can increase the TX speeds to 46k tps on Layer -1 minimum and expand their Ecosystem/Dev environment with more tools and TEAL mapping other than those minor (in comparison) issues Algorand is poised as the best current protocol to learn blockchain development with the intent of production, if as an individual developer you have the skill/determination to get your hands dirty and trailblaze with TEAL.

## Radix

- Radix is very impressive as a theory, they intend to use a sharded blockchain with dynamically synced DAPPS through a pre-sharded data-structure and consensus mechanism called Cerebrus which will make its blockchain unique among the sharded chains with atomic composability, which I do not understand but if it can be done and the team delivers anything close to their demonstrated 1.4 million tps and 1 sec finality with atomic composability between DAPPS on different shards they will lay waste to all the other competitors in the DeFi space, but that's a lot of speculation we will all see clearly in a few years.

### Radix Summary

- Radix isn't ready for development yet it just has a betaNet running but all future and current cryptodevs should be aware of it.

- Radix - is a bloody monster, if they deliver on their dream and by demonstrable evidence they will, their tech(1.4 million tps/Atomic Sharding!/1s finality) will solve both of Algorand/Ethers scalability issues in a technological coup de grace, but they are still in the early days with their fully kitted MainNet not launching until 2023.

## Polkadot

- Polakdot is an interesting venture into sharded multichains it will use a main relay blockchain with "parachains" able to connect to the relaychain with the parachains computing the smartcontracts/tokens and the relaychain allowing them to communicate, Polkadot is still in development and is currently in its infancy. From skimming the docs its seems very similar to ETH-2.0, This is an interesting project but unsuitable for learning blockchain development at the moment, as the basic tooling is still in development, although you can explore building a basic parachain via substrate. After giving the docs a second look this project could be great the dev docs are excellent and they are adding new tools and tutorials quickly this is one to watch.

### Polkadot Potential Pros

- 1,500 tps per parachain

- Significantly improved scalability because of said parachains

- Dev Docs are top-notch although extremely limited.

- If and when their tooling is complete it will be a great alternative

- Solid team

- Great Marketing

- Polkadot Potential Issues

- 10-12 sec finality

- No atomic composability between different shards

- Infinite Inflation for non-staking DOT holders

## Cardano

Ok I'm going back into Cardanos documentation and again I am immediately turned off, the structure is horrible, the dev docs are mixed in with the other documentation with things like How to buy ADA? What is a BlockChain? How to delegate, mind you they do each have a heading with an unordered list but damn who decided to place the Getting Started list above the New to Cardano? list.

Ok lets get through this and create a basic test token just to play around with on Cardano, ok we need to install a node use Linux yeah pretty standard, install about 10 dependencies using bash/command line pretty standard, run the node using Nix? ok W/E, Wait what? and I quote

Your block-producing node must ONLY talk to your relay nodes, and the relay node should talk to other relay nodes in the network. Go to our telegram channel to find out IP addresses and ports of peers.

That was a far as I got on the second read VS Algorand head over to algodesk, choose testnet, connect algosigner in the browser with one click, algodesk connects to my account in algoSigner, add the variables name supply etc click create and im done 1 million Easy coins minted on the test net in in my wallet. Apperantly you can write smatcontracts with "marlow" in haskell and javaScript but the docs are such a mess that I gave up, but as I was unpacking Cardano and attempting to find some technical specs for its blockchain on its advertisement of a website, I careened into Atala PRISM which fascinated me this is a blockchain ID solution to many problems and looks very promising It is basically a Blockchain ID with your degree name credit score health info licenses etc If they can pull this off it will change the game and its built on Cardano by the same group who made Cardano one caveat Will governments allow this group to know everything about their citizens?

### Cardano Pros

- Marketing is top notch

- The Wallets are nice

- Atala Prism

- Marlow GUI Blockly smartcontract playground

### Cardano Issues

- Haskell

- Dev Docs are not only a mess but confusing

- Dev environment/tooling/resources are currently very limited

- Slow roadmap

- 257 tps

### Cardano Summary

After discovering Atala PRISM it seems to me that Cardano is intentionally providing poor quality Dev Docs for a reasons I cannot fathom but any group that can produce that brilliance is one to watch as a beginning cryptodev for now Cardano is a hard pass.

## Solana

Well this caught me offguard I had never heard of Solana before getting into their website but from what I see I like. Solana claims to have solved the trilemma with a few unique innovations, their Dev Docs are top notch and from skimming the docs you can code in Rust and C# and JavaScript bindings, ok this is very impressive I am under the impression that you can code apps directly in Rust or C#, there is a lot of jargon here but the dev docs are excellent and they have JSON/ Javascript API for easily interacting with the blockchain through a webapp, they claim a tx speed of 50k, I will need much more research on Solana but I am impressed.

From a first impression and minimal research Solana is worth a look if you are a new developer coming from a web app background and you need a simple smartcontract to tie into a web app.

### Solana Pros

- 50k+ tps

- Impressive Dev Docs

- Impressive Website

- Dev Tooling is top notch

- Dev Environment is adequate

- sub 1 sec finality

- low tx fees

- Getting a COSMOS vibe

### Solana Cons

- Claimed atomic composability

- Ok Dev Resources

- Alot of Jargon

- Native token is inflationary

- Mobile Wallets are 3rd Party

## Elrond

Another COSMOS blockchain rust and C++ Great docs and Dev resources solid blockchain. See Solana although Elrond's tutorials and dev docs are better than Solana's.

## Avalanche

Very impressive avalanche basically fixes all of Ethereum's scalability issues and allows development of DAPPS and erc-20 tokens with solidity AND eventually the creation and deployment of custom blockchains, Avalanche is still in development so the dev docs are lacking but this is one to watch as the underlying tech and founding team are impressive.

### AAVE pros

- 4500tps

- Sub 1s validation

- POS

- Atomic Swaps

### AAVE cons

- New

- Dev Ecosystem needs expansion

- Still in development

## Tezos

Tezos seems a solid choice for a beginning blockchain developer but for me it is too decentralized there are multiple versions of dev tools each created and maintained by different teams, although their Michaelson language was easy for me to understand almost instantly the syntax is very intuitive and easy to read, and they support a python compiler for coding Michaleson contracts in Python SmartPy, The Dev Docs are adequate and the resources available are vast. I couldn't find any information on its blockchain's capabilities probably because their site is being redesigned at the moment.

### Tezos Pros

- Decentralized if you see that as a pro

- Dev Docs are adequate

- Vast Dev resources

- Excelent tooling

- Michaelson is a pleasure

### Tezos Cons

- 40 tps is just not competitive

- Decentralized

## COSMOS

### This answered alot of questions, I once saw an article claiming that you can make a blockchain in 5 min, and now I know how, I am such a noob

#### Sources

- Build Now | Avalanche (avax.network)

- Docs · The Internet Scale Blockchain (elrond.com)

- Starport - Cosmos: The Internet of Blockchains

- Tendermint

- Ecosystem | Solana: Build crypto apps that scale

- Cardano Documentation — Cardano Documentation 1.0.0 documentation

- Build | Polkadot

- Official Substrate Documentation for Blockchain Developers · Substrate Developer Hub

- Solidity — Solidity 0.4.24 documentation (soliditylang.org)

- Assets - Algorand Developer Portal

- Starport - Cosmos: The Internet of Blockchains  
