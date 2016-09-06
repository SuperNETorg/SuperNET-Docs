# Glossary

<aside class="notice">This is a technical glossary. This glossary section is stored in a separate file in `includes/_glossary.md`.</aside>

## 51 Percent Attack
<b>51% Attack, Majority Hash Rate Attack</b>

### Definition
The ability of someone controlling a majority of network hash rate to revise transaction history and prevent new transactions from confirming.

### Synonyms

   - 51 percent attack

   - Majority attack

### Links

  - <a href='https://bitcoin.org/en/developer-guide#term-51-attack'>51% attack</a> — Bitcoin.org Developer Guide
  - <a href='http://bitcoin.stackexchange.com/questions/658/what-can-an-attacker-with-51-of-hash-power-do'>What can an attacker with 51% of hash power do?</a> — Bitcoin StackExchange
  - <a href='https://bitcoin.org/en/bitcoin-paper'>Bitcoin.pdf</a> — Satoshi Nakamoto (Bitcoin.org)

## Address
<b>Payment Addresses</b>

### Definition
A 20-byte hash formatted using base58check to produce either a P2PKH or P2SH Bitcoin address. Currently the most common way users exchange payment information.

### Synonyms

   - Address

### Not To Be Confused With

   - IP address

### Links
  - <a href='https://bitcoin.org/en/developer-guide#term-address'>Address</a> — Bitcoin.org Developer Guide
  - <a href='https://en.bitcoin.it/wiki/Address'>Address</a> — Bitcoin Wiki

## Bare- MultiSig
<b>M-of-N Multisig, Multisig Output</b>

### Definition

A pubkey script that provides n number of pubkeys and requires the corresponding signature script provide m minimum number signatures corresponding to the provided pubkeys.

### Synonyms

   - Multisig

   - Bare multisig

### Not To Be Confused With

   - P2SH multisig (a multisig script contained inside P2SH)

   - Advanced scripts that require multiple signatures without using OP_CHECKMULTISIG or OP_CHECKMULTISIGVERIFY

### Links

   - <a href="https://bitcoin.org/en/developer-guide#term-multisig">Multisig</a> — Bitcoin.org Developer Guide

   - <a href="https://github.com/bitcoin/bips/blob/master/bip-0011.mediawiki">BIP11: m-of-n standard transactions</a> — Bitcoin Improvement Proposals

   - <a href="http://bitcoin.stackexchange.com/questions/3718/what-are-multi-signature-transactions">What are multi-signature transactions?</a> — Bitcoin StackExchange

## Base58check
<b>Base58check, Bitcoin Address Encoding</b>
    
### Definition

The method used in Bitcoin for converting 160-bit hashes into P2PKH and P2SH addresses. Also used in other parts of Bitcoin, such as encoding private keys for backup in WIP format. Not the same as other base58 implementations.

### Synonyms

   - Base58check

### Not To Be Confused With

   - P2PKH address

   - P2SH address

   - IP address

### Links

   - <a href='https://bitcoin.org/en/developer-reference#term-base58check'>base58check</a> — Bitcoin.org Developer Reference

   - <a href='https://en.bitcoin.it/wiki/Base58Check_encoding'>Base58Check encoding</a> — Bitcoin Wiki

## Best Block Chain
<b> Block Chain </b>

### Definition

A chain of blocks with each block referencing the block that preceded it. The most-difficult-to-recreate chain is the best block chain.

### Synonyms

- Block chain

- Best block chain

### Not To Be Confused With

- Header chain

### Links

- <a href='https://bitcoin.org/en/developer-guide#block-chain'>Block chain</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Block_chain'>Block chain</a> — Bitcoin Wiki
