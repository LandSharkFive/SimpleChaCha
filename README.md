# Simple Cha Cha

A streamlined, "no-nonsense" implementation of the Cha Cha stream cipher in C#. Designed for low-effort integration where a functional, multi-pass encryption layer is required without the bloat of enterprise security suites.



### The Core Logic
This implementation focuses on the fundamental Cha Cha quarter-round transformations. It is built for clarity and speed, providing a reliable way to encrypt and decrypt data blocks via simple addition and bitwise operations.

### ⚠️ Critical Security Warning
To maintain the integrity of the encryption, the **Nonce must be unique** for every single message. 
* **Never reuse a Nonce.** * Reusing a Nonce with the same key exposes the keystream, effectively rendering the encryption useless against even basic cryptanalysis.

### What's Under the Hood (and What's Not)
This version is stripped down to the essentials. To keep the codebase lean and "educational," the following features are **deliberately omitted**:
* **Poly1305 MAC:** No built-in message authentication.
* **Padding:** Handling of non-block-aligned data is left to the user.
* **Sub-Key Generation:** Standard key-derivation functions (KDF) are not included.
* **Secure Containers:** Key storage is not hardened against memory-dump attacks.

### Build & Execution
* **Language:** C#
* **Requirement:** Visual Studio 2022+
* **Sample:** See `sample.txt` for a demonstration of a standard encryption/decryption pass.

---

### References
Technical specifications and algorithmic deep-dives are located in `references.txt`.
