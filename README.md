# Classical Cryptography Algorithms Toolkit

## Overview

Classical Cryptography Algorithms Toolkit is an educational Python project that demonstrates the implementation of several historical encryption and decryption algorithms used in the foundations of cryptography.

The project provides practical implementations of multiple classical ciphers, allowing users to understand encryption concepts, key management, substitution techniques, and transposition methods through hands-on experimentation.

This toolkit is ideal for cybersecurity students, cryptography beginners, and educational demonstrations in information security courses.

---

## Implemented Algorithms

### Caesar Cipher

A substitution cipher that shifts each letter by a fixed number of positions in the alphabet.

Features:

* Encryption
* Decryption
* User-defined shift key
* Uppercase and lowercase support

---

### Columnar Transposition Cipher

A transposition-based encryption method that rearranges characters according to a specified column structure.

Features:

* Encryption
* Decryption
* Configurable column key
* Text reconstruction logic

---

### Auto-Key Cipher

A polyalphabetic substitution cipher that extends the encryption key using plaintext characters.

Features:

* Automatic key expansion
* Encryption
* Decryption
* Alphabet-based transformations

---

### Hill Cipher

A matrix-based encryption algorithm utilizing linear algebra and modular arithmetic.

Features:

* Matrix key generation
* Encryption using matrix multiplication
* Modular inverse matrix calculation
* Decryption support
* NumPy integration

---

### Atbash Cipher

A classical monoalphabetic substitution cipher that reverses the alphabet.

Features:

* Symmetric transformation
* Encryption and decryption using the same function
* Uppercase and lowercase support

---

## Technologies Used

* Python
* NumPy
* Mathematical Cryptography Concepts
* Matrix Operations
* Modular Arithmetic

---

## Learning Objectives

This project demonstrates:

* Classical cryptographic techniques
* Encryption and decryption processes
* Key-based security mechanisms
* Matrix mathematics in cryptography
* Modular arithmetic operations
* Historical cipher systems

---

## Project Structure

```text
Classical-Cryptography-Toolkit
│
├── caesar_cipher.py
├── columnar_transposition.py
├── auto_key_cipher.py
├── hill_cipher.py
├── atbash_cipher.py
│
└── README.md
```

---

## Supported Algorithms

| Algorithm              | Encryption | Decryption |
| ---------------------- | ---------- | ---------- |
| Caesar Cipher          | Yes        | Yes        |
| Columnar Transposition | Yes        | Yes        |
| Auto-Key Cipher        | Yes        | Yes        |
| Hill Cipher            | Yes        | Yes        |
| Atbash Cipher          | Yes        | Yes        |

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/classical-cryptography-toolkit.git
```

Install required libraries:

```bash
pip install numpy
```

Run any algorithm individually:

```bash
python caesar_cipher.py
```

---

## Educational Applications

This project can be used for:

* Cryptography courses
* Cybersecurity laboratories
* Information security demonstrations
* Algorithm analysis exercises
* Encryption fundamentals training

---

## Future Improvements

* Graphical User Interface (GUI)
* Additional classical ciphers
* Frequency analysis tools
* Cipher cracking demonstrations
* Visualization of encryption processes
* Web-based cryptography playground

---

## Author

Developed as an educational cryptography project demonstrating the implementation of classical encryption and decryption algorithms using Python.
