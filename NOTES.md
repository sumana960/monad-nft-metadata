# Developer Notes – Monad NFT Project

This document provides additional context about the project, the development choices, and the learning outcomes.  
It is intended for reviewers, instructors, and anyone interested in understanding the reasoning behind the code.

---

## Project Context

This project is an ERC-721 NFT smart contract developed and deployed on **Monad Testnet**.  
The goal was not to build a production-ready NFT platform, but to understand the complete workflow of NFT development in a Web3 environment.

---

## Why This Project

I built this contract to:

- Understand how ERC-721 NFTs work internally
- Practice writing and deploying smart contracts in Solidity
- Learn how NFT metadata is stored and retrieved using IPFS
- Gain hands-on experience deploying and interacting with contracts on a testnet

This project was intentionally kept simple to focus on core concepts rather than advanced features.

---

## Development Approach

- The contract follows the ERC-721 standard
- A minimal feature set was chosen to reduce complexity
- Deployment and interaction were performed using Remix and MetaMask
- Metadata was stored on IPFS and linked via `tokenURI`

---

## What I Learned

Through this project, I learned how to:

- Implement and deploy an ERC-721 smart contract
- Interact with a deployed contract using MetaMask
- Upload and reference NFT metadata on IPFS
- Verify `tokenURI` values directly on-chain
- Understand the relationship between on-chain data and off-chain metadata

---

## Design Decisions

- **No advanced extensions** were added to keep the contract readable
- **No royalties** were implemented initially to avoid unnecessary complexity
- **No frontend** was built at this stage to focus on smart contract fundamentals
- Clear documentation was prioritized over feature count

---

## Current Limitations

This project has some known limitations:

- No automated unit tests yet
- No frontend user interface
- No royalty mechanism (EIP-2981 not implemented)
- Not optimized for gas usage

These limitations are acknowledged and intentional at this learning stage.

---

## Future Improvements

Planned future enhancements include:

- Adding NFT royalties using the EIP-2981 standard
- Writing basic unit tests (Foundry or Hardhat)
- Creating a simple frontend for NFT minting
- Improving documentation and code comments
- Exploring gas optimization techniques

---

## Security Considerations

- This contract has not been audited
- It is intended for educational and experimental use only
- Deployment was done on a testnet, not on mainnet
- The contract should not be used in production without proper auditing

---

## Conclusion

This project represents a complete and functional example of an ERC-721 NFT contract deployed on a testnet.  
It demonstrates an understanding of fundamental NFT concepts and reflects a learning-focused development process.

Feedback and suggestions are welcome.
