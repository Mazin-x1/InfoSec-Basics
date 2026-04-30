# Basic Cryptographic Concepts  

---

## 📌 Overview
This module introduces fundamental cryptographic concepts used to secure data, verify integrity, and establish trust in modern systems.

It covers:
- Cryptographic terminology
- Hashing algorithms (SHA & MD5)
- Symmetric vs Asymmetric encryption
- Public key cryptography fundamentals

---

## 🧠 Cryptographic Terminology

![Encryption Concept](https://static.vecteezy.com/system/resources/previews/061/851/903/non_2x/minimalist-icon-of-a-padlock-merged-with-a-circuit-board-represents-digital-security-encryption-or-data-protection-ideal-for-technology-or-cybersecurity-themes-vector.jpg)

- **Plaintext**  
  Readable, unencrypted data  

- **Ciphertext**  
  Encrypted, unreadable data  

- **Cipher**  
  Algorithm used to encrypt/decrypt data  

---

## 🎭 The Cast of Characters

![Alice Bob Mallory](https://upload.wikimedia.org/wikipedia/commons/7/7c/Alice-bob-mallory.jpg)

- **Alice** → Sender  
- **Bob** → Receiver  
- **Mallory** → Attacker  

---

## 🔐 Hashing Algorithms

![Hashing Process](https://media.geeksforgeeks.org/wp-content/uploads/20190913233848/Untitled-Diagram.drawio-1.png)

### Key Properties
- **Fixed Length Output**
- **One-Way Function**
- **Data Integrity Verification**

### Common Algorithms
- **SHA-256** → Secure, industry standard  
- **MD5** → Fast but vulnerable  

### 🔴 Security Insight
Collision resistance is critical — weak hashing (like MD5) can be exploited in real-world attacks.

---

## 🔑 Symmetric Encryption

- Uses **one shared secret key**  
- Fast → suitable for bulk data  
- Main risk: **key distribution problem**

---

## 🔓 Asymmetric Encryption

- Uses **key pair (Public / Private)**  
- Public key → encryption  
- Private key → decryption  

### Key Concepts
- Identity verification  
- Secure key exchange  
- Higher computational cost  

---

## 🔄 How Hybrid Encryption Works

- Data is encrypted using a **symmetric key**  
- Symmetric key is encrypted using **public key**  
- Receiver decrypts key using **private key**  
- Then decrypts data  

> This model is used in real-world protocols like HTTPS.

---

## ⚙️ Public Key Algorithms

- **RSA**  
  Based on large prime factorization  

- **ECC (Elliptic Curve Cryptography)**  
  Same security as RSA with smaller key sizes  

- **Trapdoor Function**  
  Easy to compute, hard to reverse  

---

## ⚖️ Symmetric vs Asymmetric

| Feature | Symmetric | Asymmetric |
|--------|----------|-----------|
| Key Usage | Single key | Public/Private |
| Speed | Fast | Slow |
| Use Case | Data encryption | Identity & key exchange |
| Key Distribution | Difficult | Easier |

---

## 🛡️ Security Insight

Modern systems do not rely on a single method —  
they combine hashing, symmetric, and asymmetric cryptography to achieve:

- Confidentiality  
- Integrity  
- Authentication  

---

## 🙌 Conclusion
Cryptography is the backbone of information security, enabling secure communication, data protection, and trust in digital systems.
