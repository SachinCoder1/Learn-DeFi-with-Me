# Defi Infrastructure

## Let's Start with the basics ( Very Important ) ⭐✳


### 1️⃣ What do we mean by Decentralized Finance 📔
Before moving to Decentralized finance first understand Centralized Finance, In CEFI (Centralized finance) your Hard Earned money is held by banks, corporations whose end goal is to make money. The financial system is full of third parties (mediators) who facilitate money movement between parties, with each one charging fees for using their services. 
For example, say you purchase your keyboard using your credit card. The charge goes from the merchant to an acquiring bank, which forwards the card details to the credit card network.

Decentralized finance eliminates intermediaries by allowing people, merchants, and businesses to conduct financial transactions through emerging technology. This is accomplished through peer-to-peer financial networks that use security protocols, connectivity, software, and hardware advancements.

Decentralized Finance uses this technology to eliminate centralized finance models by enabling anyone to use financial services anywhere regardless of who or where they are.

DeFi applications give users more control over their money through personal wallets and trading services that cater to individuals.

&nbsp; 
&nbsp;  



### 2️⃣ How Does Decentralized Finance (DeFi) Works ⚒
Decentralized finance uses the blockchain technology that cryptocurrencies use. A blockchain is a distributed and secured database or ledger. Applications called dApps are used to handle transactions and run the blockchain.

&nbsp; 
&nbsp; 


### 3️⃣ Future of DeFi 🔮
Decentralized finance is still in the beginning stages of its evolution. For starters, it is unregulated, which means the ecosystem is still riddled with infrastructural mishaps, hacks, and scams.
The goal of DeFi is to get rid of the third parties that are involved in all financial transactions.

&nbsp; 
&nbsp; 



## Evolution Of Finance :-

### Purpose Of Money 
 - **Unit Of Accounts** -> A Way to compare values of various goods and services.
 - **Medium Of Exchange** -> Allows non barter transaction.
 - **Store Of Value** -> Allows values to be retained.
 - **Transfer of Value** -> Ease of Transfer of value and to defer Value.
 
 
&nbsp; 
&nbsp;  



### Characterstics of Money
 - Durability -> Repeated Use (paper, gold)
 - Portability -> You Can Carry Around
 - Divisibility -> Fractional Units
 - Uniformity -> Versions of same currency have identical values
 - Limited supply -> Which makes it valuable.


&nbsp; 
&nbsp;  




## Problems with Centralized finance

1. **Centralized Control :-**
 - Centralized banking system is highly concentrated.
 - National central banks control currency
 - Non financial centralization of tech giants eg. Facebook, google, Amazon

2. **Limited Access :-**
 - Around 1.5 Billion peoples are unbanked.
 - Many enterpreneurs use credit card to finance their business. Since banks won't lend to them because they are small.

3. **Inefficiency :-**
 - Banks charges 3% for swiping through credit card.
 - 2 days settlement times for stock transactions.
 - Slow transfer of funds.
 - Many Frauds, chargeback.
 - Difficult to get paid.
 - Money is not secured.

4. **Trust Issues :-**
 - Very little transparency
 - Bank costumers don't know about the health of bank.
 - Banks have full control over the money.
  


&nbsp; 
&nbsp;  




## Foundation Of DeFi
The Core foundation of DeFi is Blockchain technology, Cryptographic hashing, cryptocurrency.

Let's Start With Blockchain

&nbsp;   

### What is Blockchain in Terms of DeFi ⛓
Blockchain was invented by Haber and Stornetta in 1991, is basically a software protocol that allows multiple parties to operate under shared assumptions and data without trusting each other. 
 - These Data can be anything such as information of items in a supply chain or account balances of a token.
 - No one can temper with it because most of blockchains are open source.
 - Blockchain is not a bitcoin however Bitcoin uses the blockchain technology.
 - It's a distributed ledger: Blockchain is a ledger which is quickly and easily accessed by any person. It's distributed.
 - It's immutable: you can add anyting to blockchain but can't edit or delete it. 

&nbsp; 
&nbsp;  

### How public blockchain Works 🤼
 - Every Block contains a hashed reference to the block before it, So that you can trace every transaction all the way back to genesis block.
 - Cryptographic Security: Last Line (Hash) is repeated at the first line in the next block. This is why it is called chain of blocks. Altering any data in block 1, means the last line will change and will not match the first line in block 2.


