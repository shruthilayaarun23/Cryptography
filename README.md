# Cryptographic Primitives and Protocols

This repository contains implementations and analysis of foundational cryptographic primitives, secure protocols, and attack simulations. The aim is to explore how cryptographic algorithms function and how they can be both implemented and broken in practice.

## Features

### Stream Ciphers
* **babyGrain**: A minimal version of the Grain cipher.
* **babySalsa**: Simplified Salsa20 stream cipher variant.

### Hash Functions

* **Sponge-based Hashing**: Built using AES as the permutation function.
* **Merkle–Damgård Construction**: Implemented using the Simon block cipher.

### Cryptographic Attacks

* **Padding Oracle Attack**: Exploits CBC mode padding to decrypt ciphertexts.
* **Length Extension Attack**: Targets Merkle–Damgård-based hashes.
* **CBC-MAC Forgery**: Demonstrates forgery of MACs under CBC-MAC with variable-length messages.

### Authenticated Encryption

* **AES-GCM**: Implemented a secure AEAD scheme for confidentiality and authenticity.

