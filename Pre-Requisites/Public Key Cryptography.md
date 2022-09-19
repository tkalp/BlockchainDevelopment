## What is Public Key Cryptography?
- An encryption scheme that uses two mathematically related, but not identical, keys
	- A public key and a private key
- Unlike symmetric key algorithms that reply on one key to both encrypt and decrypt messages, each key in this scheme performs a unique function
- You can use them in the following ways
	1. Public key to encrypt and Private Key to Decrypt
		- Provides confidentiality since only the owner of the private key can de-cipher the ciphertext
	2. Private key to encrypt and Public Key to Encrypt
		- Provides Integrity since only the owner of the private key can encrypt the message and thus is the only one that can change the plaintext

- It is computationally infeasable to comput the private key based on the public key
	- Due to this, the public key can be freely shared
		- Allows users to encrypt concent and verify digital signatures
	- The private key can be kept secret
		- Allows for decrypting content and creating digital signatures

- Public keys need to be shared but are too long to be easily remembered
	- Thus they are stored on digital certficates for secure transport and sharing
	- Digital certificates are issued by Certificate Authorities
- Private keys are not shared
	- Thus they can be stored in software or OS
	- Can also be stored in some types of hardwares

### Business Applications
The following are the main business applications for public-key cryptography
1. **Digital Signatures**
	- Content is signed by a Alice's private key (only Alice knows this key) and verified by Alice's public key (everyone knows this key)
2. **Encryption**
	- Content is encrypted by Alice's public key and can only be decrypted by Alice's private key

### Security Benefits of Digital Signatures
Remember, a digital signature is content that is signed by a key that only ONE party has access to. Alice signs this content with her private key and can only be verified by Alice's public key, typically provided via digital certificates. This provides

1. **Authentication**
	- Due to the nature of how private keys work, only the owner of them can sign the content and can be verfied by the owner's public key.
2. **Non-repudiation**
	- Since the owner is the only one with access to the private key used to generate the digital signature, they cannot claim that it wasn't them who applied the signature
3. **Integrity**
	- When the signature is verified by comparing the content the decrypted version of the content, if there is one minor change, it would fail and integrity check.

### Security Benefits of Encryption
If Alice and Bob are communicating with each other, one way of instantiating a end-to-end encrypted channel is to use each other's respective public key to encrypt messages sent and forth to each other. That is, if Alice is sending a message to Bob, then Alice use's Bob's public key to encrypt the message and Bob and only Bob will be able to decrypt the message using his private key. There are many benefits to this approach 

1. **Confidentiality**
	- Since Bob is the only party that can decrypt messages encrypted from his public key, that achieves confidentiality
2. **Integrity**
	- If a message is altered after it has been encrypted using Bob's public key, then that would cause the decryption process to fail. Thus we have integrity of messages

Resources used
- https://www.globalsign.com/en/ssl-information-center/what-is-public-key-cryptography



