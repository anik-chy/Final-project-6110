# RSA Implementation

This repository contains the implementation of the INSE 6110 project, focused on understanding and implementing the RSA encryption algorithm without using pre-built libraries. The project is divided into two main parts: **Simple RSA Encryption/Decryption** and **Signature/Verification**.

---

## Objectives
1. **RSA Implementation**: Develop a simplified RSA encryption and decryption system.
2. **Signature and Verification**: Implement message signing and verification using RSA keys.

---

## Features
### Part 1: Simple RSA (Encryption and Decryption)
- **Prime Number Generation**: Randomly generate two 16-bit prime numbers.
- **Key Generation**:
  - Compute `N = p * q`.
  - Calculate `Phi(N) = (p-1) * (q-1)`.
  - Generate a public key `(N, e)` and a private key `d`.
- **Encryption**:
  - Encrypt messages using the recipient's public key `(N, e)`.
  - Publish encrypted messages to a designated database.
- **Decryption**:
  - Decrypt received messages using the private key `d`.

### Part 2: Signature and Verification
- **Signing**:
  - Create a digital signature for your name using your private key `d`.
  - Publish the signature along with your name.
- **Verification**:
  - Verify the authenticity of a partner's signature using their public key `(N, e)`.

---

## Deliverables
1. **Code**:
   - Fully functional Python implementation of the RSA algorithm and associated operations.
2. **Video Demonstration**:
   - A short video showcasing the steps of encryption, decryption, signing, and verification.
3. **Data File**:
   - A `data.txt` file containing formatted RSA parameters and messages.

---

## Usage
- Clone this repository and run the Python scripts to execute RSA encryption, decryption, signing, and verification.
- Detailed instructions are provided in the code comments.

---

## Acknowledgments
This project was developed as part of the INSE 6110 coursework in Winter 2024 at Concordia University. Collaboration and adherence to academic integrity are strictly enforced.

