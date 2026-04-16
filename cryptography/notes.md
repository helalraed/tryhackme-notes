# 🔐 Cryptography Basics

## 🧠 What is Cryptography?

Cryptography is the practice of securing communication so that only intended parties can read and modify the data.

---

## 🎯 Goals of Cryptography

* **Confidentiality** → Prevent unauthorized reading
* **Integrity** → Prevent unauthorized modification
* **Authentication** → Verify identity

---

## 🔑 Key Terms

* **Plaintext:** Original readable data
* **Ciphertext:** Encrypted unreadable data
* **Cipher:** Algorithm used for encryption/decryption
* **Key:** Secret value used in encryption
* **Encryption:** Converting plaintext → ciphertext
* **Decryption:** Converting ciphertext → plaintext

---

## 🔐 Caesar Cipher

* Shifts letters by a fixed number
* Easy to break (only 25 keys)
* Example:

```plaintext id="cx0l8w"
HELLO → KHOOR (key = 3)
```

---

## 🔄 Symmetric Encryption

* Same key for encryption and decryption
* Fast but key sharing is a problem

### Examples:

* AES (secure)
* DES (insecure ❌)

---

## 🔑 Asymmetric Encryption

* Uses two keys:

  * Public key (encryption)
  * Private key (decryption)

### Examples:

* RSA
* Diffie-Hellman
* ECC

---

## 🧠 XOR Operation

* Same bits → 0
* Different bits → 1

```plaintext id="x7kt0k"
A ⊕ A = 0  
A ⊕ 0 = A  
```

### Encryption:

```plaintext id="0kjd9i"
C = P ⊕ K
P = C ⊕ K
```

---

## ➗ Modulo Operation

* Remainder after division

```plaintext id="vlfk3m"
23 % 6 = 5
```

* Not reversible
* Result always between 0 and n-1

---

## 💡 Security Notes

* DES is outdated and insecure
* Always use strong algorithms (AES, RSA)
* Cryptography is used in HTTPS, SSH, banking

---

## 🎯 Takeaways

* Cryptography ensures secure communication
* Key management is critical
* XOR and modulo are basic building blocks
