# Cryptographic Techniques in Boolnetwork
This repository contains a growing set of research documents about the underlying cryptography techniques that will be used in boolnetwork.
Content may include BLS signature, threshold signature, zero-knowledge proof, homomorphic encryption, multi-party computation, etc. More content will be added as with the development of boolnetwork in the future.
At present, we start with introducing the threshold signature(TSS) techniques and its comparisons with other similar techniques. TSS is an advanced cryptographic technique that is used to protect key security by allowing multiple players to share the power to generate a signature on a message. More specifically, a private key is shared among n players, and a threshold parameter t is defined such that any subgroup of t+1 players can jointly generate a signature, whereas any adversary can neither forge a signature nor learn any information about the private key even the adversary corrupts up to t players. In TSS, the expensive distributed key generation and signation generation are all performed off-chain, and only one signature verification is performed onchain. Hence, TSS is flexible,efficient, and compatible with most of the blockchains and has higher degrees of privacy than other similar techniques, such as multi-signature. A more detailed introduction can be seen in https://github.com/boolnetwork/Cryptographic-techniques-in-boolnetwork/blob/master/document.pdf
