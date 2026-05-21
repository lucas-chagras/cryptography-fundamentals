# Hashing and Salting

## Hash Functions

Hash functions transform data into fixed-length values.

In secure systems, passwords should never be stored as plaintext.

Instead, systems store cryptographic hashes.

---

## One-Way Hash Functions

One-way hash functions are designed to:

- Be easy to compute
- Be difficult to reverse
- Detect data modifications

Small changes in the input produce completely different hashes.

---

## Cryptographic Hash Functions

Cryptographic hash functions are used for:

- Password protection
- Data integrity
- Authentication systems
- Digital signatures

Examples:
- SHA-256
- SHA-512

---

## Salting

Salting adds random values before hashing passwords.

This helps protect against:

- Rainbow table attacks
- Precomputed hash attacks
- Password reuse analysis

---

## Security Importance

Without salting, identical passwords generate identical hashes.

Salting significantly increases password security in leaked databases.

---

## Key Takeaway

Secure systems protect credentials using hashing and salting instead of storing raw passwords.
