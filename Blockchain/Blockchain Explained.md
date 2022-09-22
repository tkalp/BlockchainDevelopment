## What is a Blockchain?
- Distributed database or ledger that is shared among the nodes of a computer network
- Crutial role in cryptocurrency systems
- Type of shared database that differs froma a typical database in the way that it stores information
	- Blockchain stores data in blocks linked together by cryptography
- As new data comes in, it is entered into a fresh block
- Once the block is filled with data, it is chained onto the previous block, which makes the data chained together in chronological order
- Different types of data can be stored
- Most common use is a ledger for cryptocurrency transactions
- For Bitcoin, blockchain is used in a decentralized way so that no single person or group has control
- All users collectively retain control
- Decentralized blockchains are immutable
- Data entered is irreverssable
- Everything entered is permantently recorded and viewable to anyone


## How does Blockchain work?
- Goal is allow digital information be recorded and distributed, but NOT edited
- Also known as Distributed Ledger Technology (DLT)
- First proposed in 1991
- Bitcoin came out in 2009
- Since first proposal, we have seen blockchain in a number of use cases
	- Cryptocurrencies
	- Decentralized Finance (DeFi) applications
	- Non-fungible Tokens (NFTs)
	- Smart Contracts

### Transaction Process
![image info](Images/TransactionProcess.webp)

### Attributes of Cryptocurrency

![image info](Images/CryptoCurrencyAttributes.webp)

## Blockchain Decentralization
- Imagine a company had 50,000 computers that stored redundant data for its clients
	- Now also imagine that they stored these computers in one warehouse
	- This introduces a single point of failure, what were to happen if the electricity went out at the warehouse?
- Now if that company spreads its computers across multiple locations and networks, we eliminate the single point of failure
	- Also introduces security measures where if one bad actor tries to alter a record, the other nodes would be like 'hell nah man what are u doing? gtfo'
- This is kinda-sorta how Bitcoin works
	- If one user tampers with Bitcoin's record of transaction....they die
	- Just kidding, they'd stay alive....probably.....but all the other nodes could easily pinpoint the node with the incorrect information
		- Let's hope Satoshi is a kind soul
	- This helps establish an exact and transparent order of events, especially when every single transaction and block is timestamped

- Due to this distributed network, we now can't alter any historical transactions due to the other nodes needing to be updated as well
	- Well....good luck with that
- But this is good for things such as 
	- Legal Contracts
	- State Identifications
	- Product Inventory
	- Financial Transactions

- So how do new records or blocks get added to this decentralized magical network?
	- A majority of the network's computing power would need to agree to it
		- Majority nodes have to agree that a block or transaction is valid
	- To prevent bad actos from validating bad transactions, we use
		- Proof of Work (PoW)
		- Proof of Stake (PoS)
	- @todo Link to these

## Transparency
- All transactions can using blockchain technology can be viewed using <a href="https://www.blockchain.com/explorer?utm_campaign=dcomnav_explorer">blockchain explorers</a>
- Every node has a copy of the chain and gets updated as fresh blocks are confirmed and added
- Although blockchains are transparent, all records are encrypted and can only decrypted by the owner's public-private key pair

## Is Blockchain Secure?
- Many ways that blockchain achieves decentralized security and trust
- Each block is store linearly and chronologically on the chain
- They are always added to the "end" of a blockchain
- Once a block has been added, it is almost impossible to go back and alter the contents of the block unless
	- Majority of the network has reached a consensus to do so
- Why is it so hard to change other than consensus?
	- Each has contains its own hash along with the hash of the previous block and a timestamp
	- If a hacker, who runs a node, wants to alter a blockchain and steal crypto from everyone else
	- They could alter their own copy
		- But it wouldn't align with everyone else's during the validity check
		- Thus this copy would be cast away as illegitamate
	- What if they owned 51% of a network?
		- Well then now they have alter the entire chains of 51% of the network
		- Solving the mathematical problems for blocks are not easy and require intensive computing power
		- Because networks are massive in size and continuously growing, there is almost no chance they could succeed with this
			- Maybe with quantum computers they could
		- But even if an attacker managed to pull this off
			- It would not go unnoticed
			- Network members would then hard fork off to a new version of the chain that has not be affected
				- Another security perk of blockchain!
				- Would also cause the affected chain to plummet since no one is mining those blocks anymore

## Bitcoin vs. Blockchain
- First outlined in 1991 by Stuart Haver and W. Scott Stornetta
- They wanted to implement a system where document timestamps were set in stone and were not tampered with
- Bitcoin was one of the very first real-world applications of this system
	- Built on blockchain by Satoshi Nakamoto (alias)
- Bitcoin just uses blockchain as a means to transparency record a ledger of payuments
- Blockchain can be mutably used to record any number of data points
- 


Resources 

https://www.investopedia.com/terms/b/blockchain.asp