# Cross Ring Protocol 🚀  

## Overview 🌟  

Cross Ring Protocol is an innovative project that allows users to seamlessly prove their ownership of Bitcoin, ETH, MATIC, AVAX & XRP regardless of the chain like Ethereum, Polygon & Avalanche (testnets) while prioritizing privacy and security. This groundbreaking solution leverages a sophisticated technology stack, including Chainlink Functions for network state verification, and our hommade (Cypher Lab) ring signatures library (Alice'sring) for secure ownership proofs, opening the door to a wide range of compelling use cases in the world of decentralized finance and privacy-preserving applications.  

## Repo

- [WebApp](https://github.com/hack-chainlink/WebApp)
- [ChainLink Functions](https://github.com/hack-chainlink/chainlink-functions-call)   
- [Smart Contracts](https://github.com/hack-chainlink/contracts)
- [API](https://github.com/hack-chainlink/API) without Alice's Ring library (closed source for now -> waiting for audit)

## Table of Contents 📑

- [Features](#features)
- [Usage](#usage)
- [Technical Details](#technical-details)
- [Security and Privacy](#security-and-privacy)
- [Use Cases](#use-cases)
- [Useful ressources](#useful-ressources)

## Ideas ✨  

- **Collateral for DeFi Loans:** Prove your BTC, ETH, MATIC, AVAX & XRP holdings for decentralized loans on EVM without compromising security or exposing wallet addresses.  
- **Enhanced Privacy:** Safeguard user privacy by utilizing ring signatures and encryption techniques.  
- **Cross-Chain Integration:** Seamlessly interact with both EVM and non-EVM ecosystems.  
- **Tokenization:** Mint tokenized versions of BTC,XRP on EVM, such as Wrapped BTC (WBTC) or (WXRP), without intermediaries.  
- **Future:** Explore various applications, including credit scoring, cross-chain financial products, privacy-preserving wealth management, and more.  

## Usage 📈

To use the Cross Ring Protocol on Ethereum, Avalanche or Polygon testnets, you can directly interact with our [WebApp](https://web-app-chainlink-hack.vercel.app/):  


## Technical Details 🛠️

The Cross Ring Protocol relies on a comprehensive technology stack:

- **Chainlink Functions:** Chainlink Functions are used to fetch real-time Bitcoin, XRPL, Ethereum, Avalanche & Polygon networks state data and index it for use on EVM chains, providing accurate and up-to-date information.
- **Ring Signatures for Privacy-Preserving Ownership Proofs:** Ring signatures enable users to prove their BTC, ETH, MATIC, AVAX & XRP ownership on Ethereum, Polygon & Avalanche without revealing specific wallet addresses, preserving user's privacy.
- **IPFS for Decentralized Front-End Hosting:** We employ IPFS to host the project's front-end in a decentralized and trustless manner. This ensures that users can access and interact with the system without relying on a central authority
- **Covalent for EVM API:** Covalent API is integrated to gather token balances, positions, and historical granular transaction data from EVM chains. This ensures comprehensive and accurate data for cross-chain operations within the Ethereum ecosystem.
- **Quicknode and Public RPC for EVM RPC:** Quicknode and public RPC are utilized for EVM RPC, providing reliable and efficient access to Ethereum blockchain data. This enhances the project's ability to seamlessly interact with Ethereum-based financial instruments.
- **Quicknode for XRPL API:** Quicknode is employed for XRPL API to fetch real-time data from the XRP Ledger. This integration ensures accurate and timely information retrieval for cross-chain interactions involving XRP.
- **Blockcypher for BTC API:** Blockcypher API is integrated for Bitcoin data, providing essential information for cross-chain operations involving Bitcoin. This ensures reliable data retrieval and indexing for secure cross-chain proofs.

## Security and Privacy 🔐

Security and privacy are paramount in the Cro on Ethereum project:

- **User Data Protection:** All user data, including asset holdings, wallet addresses, and transaction histories, are kept confidential.
- **Privacy-Preserving Techniques:** Ring signatures and encryption ensure that users can prove their assets ownership on chain without exposing their other chain's wallet addresses.

## Use Cases 🌐  

- **Collateral for DeFi Loans:** Users can prove their BTC, ETH, MATIC, AVAX & XRP holdings to secure decentralized loans on EVM chains without compromising security.
- **Credit Scoring and Underwriting:** Decentralized credit systems can assess user creditworthiness without revealing identities.
- **Cross-Chain Financial Products:** Users can participate in Ethereum-based financial instruments like staking, yield farming, or liquidity pools.
- **Proof of Reserves for Exchanges:** Cryptocurrency exchanges can transparently prove Bitcoin reserves to Ethereum users.
- **Privacy-Preserving Wealth Management:** Users can manage wealth across blockchains without exposing total holdings or transactions.
- **Atomic Swaps:** Trustless atomic swaps between BTC, XRP and ETH or other Ethereum-based assets are facilitated.
- **Participation in DAOs:** Users can prove BTC, ETH, MATIC, AVAX & XRP holdings to participate in DAOs without revealing real-world identities.
- **Tokenized non-EVM assets on Ethereum:** Users can mint tokenized versions of BTC, MATIC, AVAX & XRP on EVM, potentially without intermediaries.
- **Voting Rights in DeFi Protocols:** Proof of BTC, ETH, MATIC, AVAX & XRP holdings can allocate voting rights in Ethereum-based DeFi protocols.
- **Enhanced Privacy for BTC and XRP Holders:** BTC/XRP holders can interact with the Ethereum ecosystem without revealing Bitcoin addresses.
- **Cross-Chain Reputation Systems:** Users can build financial reputations on Ethereum platforms by proving their Bitcoin holdings.

## Useful ressources 📜

- **Litepaper:** You can find our litepaer [here](https://github.com/hack-chainlink/.github/blob/main/Cross%20ring%20protocol%20Lightpaper.pdf)
- [**Alice's Ring, ring signature protocol*](https://www.cypherlab.fr/alices-ring)
