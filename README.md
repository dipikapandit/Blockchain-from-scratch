# Bitcoin Blockchain from Scratch with Python

A beginner-friendly implementation of a Bitcoin-inspired blockchain in Python, built while exploring how Bitcoin works under the hood.

## 🚧 Project Status

Currently under development. Building the core blockchain structure and exploring Proof of Work mining.

## ✅ Implemented So Far

- [x] Block structure
- [x] Block header implementation
- [x] Blockchain initialization
- [x] Genesis block creation
- [x] SHA-256 double hashing utility (`hash256`)
- [x] Merkle root generation for transaction data
- [x] Initial Proof of Work mining integration

## 🛠️ Tech Stack

- Python
- Flask (planned / tutorial dependencies)
- NumPy and Pandas (installed in development environment)
- PyCryptodome
- Git & GitHub

## 📂 Project Structure

```text
Bitcoin/
├── Blockchain/
│   └── Backend/
│       ├── core/
│       │   ├── block.py
│       │   ├── blockheader.py
│       │   └── blockchain.py
│       └── util/
│           ├── __init__.py
│           └── util.py
├── demo.py
├── requirements.txt
└── .gitignore
```

## ⚙️ Setup

Clone the repository:

```bash
git clone <your-repository-url>
cd Bitcoin
```

Create a virtual environment:

```bash
python3 -m venv .venv
```

Activate it (macOS):

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🎯 Learning Goals

- Understand how blocks and block headers work.
- Explore cryptographic hashing.
- Understand Proof of Work and nonce generation.
- Learn how blockchain validation and consensus work.
- Eventually explore wallets, transactions, and peer-to-peer networking.

## 📌 Disclaimer

This is an educational project inspired by Bitcoin's architecture. It is not intended for handling real Bitcoin or cryptocurrency transactions.
