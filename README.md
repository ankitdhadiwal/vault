# 🏦 Vault Program (Solana + Anchor)

A secure and composable on-chain vault smart contract built using the [Anchor](https://book.anchor-lang.com/) framework on the [Solana blockchain](https://solana.com/). The Vault Program is designed to manage and store assets (SOL or SPL tokens) securely, with support for advanced use cases like yield farming, governance, or escrow systems.

---

## 🚀 Features

- ✅ Create deterministic vaults using seeds
- ✅ Deposit and withdraw native SOL or SPL tokens
- ✅ Owner-controlled or permissionless vault configuration
- ✅ Cross-program invocation (CPI)-ready
- ✅ Upgradeable via Anchor's program upgrade authority

---

## 📦 Program Structure

```bash
vault/
├── Cargo.toml
├── programs/
│   └── vault/
│       ├── src/
│       │   ├── lib.rs         # Main program logic
│       │   ├── state.rs       # Vault account definitions
│       │   └── instructions/  # Handlers for init, deposit, withdraw
├── tests/
│   └── vault.ts               # Anchor Mocha test suite
├── migrations/
└── Anchor.toml
