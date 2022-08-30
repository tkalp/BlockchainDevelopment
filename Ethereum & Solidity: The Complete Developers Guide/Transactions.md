### **Transactions**
- `nonce`
	- How many times the sender has sent a transaction
- `to`
	- Address of account this money is going to
- `value`
	- Amount of ether to send to the target address
- `gasPrice
	- Amount of ether the sender is willing to pay per unit gas to get this transaction processed
- `startGas/gasLimit
	- Units of gas this transaction can consume
- `v, r, s
	- Cryptographic pieces of data that can be used to generate the **senders account address**
	- Generated from the sender's private key
	- Cannot generate the private key from these 3 values
	- https://ethereum.stackexchange.com/questions/15766/what-does-v-r-s-in-eth-gettransactionbyhash-mean
	- https://bitcoin.stackexchange.com/questions/38351/ecdsa-v-r-s-what-is-v






