# Defi Primitives

## Transaction Mechanics 🧰


### How Transaction Works
Transaction involves sending ETH or other Tokens from one address to another.
 - An Ethereum user can control address through an externally owned account or by using Smart Contract.
 - When Sending data to contract account, the data are used to execute code in that contract. The Transaction may or may not have an ETH payment for use by the contract.
 - Transaction sent to Externally Owned accounts (EOA) can only transfer ETH.
 - A single transaction starts with an end user from an EOA, but can intract with a large number of dApps before completing.
 


 ## Fungible Tokens And Non Fungible Tokens (NFTs)

 ### Fungible Tokens
  - The Main or most used protocol for fungible tokens is ERC20
    **ERC20 Functionality**
    1. When a token implements the ERC20 Interface, any application that generically handles the defined functionality can instantly and seamlessly integrate with the token.
    2. Using ERC-20 and similar interface, application developers can confidently support tokens that do not yet exits.

    **Equity Token**
    1. An equity tokens is simply a token that represents ownership of an underlying asset or proof of assets.

    **Utility Tokens**
    1. Utility token are fungible token that are required to utilize some functionality of a smart contract system or that have an intrinsic value proposition defined by its respective smart contract system. 


 ### Non Fungible Token (NFT)
   - ERC-721 defines the Non-Fungible standards.
   - It is similar to ERC-20 except that each unit has its own unique ID.
   - Their alternative name, deeds, implies their use case as representing unique ownership of unitary assets.
   - Lottery tickets are non fungible because only one or limited number will be winning tickets.
   - NFT can represent collectibles like ownership in peice of art.

   **ERC-1155**
   - ERC-20 and ERC-721 tokens require an individual contract and address deployed to the blockchan.
   - These requirements can be cumbersome for system that have many tokens, which are closely related, possible even a mix of fungible and non fungible token types.
   - ERC-1155 resolves this complexity by defining a multi token model in which the contract holds the balance for a variable number of tokens, which can be fungible, non fungible.


  

 ## Blockchain Tech 

 ### Hashes And Keys :-

   **Hasing**
  Provide the last block as a header of next. SHA-256, Keccak-256, One way cryptographic function. Hasing is a cryptographic function and not encryption.

  **Cryptography**
  This is widely used in all aspects of blockchain. It is important in deriving the public key.
   Two types of cryptography.
   1. Symmetric Key.
   2. Asymmetric Key.


### Address

 **Public Address**
 This is either identical to the public key or a function of the public key.
  - Bitcoin and ethereum uses Elleptic Curve Digital Signature Algorithm (ECDSA) for signing transaction.

**Private Address**
Private key is a number called signing key. It's a confidential key.
 - Public key is the verification key and is mathematically linked to the private key.


### Immutability

This is a crucial characterstic of a blockchain. 