&nbsp; 
&nbsp;  


 ### Hashing (Very important for DeFi) #️⃣ ❇

 **A Simple Hash** 
 Suppose i send an email to Steve Wazniak, However he needs to verify that what i sent him is exactly what he recieved.
  - Emails contains a single word "hello".
  - Encode the word (a=1, b=2, z = 26), so 8 5 12 12 15
  - Multiply number to get 86400
  - I post the hash on my website. after Steve Wazniak gets my email, She does the same hash and checks my website.
  - If the message was corrupted the hash will not match.
  - For Example the corrupted message is hallo instead of hello. So the hash will be completely different.
  - This is hash is little bit simple and causes a collison.

&nbsp; 

  **SHA-256 (Secure Hashing Algorithm)**
  This algorithm is also used by bitcoin.
  - Hashing is a one way function.
  - Hashing is not a encryption because you can't decrypt.
  - The output of SHA-256 is 256 bits longer no matter how big or small is the input.

&nbsp; 


   **Keccak-256 Algorithm**
  This algorithm is also used by ethereum.
  - Different hashing algorithm have different outputs from the SHA-256 for the same input.

&nbsp; 
&nbsp;  



### What is proof of Work and How Does it Work ⚒
Proof of Work (PoW) is the original consensus algorithm in a blockchain network. The algorithm is used to confirm the transaction and creates a new block to the chain. In this algorithm, minors (a group of people) compete against each other to complete the transaction on the network. The process of competing against each other is called mining. As soon as miners successfully created a valid block, he gets rewarded. The most famous application of Proof of Work(PoW) is Bitcoin.

Proof of work (PoW) is a decentralized consensus mechanism that requires members of a network to expend effort solving an arbitrary mathematical puzzle to prevent anybody from gaming the system.
- Proof of work is used widely in cryptocurrency mining, for validating transactions and mining new tokens.
- Due to proof of work, Bitcoin and other cryptocurrency transactions can be processed peer-to-peer in a secure manner without the need for a trusted third party.
- Proof of work at scale requires huge amounts of energy, which only increases as more miners join the network.
- Proof of Stake (POS) was one of several novel consensus mechanisms created as an alternative to proof of work.


&nbsp; 
&nbsp;  

### What is proof of Stake then and difference between POW (Proof Of Work) and POS(Proof of Stake) ? 
PoS is a consensus mechanism that randomly assigns the node that will mine or validate block transactions according to how many coins that node holds. The more tokens held in a wallet, the more mining power is effectively granted to it. While PoS is far less resource-intensive, it has several other flaws including a greater chance of a 51% attack in smaller altcoins and incentives to hoard tokens and not use them.


&nbsp; 
&nbsp;  



### ERC20 And ERC721
 - ERC20 is a fungible token. 
 - ERC721 is a non fungible token
 - Benefits of these standards is that application developers can code for one interface, and supports every possible token that implements that interface.


&nbsp; 
&nbsp;  


### What are Oracle 
 - Ethereum blockchain only knows what happens on the Ethereum blockchain. The information needed from outside the Ethereum blockchain oracle solves this problem.
 - An oracle is the data source for reporting information external to the blockchain.

 **Oracle implementation**
  - Ethereum based platform known as chainlink is designed to solve the oracle problem by using an aggregation of data sources. 



&nbsp; 
&nbsp;  


## Problems that DeFi solves.

&nbsp; 
&nbsp;  

### Inefficiency, limited access, transparency

**Inefficiency**
  * DeFi can accomplish financial transaction with high volumes of assets and low friction that would generally be larger organizational burden for traditional finance.
  * In the case of ethereum based DeFi, the contracts can be used by anyone who pays the gas fee.
  * Fork the open source code,  Copy and reuse the existing code with upgrades or improvements and make your own completely different business.

**Limited Access**
DeFi gives large underserved groups, such as the global population of the unbanked as well as small businesses, that employs the substential portion of the workforce direct access to financial services.

**Transparency or Opacity**
Traditional banks or centralized banks are not usually transparent.
 - DeFi elegantly solves the transparency problems through the open and contractual nature of agreements.
 - We will explore how smart contracts and tokenization improves transparency within DeFi.
 - Smart Contracts are transparent. The parties can read the contracts themselves.
 - Ensuring appropriate behaviour in smart contracts.
 - Token Contract: Tokenization allows for transparent ownership and users can know excatly how many tokens are in the system.
