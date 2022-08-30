Public-key Cryptography
	- Aka asymmetric crypto
	- Encryption scheme that uses two mathematically related keys
		- Public and Private key
	- Public key is used to encrypt
	- Private key is used to decrypt
	- Cannot determine the private key based on the public key
		- Public keys can be freely shared because of this


- Public keys are stored on digital certificates since they are too large
	- This is good for secure transport and sharing
	- Private keys are stored in software os OS that is being used
	- This certificates are issued by Certificate Authorities (CAs)

Business applications
- Digital signatures
	- Content is digitally signed with an individual's private key and can only be decrypted with the individual's public key
- Encryption
	- Opposite of digital signature where a party (A) signs with public key of another party (B) and only B can decrypt with their private key

Security Benefits of Digital Sigs
- Authentication
- Non-repudiation
- Integrity

Security Benefits of Encryption
- Confidentiality
- Integrity