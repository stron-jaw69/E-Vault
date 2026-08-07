# E-Vault
🔐 A cryptography tool that implements secure software engineering, modern encryption techniques, test-driven development, and modular python application design
# Objectives 🎯
- **Project Base:** Provide both password-based and hybrid public-key encryption workflows
- Derive robust encryption keys from passwords using scripts
- Apply authenticated encryption using Advanced Encryption Standard (AES-256)
- Integrate hybrid encryption using RSA-OAEP-SHA256 key wrapping
- Provide reusable cryptographic API and command line interface
# Features 🖌️
### 1. Symmetric Encryption
- 256-bit encryption keys
- Random 96-bit GCM nonces
- AES-256-GCM authenticated encryption 
### 2. Password-Based Encryption
- Unique secure random salts for password hashing
- Key derivation using scrypt
- Increased resistance to brute-force attacks with configurable scrypt parameters
### 3. Hybrid Encryption
- Support 3072-bit and 4096-bit RSA keys
- Securely wrapping generated AES session keys.
- RSA-OAEP-SHA256 key encryption
### 4. Secure Container Format
- Authenticated encryption metadata
- File metadata stored in structured header
- File format: Custom encrypted .cryp
# Technical Stack ⚙️
Control Type | Algorithm
-------|-------------  
**Password KDF**| scrypt
**Encryption**| AES-256-GCM
**Key Wrapping**| RSA-OAEP
**Random Number**| Secure RNG
### 1. Programming Language
- Python 3.11+
### 2. Library
- PyCryptodome
### 3. Testing Framework
- pytest

