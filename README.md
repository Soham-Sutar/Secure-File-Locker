# 🔐 Secure File Locker

A **Java Swing-based desktop application** for securely encrypting and decrypting files using modern cryptographic standards like **AES-GCM (256-bit)** and **PBKDF2**.

---

## 📌 Features

- 🔒 **Strong Encryption**
  - AES-GCM (256-bit) for authenticated encryption
  - PBKDF2 with high iteration count for secure key derivation

- 📂 **Supports Multiple File Types**
  - Images (`.png`, `.jpg`)
  - Documents (`.pdf`, `.ppt`, `.docx`)
  - Archives (`.zip`)
  - And more...

- 🖱️ **User-Friendly Interface**
  - Drag & Drop file support
  - Clean and modern UI using Java Swing
  - Progress bar for encryption/decryption

- 🛡️ **Security Enhancements**
  - Temporary file-safe decryption (no partial file leakage)
  - Password wiping from memory
  - Authentication check (detects wrong password/tampered files)

- ⚡ **Performance**
  - Buffered streaming for handling large files
  - Background processing using `SwingWorker`

---

## 🖥️ Screenshots

<p align="center">
  <img src="screenshots\java2.png" width="600"/>
</p>

<p align="center">
  <img src="screenshots\java1.png" width="600"/>
</p>
---

## 🚀 Getting Started

### ✅ Prerequisites

- Java 11 or higher

---

### ⚙️ Compilation & Execution

```bash
javac SecureFileLocker.java
java SecureFileLocker