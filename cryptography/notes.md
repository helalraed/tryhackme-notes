# 🔐 Cryptography Basics

## 🧠 What is Cryptography?

Cryptography is the practice of securing communication so that only authorized parties can read and modify the data.

---

## 🎯 Goals of Cryptography

* **Confidentiality** → Prevent unauthorized access
* **Integrity** → Ensure data is not altered
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
* Weak and easy to break (only 25 possible keys)

Example:

```plaintext
HELLO → KHOOR (key = 3)
```

---

## 🔄 Symmetric Encryption

* Uses the same key for encryption and decryption
* Fast but has a key distribution problem

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

```plaintext
A ⊕ A = 0  
A ⊕ 0 = A  
```

### Encryption:

```plaintext
C = P ⊕ K  
P = C ⊕ K  
```

---

## ➗ Modulo Operation

* Returns the remainder after division

```plaintext
23 % 6 = 5
```

* Not reversible
* Result is always between 0 and n-1

---

## 💡 Security Notes

* DES is outdated and insecure
* Always use strong algorithms (AES, RSA)
* Cryptography is used in HTTPS, SSH, and online banking

---

## 🎯 Takeaways

* Cryptography ensures secure communication
* Key management is critical
* XOR and modulo are fundamental concepts
