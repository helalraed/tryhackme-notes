# 🔐 Public Key Cryptography

## 🧠 Overview

Public key cryptography (asymmetric encryption) uses two keys:

* **Public Key** → Used for encryption
* **Private Key** → Used for decryption

---

## 🔑 Key Exchange Problem

Symmetric encryption is fast but requires sharing a secret key securely.
Asymmetric cryptography solves this problem.

---

## 🔄 Diffie-Hellman Key Exchange

* Allows two parties to generate a shared secret without sending it
* Uses public values and private secrets
* Final result: both parties compute the same secret key

### Key Idea

> The key is never transmitted, only calculated.

---

## 🔐 RSA

* Based on difficulty of factoring large numbers
* Public Key = (n, e)
* Private Key = (n, d)

### Key Idea

> Easy to multiply, hard to factor

---

## 🔏 Digital Signatures

* Created using **private key**
* Verified using **public key**

### Purpose

* Authentication
* Integrity

---

## 🌐 Certificates

* Used to verify server identity
* Issued by Certificate Authorities (CA)

### Chain of Trust

```plaintext
Website → CA → Trusted by browser
```

---

## 🔑 SSH Key Authentication

* Public key stored on server
* Private key used by client
* More secure than passwords

---

## 📧 PGP / GPG

* Used for encryption and digital signatures
* Common in email security

### Commands

```bash
gpg --full-gen-key
gpg --decrypt file.gpg
gpg --import keyfile
```

---

## ⚔️ Attacks

* **Brute Force** → Try all possibilities
* **Dictionary Attack** → Try common passwords

---

## 🎯 Takeaways

* Asymmetric cryptography solves key exchange
* Diffie-Hellman generates shared keys
* RSA provides encryption and signatures
* Certificates establish trust
