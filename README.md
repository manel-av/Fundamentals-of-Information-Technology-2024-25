# Fundamentals of Information Technology
## About This Course
This foundational course in Information Technology covers essential cryptographic algorithms, coding theory, and security protocols through five hands-on practical sessions. Students implement core algorithms from scratch using SageMath in Python, gaining deep understanding of their mathematical foundations.

## Practical Sessions Overview
### 1. Arithmetic Fundamentals (Week 1)
#### Key Concepts Implemented:
- Divisibility criteria (7 and 13) without using modulo operations
- Extended Euclidean algorithm (Bezout's identity)
- Quotient rings Z₃[x]/m(x) with:
  - Zero divisor identification
  - Field property verification

### 2. Cyclic Codes (Week 2)
#### Key Components:
- Polynomial operations over GF(2)
- Cyclic shift implementation
- Code validation for cyclic property
- Generator polynomial analysis for length-10 codes
- Message encoding:
  - Via generator polynomial
  - Via generator matrix
- Standard array construction for error correction

### 3. Public Key Cryptography (Week 3)
#### Protocols Implemented:
- Diffie-Hellman key exchange:
  - Parameter validation
  - Discrete logarithm brute-force attack
  - Security estimation for 1024-bit primes
- RSA cryptosystem:
  - NIU-grade encryption table
  - Table-based vs private key decryption
- ElGamal signature existential forgery

### 4. SHA-256 Implementation (Week 4)
#### Hash Function Components:
- Bitwise operations:
  - ROTR (Rotate Right)
  - SHR (Shift Right)
- Core functions:
  - Ch (Choose)
  - Maj (Majority)
  - Σ₀/Σ₁ (Message schedule)
- Full pipeline:
  - Padding
  - Message block expansion
  - Compression function
  - Final hash computation

### 5. Ring Signatures (Week 5)
#### Anonymous Signature System:
- RSA adaptations for large inputs
- Ring structure setup:
  - Key generation (LENGTH=5)
  - Position randomization
- Signature components:
  - Challenge solving (UAB_solve_C)
  - Ring construction (UAB_sign_ring)
  - Verification (UAB_verify_ring_signature)

## Technical Implementation
### Development Environment
- **Primary Tool**: SageMath (v9.0+) Jupyter Notebook
- **Key Libraries**:
  - PyCryptodome (for AES/SHA-256 operations)
  - Sage core libraries (for finite fields/polynomials)
- **System Requirements**:
  - Linux/Ubuntu recommended
  - 4GB RAM minimum
  - Python 3.7+ compatibility

## Learning Outcomes
Through these practicals, students gain:
1. **Deep Algorithm Understanding**:
   - From mathematical theory to executable code
   - Cryptographic primitive construction
2. **Security Awareness**:
   - Attack vectors (forgery, brute-force)
   - Parameter validation importance
3. **Mathematical Programming**:
   - Finite field arithmetic
   - Polynomial ring operations
   - Bitwise manipulation skills
4. **Protocol Design**:
   - Key exchange mechanisms
   - Anonymous authentication
   - Error-correcting codes