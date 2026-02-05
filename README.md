# Bobine is awesome

A curated list on the [Bobine](https://bobine.tech) ecosystem

## Kernel

### Runtimes
- [@hazae41/bobine](https://github.com/hazae41/bobine) / A blockchain in your garage

## Userland

The Bobine VM can run code written in any language that compiles to WebAssembly, but AssemblyScript is the best one so far

### Starters

Module starters help you write modules with the right setup and batteries included

- [@hazae41/create-bobine-module](https://github.com/hazae41/create-bobine-module) / Create and deploy your own Bobine module in AssemblyScript

### Libraries

Libraries are portions of code that are cloned into each module, typically to add syntactic sugar, define common interfaces, or anything helpful

- [@hazae41/stdbob](https://github.com/hazae41/stdbob) / Standard libraries for Bobine WebAssembly VM

### Modules

Modules are portion of code with an address and a storage, and can have their methods referenced externally or by other modules

#### Accounts

There is no built-in concept of accounts in Bobine, you can use any accounting module you want, or create your own

- [@hazae41/ed25519](https://github.com/hazae41/openbob/tree/main/mods/accounts/ed25519) / Ed25519 accounts for Bobine

#### Finance

- [@ccamel/token_fungible](https://github.com/ccamel/bobinerie/blob/main/contracts/token_fungible/README.md) / A minimal fungible token module for Bobine
- [@ccamel/pool-xyk](https://github.com/ccamel/bobinerie/blob/main/contracts/pool-xyk/README.md) / XYK (constant-product) AMM pool for two fungible tokens

#### Playful

- [@ccamel/counter](https://github.com/ccamel/bobinerie/blob/main/contracts/counter/README.md) / Per-account counter with Ed25519 session authentication

- [@ccamel/say-my-name](https://github.com/ccamel/bobinerie/blob/main/contracts/say-my-name/README.md) / A simple name storage contract that remembers who you are

- [@ccamel/sigil](https://github.com/ccamel/bobinerie/blob/main/contracts/sigil/README.md) / Account-bound on-chain sigil (SVG PFP)

Add your own thing via pull request 🫡
