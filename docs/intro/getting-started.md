---
sidebar_position: 2
---

# Getting Started

Local installations install Tackle into the Git repository itself. This does a number of things:

1. Installs a wrapper script into the Git repository.
2. Downloads the latest version of Tackle.
3. Sets up the repository to support Tackle.

The tackle wrapper script is used to prevent developers having to push the Tackle binary itself to their repositories.

You can install Tackle locally using the following script:

**On \*NIX:**

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

**On Windows:**

```powershell
. { iwr -useb https://omnitruck.chef.io/install.ps1 } | iex; install
```
