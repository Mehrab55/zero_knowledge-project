🔐 Zero Knowledge Proof (ZKP) Project

A beginner-friendly implementation of Zero-Knowledge Proofs (ZKP) using Circom. This project explores how one party can prove that a statement is true without revealing the actual information behind it.

📌 About the Project

Zero-Knowledge Proofs are cryptographic techniques that allow a Prover to convince a Verifier that a particular statement is true without disclosing the underlying secret information.

This project aims to understand the fundamentals of zero-knowledge cryptography, circuit development, and proof generation using Circom.

🎯 Objectives

- Understand the fundamentals of Zero-Knowledge Proofs.
- Learn how to write arithmetic circuits using Circom.
- Understand Prover and Verifier concepts.
- Explore circuit compilation and witness generation.
- Learn the process of generating and verifying cryptographic proofs.

🛠️ Technologies Used

- Circom – Domain-specific language for writing arithmetic circuits.
- SnarkJS – JavaScript library for generating and verifying zk-SNARK proofs.
- Node.js – JavaScript runtime environment.
- Visual Studio Code – Code editor.

⚙️ Installation & Setup

1. Clone the Repository

git clone https://github.com/Mehrab55/zero_knowledge-project.git

2. Navigate to the Project

cd zero_knowledge-project

3. Install Dependencies

Install Node.js and npm, then install SnarkJS:

npm install -g snarkjs

4. Install Circom

Follow the official installation instructions:

https://docs.circom.io/getting-started/installation/

Check the installations:

circom --version
snarkjs --version
node --version

🔍 How Zero-Knowledge Proofs Work

The basic ZKP process involves three main steps:

1. Prover: Generates a proof using private information.
2. Verifier: Checks whether the generated proof is valid.
3. Verification: Confirms the statement without revealing the secret.

📂 Project Structure

zero_knowledge-project/
│
├── README.md
├── circuits/
│   └── circuit.circom
│
├── input.json
├── build/
│
└── package.json

Note: The structure above is a suggested organization for the project.

🚀 Future Improvements

- Implement different types of arithmetic circuits.
- Explore zk-SNARK protocols.
- Improve proof generation and verification.
- Build practical applications using Zero-Knowledge Proofs.

📚 Learning Resources

- "Circom Documentation" (https://docs.circom.io/)
- "SnarkJS Documentation" (https://github.com/iden3/snarkjs)
- "Zero-Knowledge Proofs – Ethereum" (https://ethereum.org/en/zero-knowledge-proofs/)

👩‍💻 Author

Mehrab Fatma

GitHub: "@Mehrab55" (https://github.com/Mehrab55)

---
