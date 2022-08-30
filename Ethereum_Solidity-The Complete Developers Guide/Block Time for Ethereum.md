Self Account
	- Account number
	- Public key
	- Private key
		- Hex Number

- Hash that is less than some **target value**
- The hash is looking for a specific pattern
- Proof of work analogy
	- Imagine you have a handful of 64 dice
	- Goal is to roll numbers to less than 100
	- Would take a while
- Time to find a solution
	- Block Time
- The number gets adjusted every time
	- If the block time is high, raise the target number
	- If the block time low, lower the target number
- Example, we want to keep the hash within 15 seconds
	- Block #100 -> Find a hash less than 1000 -> takes 20 secons
	- Block #101 -> Find a hash less than 10 000 -> takes 5 seconds
	- Block #102 -> Find a hash less than 5 000 -> takes 17 seconds
	- Block #103 -> Find a hash less than 4 000 -> takes 15 seconds

https://etherscan.io/chart/blocktime
	