# Wallet.rs Node Binding Tutorial

This tutorial consists of several pieces of code you can run in order to interact
with the IOTA Wallet.rs library through Node.js

For this to work you need to follow the installation instructions for the wallet.rs
node bindings for now on https://github.com/iotaledger/wallet.rs/tree/develop/bindings/node

`npm install` after that

Make sure you generate a 24-word BIP39 mnemonic in your .env file and define a node; see
`.env.example` for a boilerplate. To generate a mnemonic you can utilize the BIP39 standard
for that; We encourage you to generate this offline with trusted tools but if you need a 
quick mnemonic for testing only you can use something like https://github.com/iancoleman/bip39
