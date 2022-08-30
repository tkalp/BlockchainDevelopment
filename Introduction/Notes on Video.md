- Symmetric Key Cryptography
	- One key that both parties know
	- Somehow need to share key
	- Establishing secure connection
- Asymmetric Key Cryptography
	- 2 keys
	- Public and Private keys
	- Key Pair
		- Pick one as the public key
		- Pick one as the private key
	- Anything encrypted with key A can only be decrypted with key B
	- Anything encrypted with key B can only be encrypted with Kay A
	- Between two parties
		- There are two key-pairs
			- 2 public keys (Pa and Pb)
			- 2 private keys (A and B)
	- I can encrypt a message with the receipients public key
		- Only they can decrypt the message
		- Confidentiality
	- I can encrypt the message with my private key
		- Can only decrypt with public key
		- Maintains integrity
	- Putting all this together w/ Bob
		- I have a message
		- I encrypt with my private key
		- I encrypt again with Bob's public key
		- Bob can now decrypt the message with his private key and my public key
		- Now we can maintain Confidentiality and Integrity



	