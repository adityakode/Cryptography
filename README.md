# Cryptography

## Blockchain Cryptograhy Docuementation

## Blockchains

Purpose of Blockchain :

- No person or organization can control a particular process

Why Blockchain? :

- Blockchain was invented to solve for trust and to create a system that is completely safe and secure from various harms

Cryptographic Hash Functions :

- Conversion of any input of any size converted into fixed size output is known as function of Cryptographic Hash Function
- Best method for hashing is Modulo Division Method (accordingto Wikipedia)

# Digital Signatures

Public Key Cryptography :

Cryptography

- Cryptography in early stages was study of encrypting message so that they could not be decrypted even if intercepted and it was used for important secrets.
  Symmetric-Key Cryptography :

- Symmetric-key cryptography refers to encryption methods in which both the sender and reciever share the same key

Personal Computing

- Public Key was introduced to make the blockchain more secure rather than sharing keys directly.

- Public Key Cryptography is considered as Asymmetric Encryption in that only one party has access to private key.

- And only the person having key can decrypt the message sent to him!

RSA and ECDSA Algorithms

- Both Algorithms used for public key cryptography

- RSA algorithm is very difficult to be decrypted and is still an unsolved mystery in Computer Science.

- ECDSA algorithm uses Elliptic Curves and provide same level of security as other public key algorithms with smaller key sizes

- It is the Digital Signing Algorithm used by Bitcoin, specially the `secp256k1` curve

- `secp256k1` is used in Bitcoins public-key crpytography. `secp256k1` was constructed in a special non-random way which allows for especially efficient computation. As a result, it is often more than 30% faster than other curves if the implementation is sufficiently optimized.

- _Diffie-Hellman Key Exchange_ is used to get that Secret Key

# Proof of Work and Mining

Consensus Mechanisms :

- Consensus means coming to general agreement.
- Blockchain consensus typically means at least 51% of nodes are in agreement over the current global state of the network.

Proof-of-work and Minning :

- POW networks will typically have some sort of target_difficulty
- If a Miner wants to add a new block then must find a POW lower than the network target difficulty.
- If Miner follows all consensus rules then his block gets valid and miner gets paid for mining a valid transaction.

How does Bitcoin use Proof of Work?

- POW act as a security of the Bitcoin system. Thousands of nodes are working to find hashes of data. And if you want to hash data more than other miners then you should come up with more computing power than all the nodes in the entire system.
- This is referred to as a 51% attack because you need 51% of the total hashing power in the network.

Hashcash Concept :

- Hashcash is a POW system used to limit E-mail spam and denial of sevice attacks.
- Hashcash is a cryptographic hash based POW algorithm that requires a selectable amount of work to compute, but the proof can be verified efficiently.
