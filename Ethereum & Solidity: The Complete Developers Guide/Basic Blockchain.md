### **SHA256 Hash**
- Looks like random numbers
- Fingerprint of some digital input data
- If the input data changes by one character, so does the entire hash
	- If it's a good hash function
- The same input data will always result in the same hash
- Example for SHA256
	- Input Data:  `hash function`
	- Output Data: `04ce4af53ae1b0f46451715ffc43092eab5b23330a6584462d0723732b147c4b`

- The output data will always be the same length (256 bits, or 64 hex characters)


### **Block**
- Contains 
	- a number for the block
	- nonce
	- data
- There is a hash that begins with 4 0s
	- We are going to say that this block is signed
- If we change the data
	- The hash changes and the 4 0s disspear
- So the nonce needs to change
- This is called mining
	- Finding a valid nonce that finds the signature hash


### **Blockchain**
- Chain of these blocks
- Here each block contains the same attributes as the block above
- But also includes the hash of the previous block
	- Almost like a backwards linked list
- Once again, each block needs to follow signature
- If one block gets changed, then it is expensive to mine each of the blocks
	- This is because each block contains a hash of the previous block
- Need to mine leastmost block that is invalid and work your way up


### Distributed 
- Looks the same as the previous block chain
- Now we add in peers
	- Peer A
	- Peer B
	- Peer C
- So if you re-mine a block in a blockchain contained on a node, other peers will show that this one has been modified
- If Peer A has a block modified and re-mined, Peer B and C will vote against this and see that it has been modified
- Done by looking at the hash at the most recent one to view alteration of blocks

### Tokens
- Contains transactions in a block for the data
- Used to remember tokens
- Only remembers transactions (tokens)

### **Coinbase Transaction**
- We add a coinbase in the block
- Where an address recieves a transaction from coins
- It has to balance out
	- Tokens get validated backwards
	- Tracing providence of coins