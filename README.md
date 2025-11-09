Of course — here’s your **clean, complete English `README.md`**, written in a professional GitHub style.
It clearly states that this repository is **your personal attempt to learn, recreate, and use** the Anchor Escrow 2025 project.

---

````markdown
# 🪙 Anchor Escrow 2025 — Personal Implementation

## 🧠 About This Repository

This repository is **my personal attempt** to recreate, understand, and use the  
[Anchor Escrow 2025](https://github.com/mikemaccana/anchor-escrow-2025) project from scratch.

The goal is to **learn how to build, test, and deploy** a complete Solana program (smart contract)  
using modern tools like Anchor, Rust, and Solana Kit — by doing it myself, step by step.

> ⚠️ This repository is **not the official version**.  
> It’s my own educational implementation based on the open-source project by [mikemaccana](https://github.com/mikemaccana).

---

## 🆕 Learning Objectives

- Understand and work with **Anchor 0.32.1**  
- Build a full **Rust + Solana local environment (LiteSVM)**  
- Use **Solana Kit**, **Kite**, and **Anchor CLI**  
- Run **Rust-based and TypeScript tests**  
- Deploy and interact with the program on a local validator

---

## 📚 Original Project Overview

The Anchor Escrow 2025 program implements an **escrow system**  
that enables secure token swaps between users on Solana.

For example, Alice might offer **10 USDC** in exchange for **100 WIF**.  
Without escrow, either side could fail to deliver, leading to fraud.  
The escrow program ensures both sides receive their tokens only  
after meeting the agreed conditions — safely and without intermediaries.

---

## 🧩 Technologies Used

- 🧰 **Solana CLI**
- 🦀 **Rust** & `cargo`
- ⚓ **Anchor Framework** (v0.32.1)
- 💻 **Node.js** & **npm**
- 🧪 **LiteSVM** for local Rust-based testing

---

## 🚀 Usage

1. **Clone this repository**

   ```bash
   git clone https://github.com/<YOUR_USERNAME>/anchor-escrow-2025-learning.git
   cd anchor-escrow-2025-learning
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run TypeScript tests**

   ```bash
   anchor test
   ```

4. **Run Rust (LiteSVM) tests**

   ```bash
   cd programs/escrow
   cargo test
   ```

5. **Deploy the program**

   ```bash
   anchor deploy
   ```

---

## 🧪 Versions Used (for compatibility)

```
OS:
  Windows / WSL2
Solana CLI:
  solana-cli 2.1.21 (Agave)
Anchor:
  anchor-cli 0.32.1
Node:
  v22.x
Rust:
  rustc 1.86.0 (05f9846f8 2025-03-31)
build-sbf:
  solana-cargo-build-sbf 2.1.21
```

> Using different versions may cause compatibility issues.

---

## 🙏 Credits

Based on the open-source project
[**Anchor Escrow 2025** by mikemaccana](https://github.com/mikemaccana/anchor-escrow-2025).
This version was recreated and customized for **learning and experimentation**.

---

## 💡 Author

**CuzimSmoky**
Learning Rust, Solana, and Anchor — one block at a time 🦀⚓

```