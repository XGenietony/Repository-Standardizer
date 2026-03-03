# repo_standardizer Skill

This ClaudeCode Skill automatically refactors repositories into a clean,
modular, maintainable architecture.

Supports:

- Python
- Node.js
- TypeScript
- React / Vue
- Go
- Rust
- Java
- AI agent repositories

---

# Features

- Splits monolithic files
- Creates modular architecture
- Enforces separation of concerns
- Fixes import dependencies
- Generates missing modules
- Standardizes folder structure

---

# Standard Python Structure
repo/
configs/
models/
services/
handlers/
utils/
agents/ (optional)
middlewares/ (optional)
tests/
main.py


---

# Usage

In ClaudeCode:

standardize this repository

or

refactor repo using repo_standardizer

---

# Guarantees

No business logic in:

- main.py
- handlers
- controllers

Business logic only in services.

---

# Designed for

Production-grade repositories.