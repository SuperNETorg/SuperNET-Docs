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

## Best Header Chain
<b> Header Chain, Best Header Chain </b>

### Definition

A chain of block headers with each header linking to the header that preceded it; the most-difficult-to-recreate chain is the best header chain

### Synonyms

- Header chain

- Best header chain

### Not To Be Confused With
 - Block chain

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-header-chain'>Header chain</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/35448/is-it-chain-of-headers-rather-than-a-chain-of-blocks'>Is it a chain of headers rather than a chain of blocks?</a> — Bitcoin StackExchange

## Bitcoins
<b> Denominations </b>

### Definition

Denominations of Bitcoin value, usually measured in fractions of a bitcoin but sometimes measured in multiples of a satoshi. One bitcoin equals 100,000,000 satoshis.

### Synonyms

- Denomination

- Bitcoins

- Satoshis

### Not To Be Confused With

- Binary bits, a unit of data with two possible values

### Links

- <a href='https://en.bitcoin.it/wiki/Units'>Bitcoin Units</a> — Bitcoin Wiki

## Block
<b> Block, Block Of Transactions </b>

### Definition

One or more transactions prefaced by a block header and protected by proof of work. Blocks are the data stored on the block chain.

### Synonyms

- Block

### Links

- <a href='https://bitcoin.org/en/developer-guide#block-chain-overview'>Block</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Block'>Block</a> — Bitcoin Wiki

## Block 0
<b>Genesis Block, Block 0</b>

### Definition

The first block in the Bitcoin block chain.

### Synonyms

- Genesis block

- Block 0

### Not To Be Confused With

- Generation transaction (the first transaction in a block)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-genesis-block'>Genesis block</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Genesis_block'>Genesis block</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/10009/why-can-t-the-genesis-block-coinbase-be-spent'>Why can’t the genesis block coinbase transaction be spent?</a> — Bitcoin StackExchange 

## Block Chain
<b>Block Chain</b>

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

## Block Header
<b>Block Header</b>

### Definition

An 80-byte header belonging to a single block which is hashed repeatedly to create proof of work.

### Synonyms

- Block header

- Header

### Links

- <a href='https://bitcoin.org/en/developer-reference#block-headers'>Block header</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Block_hashing_algorithm'>Block hashing algorithm</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/8031/what-are-bitcoin-miners-really-solving'>What are Bitcoin miners really solving?</a> — Bitcoin StackExchange

## Block Height
<b>Block Chain Height, Block Height</b>

### Definition

The number of blocks preceding a particular block on a block chain. For example, the genesis block has a height of zero because zero block preceded it.

### Synonyms

- Height

- Block height

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-block-height'>Block height</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/18561/definition-of-blockchain-height'>Definition of block height</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/30764/why-block-height-is-required-in-coinbase'>Why is block height required in the coinbase?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/24309/is-block-height-always-sequential'>Is block height always sequencial?</a> — Bitcoin StackExchange

## Block Reward
<b>Block Reward, Block Miner Reward</b>

### Definition

The amount that miners may claim as a reward for creating a block. Equal to the sum of the block subsidy (newly available satoshis) plus the transactions fees paid by transactions included in the block.

### Synonyms

- Block reward

### Not To Be Confused With

- Block subsidy

- Transaction fees

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-block-reward'>Block reward</a> — Bitcoin.org Developer Reference

## Blocks-First Sync
<b>Blocks-First, Blocks-First Sync</b>

### Definition

Synchronizing the block chain by downloading each block from a peer and then validating it.

### Synonyms

- Blocks-first sync

### Not To Be Confused With

- Headers-first sync

### Links

- <a href='https://bitcoin.org/en/developer-guide#blocks-first'>Blocks-first sync</a> — Bitcoin.org Developer Guide

## Bloom Filter
<b>Bloom Filter</b>

### Definition

A filter used primarily by SPV clients to request only matching transactions and merkle blocks from full nodes.

### Synonyms

- Bloom filter

### Not To Be Confused With

- Bloom filter (general computer science term, of which Bitcoin’s bloom filters are a specific implementation)

### Links

- <a href='https://bitcoin.org/en/developer-guide#bloom-filters'>Bloom filter</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki'>BIP37: Connection Bloom Filtering </a>— Bitcoin Improvement Proposals

- <a href='https://github.com/bitcoin/bitcoin/pull/1795'>Pull request that implemented bloom filters in Bitcoin Core </a> — GitHub

- <a href='https://bitcointalk.org/index.php?topic=252937.0'>Discussion about bloom filtering and SPV clients</a> — BitcoinTalk

## Chain Code
<b>Chain Code, HD Wallet Chain Code</b>

### Definition

In HD wallets, 256 bits of entropy added to the public and private keys to help them generate secure child keys; the master chain code is usually derived from a seed along with the master private key

### Synonyms

- Chain code

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-chain-code'>Chain code</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: Hierarchical Deterministic Wallets</a> — Bitcoin Improvement Proposals

- <a href='https://en.bitcoin.it/wiki/Deterministic_wallet'>Deterministic wallet</a> — Bitcoin wiki

## Change Address 
<b>Change, Change Address, Change Output</b>

### Definition

An output in a transaction which returns satoshis to the spender, thus preventing too much of the input value from going to transaction fees.

### Synonyms

- Change address

- Change output

### Not To Be Confused With

- Address reuse

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-change-output'>Change address</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Change'>Change</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/35412/why-does-bitcoin-use-separate-change-addresses'>Why does Bitcoin Core use separate change addresses?</a> — Bitcoin StackExchange

## Change Output
<b>Change, Change Address, Change Output</b>

### Definition

An output in a transaction which returns satoshis to the spender, thus preventing too much of the input value from going to transaction fees.

### Synonyms

- Change address

- Change output

### Not To Be Confused With

- Address reuse

### Links

- <a href='https://bitcoin.org/en/developer-guide#transaction-fees-and-change'>Change address</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Change'>Change</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/35412/why-does-bitcoin-use-separate-change-addresses'>Why does Bitcoin Core use separate change addresses?</a> — Bitcoin StackExchange

## Child Key
<b>Child Key, HD Wallet Child Key</b>

### Definition

In HD wallets, a key derived from a parent key. The key can be either a private key or a public key, and the key derivation may also require a chain code.

### Synonyms

- Child key

- Child public key

- Child private key

### Not To Be Confused With

- Public key (derived from a private key, not a parent key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-child-public-key'>Child key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: Hierarchical Deterministic Wallets</a> — Bitcoin Improvement Proposals
 
## Child Private Key
<b>Child Key, HD Wallet Child Key</b>

### Definition

In HD wallets, a key derived from a parent key. The key can be either a private key or a public key, and the key derivation may also require a chain code.

### Synonyms

- Child key

- Child public key

- Child private key

### Not To Be Confused With

- Public key (derived from a private key, not a parent key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-child-public-key'>Child key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: Hierarchical Deterministic Wallets</a> — Bitcoin Improvement Proposals

## Child Public Key
<b>Child Key, HD Wallet Child Key</b>

### Definition

In HD wallets, a key derived from a parent key. The key can be either a private key or a public key, and the key derivation may also require a chain code.

### Synonyms

- Child key

- Child public key

- Child private key

### Not To Be Confused With

- Public key (derived from a private key, not a parent key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-child-public-key'>Child key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: Hierarchical Deterministic Wallets</a> — Bitcoin Improvement Proposals

## Coinbase 
<b>Coinbase, Coinbase Field</b>

### Definition

A special field used as the sole input for coinbase transactions. The coinbase allows claiming the block reward and provides up to 100 bytes for arbitrary data.

### Synonyms

- Coinbase

### Not To Be Confused With

- Coinbase transaction

- Coinbase.com

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-coinbase-field'>Coinbase</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Coinbase'>Coinbase</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/4571/what-is-the-coinbase'>What is the coinbase?</a> — Bitcoin StackExchange

## Coinbase Transaction
<b>Coinbase / Generation Transaction</b>

### Definition

The first transaction in a block. Always created by a miner, it includes a single coinbase.

### Synonyms

- Coinbase transaction

- Generation transaction

### Not To Be Confused With

- Coinbase (the unique part of a coinbase transaction)

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-coinbase-tx'>Coinbase transaction</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Transaction#Generation'>Generation transaction</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/32091/who-generates-the-coinbase-transaction'>Who generates the coinbase transaction?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/30349/must-a-block-contain-a-coinbase-transaction'>Must a block contain a coinbase transaction?</a> — Bitcoin StackExchange

## Compact Size
<b>CompactSize Unsigned Integer</b>

### Definition

A type of variable-length integer commonly used in the Bitcoin P2P protocol and Bitcoin serialized data structures.

### Synonyms

- CompactSize

### Not To Be Confused With

- VarInt (a data type Bitcoin Core uses for local data storage)

- Compact (the data type used for nBits in the block header)

### Links

- <a href='https://bitcoin.org/en/developer-reference#compactsize-unsigned-integers'>CompactSize Unsigned Integers</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#Variable_length_integer'>Variable length integers (compactSize)</a> — Bitcoin Wiki

## Compressed Public Key
<b>Compressed Public Key</b>

### Definition

An ECDSA public key that is 33 bytes long rather than the 65 bytes of an uncompressed public key.

### Synonyms

- Compressed public key

### Links

- <a href='https://bitcoin.org/en/developer-guide#public-key-formats'>Public key formats</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/3059/what-is-a-compressed-bitcoin-key'>What is a compressed public key?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/5952/why-does-bitcoin-support-both-compressed-and-uncompressed-keys-addresses'>Why does Bitcoin Core support both compressed and uncompressed keys?</a> — Bitcoin StackExchange

## Confirmation Score
<b>Confirmation Score, Confirmed Transaction</b>

### Definition

A score indicating the number of blocks on the best block chain that would need to be modified to remove or modify a particular transaction. A confirmed transaction has a confirmation score of one or higher.

### Synonyms

- Confirmation score

- Confirmations

- Confirmed transaction

- Unconfirmed transaction

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-confirmation'>Confirmations</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Confirmation'>Confirmation</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/146/what-are-bitcoin-confirmations/160#160'>What are confirmations?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/32562/when-to-worry-about-1-confirmation-payments'>When should I worry about 1-confirmation payments?</a> — Bitcoin StackExchange

## Confirmations
<b>Confirmation Score, Confirmed Transaction</b>

### Definition

A score indicating the number of blocks on the best block chain that would need to be modified to remove or modify a particular transaction. A confirmed transaction has a confirmation score of one or higher.

### Synonyms

- Confirmation score

- Confirmations

- Confirmed transaction

- Unconfirmed transaction

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-confirmation'>Confirmations</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Confirmation'>Confirmation</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/146/what-are-bitcoin-confirmations/160#160'>What are confirmations?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/32562/when-to-worry-about-1-confirmation-payments'>When should I worry about 1-confirmation payments?</a> — Bitcoin StackExchange

## Confirmed Transaction
<b>Confirmation Score, Confirmed Transaction</b>

### Definition

A score indicating the number of blocks on the best block chain that would need to be modified to remove or modify a particular transaction. A confirmed transaction has a confirmation score of one or higher.

### Synonyms

- Confirmation score

- Confirmations

- Confirmed transaction

- Unconfirmed transaction

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-confirmation'>Confirmations</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Confirmation'>Confirmation</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/146/what-are-bitcoin-confirmations/160#160'>What are confirmations?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/32562/when-to-worry-about-1-confirmation-payments'>When should I worry about 1-confirmation payments?</a> — Bitcoin StackExchange

## Consensus
<b>Consensus</b>

### Definition

When several nodes (usually most nodes on the network) all have the same blocks in their locally-validated best block chain.

### Synonyms

- Consensus

### Not To Be Confused With

- Social consensus (often used in discussion among developers to indicate that most people agree with a particular plan)

- Consensus rules (the rules that allow nodes to maintain consensus)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-consensus'>Consensus</a> — Bitcoin.org Developer Guide

## Consensus Rules
<b>Consensus Rules, Validation Rules</b>

### Definition

The block validation rules that full nodes follow to stay in consensus with other nodes.

### Synonyms

- Consensus rules

### Not To Be Confused With

- Consensus (what happens when nodes follow the same consensus rules)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-consensus-rules'>Consensus rules</a> — Bitcoin.org Developer Guide

## Data Carrier Transaction
<b>Null Data (OP_RETURN) Transaction</b>

### Definition

A transaction type relayed and mined by default in Bitcoin Core 0.9.0 and later that adds arbitrary data to a provably unspendable pubkey script that full nodes don’t have to store in their UTXO database.

### Synonyms

- Null data transaction

- OP_RETURN transaction

- Data carrier transaction

### Not To Be Confused With

- OP_RETURN (an opcode used in one of the outputs in an OP_RETURN transaction)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-null-data'>Null data transaction</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bitcoin/pull/2738'>Pull request implement null data transactions</a> — GitHub

## Data-Pushing Opcode
<b>Opcode</b>

### Definition

Operation codes from the Bitcoin Script language which push data or perform functions within a pubkey script or signature script.

### Synonyms

- Opcode

- Data-pushing opcode

- Non-data-pushing opcode

### Links

- <a href='https://bitcoin.org/en/developer-reference#opcodes'>Opcodes</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Script'>List of opcodes</a> — Bitcoin Wiki

## Denomination
<b>Denominations</b>

### Definition

Denominations of Bitcoin value, usually measured in fractions of a bitcoin but sometimes measured in multiples of a satoshi. One bitcoin equals 100,000,000 satoshis.

### Synonyms

- Denomination

- Bitcoins

- Satoshis

### Not To Be Confused With

- Binary bits, a unit of data with two possible values

### Links

- <a href='https://en.bitcoin.it/wiki/Units'>Bitcoin Units</a> — Bitcoin Wiki

## Difficulty
<b>Difficulty, Network Difficulty</b>

### Definition

How difficult it is to find a block relative to the difficulty of finding the easiest possible block. The easiest possible block has a proof-of-work difficulty of 1.

### Synonyms

- Difficulty

- Network difficulty

### Not To Be Confused With

- Target threshold (the value from which difficulty is calculated)

### Links

- <a href='https://bitcoin.org/en/developer-guide#proof-of-work'>Difficulty</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Difficulty'>Difficulty</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/5838/how-is-difficulty-calculated'>How is difficulty calculated?</a> — Bitcoin StackExchange

## DNS Seed
<b>DNS Seed</b>

### Definition

A DNS server which returns IP addresses of full nodes on the Bitcoin network to assist in peer discovery.

### Synonyms

- DNS seed

### Not To Be Confused With

- HD wallet seeds

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-dns-seed'>DNS seed</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Satoshi_Client_Node_Discovery#DNS_Addresses'>DNS seeds</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/14371/what-is-a-dns-seed-node-vs-a-seed-node'>What is a DNS seed versus a seed node?</a> — Bitcoin StackExchange

## Double Spend
<b>Double Spend</b>
### Definition

A transaction that spends the same input as spent in another transaction.

### Synonyms

- Double spend

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-double-spend'>Double spend</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Double-spending'>Double spending</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/4974/what-is-a-double-spend'>What is a double spend?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/13370/how-do-i-detect-a-double-spend'>How do I detect a double spend?</a> — Bitcoin StackExchange

## Escrow Contract
<b>Escrow Contract</b>

### Definition

A transaction in which a spender and receiver place funds in a 2-of-2 (or other m-of-n) multisig output so that neither can spend the funds until they’re both satisfied with some external outcome.

### Synonyms

- Escrow contract

### Links

- <a href='https://bitcoin.org/en/developer-guide#escrow-and-arbitration'>Escrow contract</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Contract#Example_2:_Escrow_and_dispute_mediation'>Escrow and dispute mediation</a> — Bitcoin Wiki

## Extended Key
<b>Extended Key, HD Wallet Extended Key</b>

### Definition

In the context of HD wallets, a public key or private key extended with the chain code to allow them to derive child keys.

### Synonyms

- Extended key

- Public extended key

- Private extended key

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-extended-key'>Extended key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## Fork
<b>Fork, Accidental Fork</b>

### Definition

When two or more blocks have the same block height, forking the block chain. Typically occurs when two or more miners find blocks at nearly the same time. Can also happen as part of an attack.

### Synonyms

- Fork

### Not To Be Confused With

- Hard fork (a change in consensus rules that breaks security for nodes that don’t upgrade)

- Soft fork (a change in consensus rules that weakens security for nodes that don’t upgrade)

- Software fork (when one or more developers permanently develops a codebase separately from other developers)

- Git fork (when one or more developers temporarily develops a codebase separately from other developers)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-fork'>Fork</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/3343/what-is-the-longest-blockchain-fork-that-has-been-orphaned-to-date'>What is the longest block chain fork that has been made stale so far?</a> — Bitcoin StackExchange

## Free Transaction
<b>High-Priority Transaction, Free Tx</b>

### Definition

Transactions that don’t have to pay a transaction fee because their inputs have been idle long enough to accumulated large amounts of priority. Note: miners choose whether to accept free transactions.

### Synonyms

- High-priority transaction

- Free transaction

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-high-priority-transactions'>High-priority transactions</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Free_transaction_relay_policy'>Free transaction relay policy</a> — Bitcoin Wiki

## Generation Transaction
<b>Coinbase / Generation Transaction</b>

### Definition

The first transaction in a block. Always created by a miner, it includes a single coinbase.

### Synonyms

- Coinbase transaction

- Generation transaction

### Not To Be Confused With

- Coinbase (the unique part of a coinbase transaction)

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-coinbase-tx'>Coinbase transaction</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Transaction#Generation'>Generation transaction</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/32091/who-generates-the-coinbase-transaction'>Who generates the coinbase transaction?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/30349/must-a-block-contain-a-coinbase-transaction'>Must a block contain a coinbase transaction?</a> — Bitcoin StackExchange

## Genesis Block
<b>Genesis Block, Block 0</b>

### Definition

The first block in the Bitcoin block chain.

### Synonyms

- Genesis block

- Block 0

### Not To Be Confused With

- Generation transaction (the first transaction in a block)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-genesis-block'>Genesis block</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Genesis_block'>Genesis block</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/10009/why-can-t-the-genesis-block-coinbase-be-spent'>Why can’t the genesis block coinbase transaction be spent?</a> — Bitcoin StackExchange

## Hard Fork
<b>Hard Fork, Hard-Forking Change</b>

### Definition

A permanent divergence in the the block chain, commonly occurs when non-upgraded nodes can’t validate blocks created by upgraded nodes that follow newer consensus rules.

### Synonyms

- Hard fork

### Not To Be Confused With

- Fork (a regular fork where all nodes follow the same consensus rules, so the fork is resolved once one chain has more proof of work than another)

- Soft fork (a temporary divergence in the block chain caused by non-upgraded nodes not following new consensus rules)

- Software fork (when one or more developers permanently develops a codebase separately from other developers)

- Git fork (when one or more developers temporarily develops a codebase separately from other developers

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-hard-fork'>Hard fork</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Hardfork'>Hard fork</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/36090/has-a-hard-fork-ever-occurred'>Has a hard fork ever occurred?</a> — Bitcoin StackExchange

## Hardened Extended Key
<b>Hardened Extended Key (HD Wallets)</b>

### Definition

A variation on HD wallet extended keys where only the hardened extended private key can derive child keys. This prevents compromise of the chain code plus any private key from putting the whole wallet at risk.

### Synonyms

- Hardened extended key

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-hardened-extended-private-key'>Hardened extended private keys</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## HD Protocol
<b>HD Protocol, HD Wallet, BIP32</b>

### Definition

The Hierarchical Deterministic (HD) key creation and transfer protocol (BIP32), which allows creating child keys from parent keys in a hierarchy. Wallets using the HD protocol are called HD wallets.

### Synonyms

- HD protocol

- HD wallet

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-hd-protocol'>HD Protocol</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

- <a href='https://en.bitcoin.it/wiki/Deterministic_wallet'>Deterministic wallet</a> — Bitcoin Wiki

## HD Wallet
<b>HD Protocol, HD Wallet, BIP32</b>

### Definition

The Hierarchical Deterministic (HD) key creation and transfer protocol (BIP32), which allows creating child keys from parent keys in a hierarchy. Wallets using the HD protocol are called HD wallets.

### Synonyms

- HD protocol

- HD wallet

### Links

- <a href='https://bitcoin.org/en/developer-guide#hierarchical-deterministic-key-creation'>HD Protocol</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

- <a href='https://en.bitcoin.it/wiki/Deterministic_Wallet'>Deterministic wallet</a> — Bitcoin Wiki

## HD Wallet
<b>HD Wallet Seed, Root Seed</b>

### Definition

A potentially-short value used as a seed to generate the master private key and master chain code for an HD wallet.

### Synonyms

- HD wallet seed

- Root seed

### Not To Be Confused With

- Mnemonic code / mnemonic seed (a binary root seed formatted as words to make it easier for humans to transcribe and possibly remember)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-root-seed'>Root seed</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki'>BIP39: mnemonic code for generating deterministic keys</a> — Bitcoin Improvement Proposals

## Header
<b>Block Header</b>

### Definition

An 80-byte header belonging to a single block which is hashed repeatedly to create proof of work.

### Synonyms

- Block header

- Header

### Links

- <a href='https://bitcoin.org/en/developer-reference#block-headers'>Block header</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Block_hashing_algorithm'>Block hashing algorithm</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/8031/what-are-bitcoin-miners-really-solving'>What are Bitcoin miners really solving?</a> — Bitcoin StackExchange

## Header Chain
<b>Header Chain, Best Header Chain</b>

### Definition

A chain of block headers with each header linking to the header that preceded it; the most-difficult-to-recreate chain is the best header chain

### Synonyms

- Header chain

- Best header chain

### Not To Be Confused With

- Block chain

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-header-chain'>Header chain</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/35448/is-it-chain-of-headers-rather-than-a-chain-of-blocks'>Is it a chain of headers rather than a chain of blocks?</a> — Bitcoin StackExchange

## Headers-First Sync
<b>Headers-First, Headers-First Sync</b>

### Definition

Synchronizing the block chain by downloading block headers before downloading the full blocks.

### Synonyms

- Headers-first sync

### Not To Be Confused With

- Blocks-first sync (Downloading entire blocks immediately without first getting their headers)

### Links

- <a href='https://bitcoin.org/en/developer-guide#headers-first'>Headers-first sync</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bitcoin/pull/4468'>Pull request adding headers-first sync to Bitcoin Core</a> — GitHub

## Height
<b>Block Chain Height, Block Height</b>

### Definition

The number of blocks preceding a particular block on a block chain. For example, the genesis block has a height of zero because zero block preceded it.

### Synonyms

- Height

- Block height

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-block-height'>Block height</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/18561/definition-of-blockchain-height'>Definition of block height</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/30764/why-block-height-is-required-in-coinbase'>Why is block height required in the coinbase?</a> — Bitcoin StackExchange

- <a href='http://bitcoin.stackexchange.com/questions/24309/is-block-height-always-sequential'>Is block height always sequencial?</a> — Bitcoin StackExchange

## High-Priority Transaction
<b>High-Priority Transaction, Free Tx</b>

### Definition

Transactions that don’t have to pay a transaction fee because their inputs have been idle long enough to accumulated large amounts of priority. Note: miners choose whether to accept free transactions.

### Synonyms

- High-priority transaction

- Free transaction

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-high-priority-transactions'>High-priority transactions</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Free_transaction_relay_policy'>Free transaction relay policy</a> — Bitcoin Wiki

## IBD
<b>Initial Block Download, IBD</b>

### Definition

The process used by a new node (or long-offline node) to download a large number of blocks to catch up to the tip of the best block chain.

### Synonyms

- Initial block download

- IBD

### Not To Be Confused With

- Blocks-first sync (syncing includes getting any amount of blocks; IBD is only used for large numbers of blocks)

### Links

- <a href='https://bitcoin.org/en/developer-guide#initial-block-download'>Initial block download</a> — Bitcoin.org Developer Guide

## Initial Block Download
<b>Initial Block Download, IBD</b>

### Definition

The process used by a new node (or long-offline node) to download a large number of blocks to catch up to the tip of the best block chain.

### Synonyms

- Initial block download

- IBD

### Not To Be Confused With

- Blocks-first sync (syncing includes getting any amount of blocks; IBD is only used for large numbers of blocks)

### Links

- <a href='https://bitcoin.org/en/developer-guide#initial-block-download'>Initial block download</a> — Bitcoin.org Developer Guide

## Input
<b>Input, Transaction Input, TxIn</b>

### Definition

An input in a transaction which contains four fields: an outpoint, a signature script, and a sequence number. The outpoint references a previous output and the signature script allows spending it.

### Synonyms

- Input

- TxIn

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-input'>Input</a> — Bitcoin.org Developer Guide

- <a href='https://bitcoin.org/en/developer-reference#txin'>TxIn</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Transaction#Input'>Inputs</a> — Bitcoin Wiki

## Internal Byte Order
<b>Internal Byte Order</b>

### Definition

The standard order in which hash digests are displayed as strings—the same format used in serialized blocks and transactions.

### Synonyms

- Internal byte order

### Not To Be Confused With

- RPC byte order (where the byte order is reversed)

### Links

- <a href='https://bitcoin.org/en/developer-reference#hash-byte-order'>Internal byte order</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Block_hashing_algorithm'>Block hashing algorithm (‘endian conversion’)</a> — Bitcoin Wiki

## Inventory
<b>Inventory, Block Or Transaction Inventory</b>

### Definition

A data type identifier and a hash; used to identify transactions and blocks available for download through the Bitcoin P2P network.

### Synonyms

- Inventory

### Not To Be Confused With

- Inv message (one of the P2P messages that transmits inventories)

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-inventory'>Inventory</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#Inventory_Vectors'>Inventory vectors</a> — Bitcoin Wiki

## Lightweight Client
<b>SPV, Simplified Payment Verification</b>

### Definition

A method for verifying particular transactions were included in a block without downloading the entire block. The method is used by some lightweight Bitcoin clients.

### Synonyms

- SPV

- Simplified Payment Verification

- Lightweight client

- Thin client

### Links

- <a href='https://bitcoin.org/en/developer-guide#simplified-payment-verification-spv'>SPV</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Thin_Client_Security'>Thin client security</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/32529/what-is-a-thin-client'>What is a thin client?</a> — Bitcoin StackExchange

## Locktime
<b>Locktime, nLockTime</b>

### Definition

Part of a transaction which indicates the earliest time or earliest block when that transaction may be added to the block chain.

### Synonyms

- Locktime

- nLockTime

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-locktime'>Locktime</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/NLockTime'>nLockTime</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/5914/how-is-locktime-enforced-in-the-standard-client'>How is locktime enforced in Bitcoin Core?</a> — Bitcoin StackExchange

## Mainnet
<b>Mainnet, Bitcoin Main Network</b>

### Definition

The original and main network for Bitcoin transactions, where satoshis have real economic value.

### Synonyms

- Mainnet

### Not To Be Confused With

- Testnet (an open network very similar to mainnet where satoshis have no value)

- Regtest (a private testing node similar to testnet)

### Links

- <a href='https://bitcoin.org/en/developer-examples#term-mainnet'>Mainnet</a> — Bitcoin.org Developer Examples

## Majority Attack
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
  
## Master Chain Code
<b>Master Chain Code And Private Key</b>

### Definition

In HD wallets, the master chain code and master private key are the two pieces of data derived from the root seed.

### Synonyms

- Master chain code

- Master private key

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-master-chain-code'>Master chain code</a> — Bitcoin.org Developer Guide

- <a href='https://bitcoin.org/en/developer-guide#hierarchical-deterministic-key-creation'>Master private key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## Master Private Key
<b>Master Chain Code And Private Key</b>

### Definition

In HD wallets, the master chain code and master private key are the two pieces of data derived from the root seed.

### Synonyms

- Master chain code

- Master private key

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-master-chain-code'>Master chain code</a> — Bitcoin.org Developer Guide

- <a href='https://bitcoin.org/en/developer-guide#hierarchical-deterministic-key-creation'>Master private key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals
 
## Merkle Block
<b>Merkle Block</b>

### Definition

A partial merkle tree connecting transactions matching a bloom filter to the merkle root of a block.

### Synonyms

- Merkle block

### Not To Be Confused With

- MerkleBlock message (a P2P protocol message that transmits a merkle block)

### Links

- <a href='https://bitcoin.org/en/developer-reference#merkleblock'>Merkle block</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#filterload.2C_filteradd.2C_filterclear.2C_merkleblock'>MerkleBlock P2P protocol message</a> — Bitcoin Wiki

## Merkle Root
<b>Merkle Root</b>

### Definition

The root node of a merkle tree, a descendant of all the hashed pairs in the tree. Block headers must include a valid merkle root descended from all transactions in that block.

### Synonyms

- Merkle root

### Not To Be Confused With

- Merkle tree (the tree of which the merkle root is the root node)

- Merkle block (a partial merkle branch connecting the root to one or more leaves transactions)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-merkle-root'>Merkle root</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#Merkle_Trees'>Merkle trees</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/10479/what-is-the-merkle-root'>What is the merkle root?</a> — Bitcoin StackExchange

- <a href='https://en.wikipedia.org/wiki/Merkle_tree'>Merkle tree</a> — Wikipedia

## Merkle Tree
<b>Merkle Tree</b>

### Definition

A tree constructed by hashing paired data (the leaves), then pairing and hashing the results until a single hash remains, the merkle root. In Bitcoin, the leaves are almost always transactions from a single block.

### Synonyms

- Merkle tree

### Not To Be Confused With

- Partial merkle branch (a branch connecting one or more leaves to the root)

- Merkle block (a partial merkle branch connecting one or more transactions from a single block to the block merkle root)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-merkle-tree'>Merkle tree</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#Merkle_Trees'>Merkle trees</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/1110/how-do-i-implement-a-merkle-tree'>How do I implement a merkle tree?</a> — Bitcoin StackExchange

- <a href='https://en.wikipedia.org/wiki/Merkle_tree'>Merkle tree</a> — Wikipedia

## Message Header
<b>Message Header</b>

### Definition

The four header fields prefixed to all messages on the Bitcoin P2P network.

### Synonyms

- Message header

### Links

- <a href='https://bitcoin.org/en/developer-reference#message-headers'>Message headers</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#Message_structure'>Message structure</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/22882/what-is-the-function-of-the-payload-checksum-field-in-the-bitcoin-protocol'>What is the function of the payload checksum in message headers?</a> — Bitcoin StackExchange

## Miner
<b>Mining, Miner</b>

### Definition

Mining is the act of creating valid Bitcoin blocks, which requires demonstrating proof of work, and miners are devices that mine or people who own those devices.

### Synonyms

- Mining

- Miner

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-miner'>Mining</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Mining'>Mining</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/148/what-exactly-is-mining'>What exactly is mining?</a> — Bitcoin StackExchange

## Miners Fee
<b>Transaction Fee, Miner Fee</b>

### Definition

The amount remaining when the value of all outputs in a transaction are subtracted from all inputs in a transaction; the fee is paid to the miner who includes that transaction in a block.

### Synonyms

- Transaction fee

- Miners fee

### Not To Be Confused With

- Minimum relay fee (the lowest fee a transaction must pay to be accepted into the memory pool and relayed by Bitcoin Core nodes)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-transaction-fee'>Transaction fee</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Transaction_fees'>Transaction fees</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/1195/how-to-calculate-transaction-size-before-sending'>How to calculate transaction fees before sending?</a> — Bitcoin StackExchange

## Minimum Relay Fee
<b>Minimum Relay Fee</b>

### Definition

The minimum transaction fee a transaction must pay (if it isn’t a high-priority transaction) for a full node to relay that transaction to other nodes. There is no one minimum relay fee—each node chooses its own policy.

### Synonyms

- Minimum relay fee

- Relay fee

### Not To Be Confused With

- Transaction fee (the minimum relay fee is a policy setting that filters out transactions with too-low transaction fees)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-minimum-fee'>Minimum relay fee</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Transaction_fees'>Transaction fees</a> — Bitcoin Wiki

## Mining
<b>Mining, Miner</b>

### Definition

Mining is the act of creating valid Bitcoin blocks, which requires demonstrating proof of work, and miners are devices that mine or people who own those devices.

### Synonyms

- Mining

- Miner

### Links

- <a href='https://bitcoin.org/en/developer-guide#block-chain-overview'>Mining</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Mining'>Mining</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/148/what-exactly-is-mining'>What exactly is mining?</a> — Bitcoin StackExchange

## Multisig
<b> M-of-N Multisig, Multisig Output M-of-N Multisig, Multisig Output </b>

### Definition

A pubkey script that provides n number of pubkeys and requires the corresponding signature script provide m minimum number signatures corresponding to the provided pubkeys.

### Synonyms

- Multisig

- Bare multisig

### Not To Be Confused With

- P2SH multisig (a multisig script contained inside P2SH)

- Advanced scripts that require multiple signatures without using OP_CHECKMULTISIG or OP_CHECKMULTISIGVERIFY

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-multisig'>Multisig</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0011.mediawiki'>BIP11: m-of-n standard transactions</a> — Bitcoin Improvement Proposals

- <a href='http://bitcoin.stackexchange.com/questions/3718/what-are-multi-signature-transactions'>What are multi-signature transactions?</a> — Bitcoin StackExchange

## NBits
<b>nBits, Target Threshold </b>

### Definition

The target is the threshold below which a block header hash must be in order for the block to valid, and nBits is the encoded form of the target threshold as it appears in the block header.

### Synonyms

- nBits

- Target

### Not To Be Confused With

- Difficulty (a number measuring the difficulty of finding a header hash relative to the difficulty of finding a header hash with the easiest target)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-target'>Target</a> — Bitcoin.org Developer Guide

- <a href='https://bitcoin.org/en/developer-reference#target-nbits'>nBits</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Target'>Target</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/23912/how-is-the-target-section-of-a-block-header-calculated'>How is the target section of the block header calculated?</a> — Bitcoin StackExchange

## Network Difficulty
<b>Difficulty, Network Difficulty </b>

### Definition

How difficult it is to find a block relative to the difficulty of finding the easiest possible block. The easiest possible block has a proof-of-work difficulty of 1.

### Synonyms

- Difficulty

- Network difficulty

### Not To Be Confused With

- Target threshold (the value from which difficulty is calculated)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-difficulty'>Difficulty</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Difficulty'>Difficulty</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/5838/how-is-difficulty-calculated'>How is difficulty calculated?</a> — Bitcoin StackExchange

## Network Magic
<b>Start String, Network Magic</b>

### Definition

Four defined bytes which start every message in the Bitcoin P2P protocol to allow seeking to the next message.

### Synonyms

- Start string

- Network magic

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-start-string'>Start string</a> — Bitcoin.org Developer Reference

- <a href='http://bitcoin.stackexchange.com/questions/2337/how-was-the-magic-network-id-value-chosen'>How was the start string chosen?</a> — Bitcoin StackExchange

## NLockTime
<b>Locktime, nLockTime</b>

### Definition

Part of a transaction which indicates the earliest time or earliest block when that transaction may be added to the block chain.

### Synonyms

- Locktime

- nLockTime

### Links

- <a href='https://bitcoin.org/en/developer-guide#locktime-and-sequence-number'>Locktime</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/NLockTime'>nLockTime</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/5914/how-is-locktime-enforced-in-the-standard-client'>How is locktime enforced in Bitcoin Core?</a> — Bitcoin StackExchange

## Non-data-pushing opcode
<b>Opcode</b>

### Definition

Operation codes from the Bitcoin Script language which push data or perform functions within a pubkey script or signature script.

### Synonyms

- Opcode

- Data-pushing opcode

- Non-data-pushing opcode

### Links

- <a href='https://bitcoin.org/en/developer-reference#opcodes'>Opcodes</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Script'>List of opcodes</a> — Bitcoin Wiki

## Null Data Transaction
<b>Null Data (OP_RETURN) Transaction</b>

### Definition

A transaction type relayed and mined by default in Bitcoin Core 0.9.0 and later that adds arbitrary data to a provably unspendable pubkey script that full nodes don’t have to store in their UTXO database.

### Synonyms

- Null data transaction

- OP_RETURN transaction

- Data carrier transaction

### Not To Be Confused With

- OP_RETURN (an opcode used in one of the outputs in an OP_RETURN transaction)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-null-data'>Null data transaction</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bitcoin/pull/2738'>Pull request implement null data transactions</a> — GitHub

## OP_RETURN transaction
<b>Null Data (OP_RETURN) Transaction</b>

### Definition

A transaction type relayed and mined by default in Bitcoin Core 0.9.0 and later that adds arbitrary data to a provably unspendable pubkey script that full nodes don’t have to store in their UTXO database.

### Synonyms

- Null data transaction

- OP_RETURN transaction

- Data carrier transaction

### Not To Be Confused With

- OP_RETURN (an opcode used in one of the outputs in an OP_RETURN transaction)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-null-data'>Null data transaction</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bitcoin/pull/2738'>Pull request implement null data transactions</a> — GitHub

## Opcode
<b>Opcode</b>

### Definition

Operation codes from the Bitcoin Script language which push data or perform functions within a pubkey script or signature script.

### Synonyms

- Opcode

- Data-pushing opcode

- Non-data-pushing opcode

### Links

- <a href='https://bitcoin.org/en/developer-reference#opcodes'>Opcodes</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Script'>List of opcodes</a> — Bitcoin Wiki

## Orphan Block
<b>Orphan Block</b>

### Definition

Blocks whose parent block has not been processed by the local node, so they can’t be fully validated yet.

### Synonyms

- Orphan block

### Not To Be Confused With

- Stale block

### Links

- <a href='https://bitcoin.org/en/developer-guide#orphan-blocks'>Orphan blocks</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/5859/what-are-orphaned-and-stale-blocks'>What are orphaned and stale blocks?</a> — Bitcoin StackExchange

## Outpoint
<b>Outpoint</b>

### Definition

The data structure used to refer to a particular transaction output, consisting of a 32-byte TXID and a 4-byte output index number (vout).

### Synonyms

- Outpoint

### Not To Be Confused With

- Output (an entire output from a transaction)

- TxOut (same as output)

### Links

- <a href='https://bitcoin.org/en/developer-reference#outpoint'>Outpoint</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#tx'>Tx message (includes outpoint description)</a> — Bitcoin Wiki

## Output
<b>Output, Transaction Output, TxOut</b>

### Definition

An output in a transaction which contains two fields: a value field for transferring zero or more satoshis and a pubkey script for indicating what conditions must be fulfilled for those satoshis to be further spent.

### Synonyms

- Output

- TxOut

### Not To Be Confused With

- Outpoint (a reference to a particular output)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-output'>Output</a> — Bitcoin.org Developer Guide

- <a href='https://bitcoin.org/en/developer-reference#raw-transaction-format'>TxOut</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Transaction#Output'>Output</a> — Bitcoin Wiki

## P2PKH Address
<b>P2PKH Address, Pay To PubKey Hash</b>

### Definition

A Bitcoin payment address comprising a hashed public key, allowing the spender to create a standard pubkey script that Pays To PubKey Hash (P2PKH).

### Synonyms

- P2PKH address

- P2PKH output

### Not To Be Confused With

- P2PK output (an output paying a public key directly)

- P2SH address, P2SH output (an address comprising a hashed script, and its corresponding output)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-p2pkh'>P2PKH</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/32639/why-does-the-default-miner-implementation-use-pay-to-pubkey/32642#32642'>P2PKH versus P2PK</a> — Bitcoin StackExchange

## P2PKH Output
<b>P2PKH Address, Pay To PubKey Hash</b>

### Definition

A Bitcoin payment address comprising a hashed public key, allowing the spender to create a standard pubkey script that Pays To PubKey Hash (P2PKH).

### Synonyms

- P2PKH address

- P2PKH output

### Not To Be Confused With

- P2PK output (an output paying a public key directly)

- P2SH address, P2SH output (an address comprising a hashed script, and its corresponding output)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-p2pkh'>P2PKH</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/32639/why-does-the-default-miner-implementation-use-pay-to-pubkey/32642#32642'>P2PKH versus P2PK</a> — Bitcoin StackExchange

## P2SH Address
<b>P2SH Address, Pay To Script Hash</b>

### Definition

A Bitcoin payment address comprising a hashed script, allowing the spender to create a standard pubkey script that Pays To Script Hash (P2SH). The script can be almost any valid pubkey script.

### Synonyms

- P2SH address

- P2SH output

### Not To Be Confused With

- P2PK output (an output paying a public key directly)

- P2PKH address, P2PKH output (an address comprising a hashed pubkey, and its corresponding output)

- P2SH multisig (a particular instance of P2SH where the script uses a multisig opcode)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-p2sh'>P2SH</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0016.mediawiki'>BIP16: pay to script hash</a> — Bitcoin Improvement Proposals

- <a href='https://en.bitcoin.it/wiki/Pay_to_script_hash'>P2SH</a> — Bitcoin Wiki

## P2SH Multisig
<b>P2SH Multisig, P2SH Multisig Output</b>

### Definition

A P2SH output where the redeem script uses one of the multisig opcodes. Up until Bitcoin Core 0.10.0, P2SH multisig scripts were standard transactions, but most other P2SH scripts were not.

### Synonyms

- P2SH multisig

### Not To Be Confused With

- Multisig pubkey scripts (also called “bare multisig”, these multisig scripts don’t use P2SH encapsulation)

- P2SH (general P2SH, of which P2SH multisig is a specific instance that was special cased up until Bitcoin Core 0.10.0)

### Links

- <a href='https://bitcoin.org/en/developer-guide#escrow-and-arbitration'>P2SH multisig</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0016.mediawiki'>BIP16: pay to script hash</a> — Bitcoin Improvement Proposals

- <a href='http://bitcoin.stackexchange.com/questions/23893/what-are-the-limits-of-m-and-n-in-m-of-n-multisig-addresses'>What are the limits of bare multisig and P2SH multisig?</a> — Bitcoin StackExchange

## P2SH Output
<b>P2SH Address, Pay To Script Hash</b>

### Definition

A Bitcoin payment address comprising a hashed script, allowing the spender to create a standard pubkey script that Pays To Script Hash (P2SH). The script can be almost any valid pubkey script.

### Synonyms

- P2SH address

- P2SH output

### Not To Be Confused With

- P2PK output (an output paying a public key directly)

- P2PKH address, P2PKH output (an address comprising a hashed pubkey, and its corresponding output)

- P2SH multisig (a particular instance of P2SH where the script uses a multisig opcode)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-p2sh'>P2SH</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0016.mediawiki'>BIP16: pay to script hash</a> — Bitcoin Improvement Proposals

- <a href='https://en.bitcoin.it/wiki/Pay_to_script_hash'>P2SH</a> — Bitcoin Wiki

## Parent Key
<b>Parent Key, HD Wallet Parent Key</b>

### Definition

In HD wallets, a key used to derive child keys. The key can be either a private key or a public key, and the key derivation may also require a chain code.

### Synonyms

- Parent key

- Parent public key

- Parent private key

### Not To Be Confused With

- Public key (derived from a private key, not a parent key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-parent-key'>Parent key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## Parent Private Key
<b>Parent Key, HD Wallet Parent Key</b>

### Definition

In HD wallets, a key used to derive child keys. The key can be either a private key or a public key, and the key derivation may also require a chain code.

### Synonyms

- Parent key

- Parent public key

- Parent private key

### Not To Be Confused With

- Public key (derived from a private key, not a parent key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-parent-key'>Parent key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## Parent Public Key
<b>Parent Key, HD Wallet Parent Key</b>

### Definition

In HD wallets, a key used to derive child keys. The key can be either a private key or a public key, and the key derivation may also require a chain code.

### Synonyms

- Parent key

- Parent public key

- Parent private key

### Not To Be Confused With

- Public key (derived from a private key, not a parent key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#hierarchical-deterministic-key-creation'>Parent key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## Payment Protocol
<b>Payment Protocol, Payment Request, BIP70</b>

### Definition

The protocol defined in BIP70 (and other BIPs) which lets spenders get signed payment details from receivers.

### Synonyms

- Payment protocol

- Payment request

### Not To Be Confused With

- IP-to-IP payment protocol (an insecure, discontinued protocol included in early versions of Bitcoin)

### Links

- <a href='https://bitcoin.org/en/developer-guide#payment-protocol'>Payment Protocol</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki'>BIP70: payment protocol</a> — Bitcoin Improvement Proposals

## Payment Request
<b>Payment Protocol, Payment Request, BIP70</b>

### Definition

The protocol defined in BIP70 (and other BIPs) which lets spenders get signed payment details from receivers.

### Synonyms

- Payment protocol

- Payment request

### Not To Be Confused With

- IP-to-IP payment protocol (an insecure, discontinued protocol included in early versions of Bitcoin)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-payment-protocol'>Payment Protocol</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki'>BIP70: payment protocol</a> — Bitcoin Improvement Proposals

## POW
<b>Proof Of Work</b>

### Definition

A hash below a target value which can only be obtained, on average, by performing a certain amount of brute force work—therefore demonstrating proof of work.

### Synonyms

- Proof of work

- POW

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-proof-of-work'>Proof of work</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Proof_of_work'>Proof of work</a> — Bitcoin Wiki

## Private Extended Key
<b>Extended Key, HD Wallet Extended Key</b>

### Definition

In the context of HD wallets, a public key or private key extended with the chain code to allow them to derive child keys.

### Synonyms

- Extended key

- Public extended key

- Private extended key

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-extended-key'>Extended key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## Private Key
<b>Private Key, ECDSA Private Key</b>

### Definition

The private portion of a keypair which can create signatures that other people can verify using the public key.

### Synonyms

- Private key

### Not To Be Confused With

- Public key (data derived from the private key)

- Parent key (a key used to create child keys, not necessarily a private key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-private-key'>Private key</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Private_key'>Private key</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/4675/what-is-a-private-key-and-a-public-key'>What is a private key?</a> — Bitcoin StackExchange

## Proof Of Work
<b>Proof Of Work</b>

### Definition

A hash below a target value which can only be obtained, on average, by performing a certain amount of brute force work—therefore demonstrating proof of work.

### Synonyms

- Proof of work

- POW

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-proof-of-work'>Proof of work</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Proof_of_work'>Proof of work</a> — Bitcoin Wiki

## Pubkey Script
<b>Pubkey Script, ScriptPubKey</b>

### Definition

A script included in outputs which sets the conditions that must be fulfilled for those satoshis to be spent. Data for fulfilling the conditions can be provided in a signature script. Pubkey Scripts are called a scriptPubKey in code.

### Synonyms

- Pubkey script

- ScriptPubKey

### Not To Be Confused With

- Pubkey (a public key, which can be used as part of a pubkey script but don’t provide a programmable authentication mechanism)

- Signature script (a script that provides data to the pubkey script)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-pubkey-script'>Pubkey script</a> — Bitcoin.org Developer Guide

## Public Extended Key
<b>Extended Key, HD Wallet Extended Key</b>

### Definition

In the context of HD wallets, a public key or private key extended with the chain code to allow them to derive child keys.

### Synonyms

- Extended key

- Public extended key

- Private extended key

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-extended-key'>Extended key</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

## Public Key
<b>Public Key, ECDSA Public Key</b>

### Definition

The public portion of a keypair which can be used to verify signatures made with the private portion of the keypair.

### Synonyms

- Public key

### Not To Be Confused With

- Private key (data from which the public key is derived)

- Parent key (a key used to create child keys, not necessarily a public key)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-public-key'>Public key</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/4675/what-is-a-private-key-and-a-public-key'>What is a public key?</a> — Bitcoin StackExchange

## Raw Transaction
<b>Serialized Transaction, Raw Transaction</b>

### Definition

Complete transactions in their binary format; often represented using hexadecimal. Sometimes called raw format because of the various Bitcoin Core commands with “raw” in their names.

### Synonyms

- Serialized transaction

- Raw transaction

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-raw-format'>Serialized transactions</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#tx'>Tx message (serialized transaction)</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Transaction'>Transaction</a> — Bitconi Wiki

## Redeem Script
<b>Redeem Script, RedeemScript</b>

### Definition

A script similar in function to a pubkey script. One copy of it is hashed to create a P2SH address (used in an actual pubkey script) and another copy is placed in the spending signature script to enforce its conditions.

### Synonyms

- Redeem script

- RedeemScript

### Not To Be Confused With

- Signature script (a script that provides data to the pubkey script, which includes the redeem script in a P2SH input)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-redeem-script'>Redeem script</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0016.mediawiki'>BIP16: pay to script hash</a> — Bitcoin Improvement Proposals

## RedeemScript
<b>Redeem Script, RedeemScript</b>

### Definition

A script similar in function to a pubkey script. One copy of it is hashed to create a P2SH address (used in an actual pubkey script) and another copy is placed in the spending signature script to enforce its conditions.

### Synonyms

- Redeem script

- RedeemScript

### Not To Be Confused With

- Signature script (a script that provides data to the pubkey script, which includes the redeem script in a P2SH input)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-redeem-script'>Redeem script</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0016.mediawiki'>BIP16: pay to script hash</a> — Bitcoin Improvement Proposals

## Regression Test Mode
<b>Regtest, Regression Test Mode</b>

### Definition

A local testing environment in which developers can almost instantly generate blocks on demand for testing events, and can create private satoshis with no real-world value.

### Synonyms

- Regtest

- Regression test mode

### Not To Be Confused With

- Testnet (a global testing environment which mostly mimics mainnet)

### Links

- <a href='https://bitcoin.org/en/developer-examples#regtest-mode'>Regtest mode</a> — Bitcoin.org Developer Examples

## Regtest
<b>Regtest, Regression Test Mode</b>

### Definition

A local testing environment in which developers can almost instantly generate blocks on demand for testing events, and can create private satoshis with no real-world value.

### Synonyms

- Regtest

- Regression test mode

### Not To Be Confused With

- Testnet (a global testing environment which mostly mimics mainnet)

### Links

- <a href='https://bitcoin.org/en/developer-examples#regtest-mode'>Regtest mode</a> — Bitcoin.org Developer Examples

## Relay Fee
<b>Minimum Relay Fee</b>

### Definition

The minimum transaction fee a transaction must pay (if it isn’t a high-priority transaction) for a full node to relay that transaction to other nodes. There is no one minimum relay fee—each node chooses its own policy.

### Synonyms

- Minimum relay fee

- Relay fee

### Not To Be Confused With

- Transaction fee (the minimum relay fee is a policy setting that filters out transactions with too-low transaction fees)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-minimum-fee'>Minimum relay fee</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Transaction_fees'>Transaction fees — Bitcoin Wiki

## Root Seed
<b>HD Wallet Seed, Root Seed</b>

### Definition

A potentially-short value used as a seed to generate the master private key and master chain code for an HD wallet.

### Synonyms

- HD wallet seed

- Root seed

### Not To Be Confused With

- Mnemonic code / mnemonic seed (a binary root seed formatted as words to make it easier for humans to transcribe and possibly remember)

### Links

- <a href='https://bitcoin.org/en/developer-guide#hierarchical-deterministic-key-creation'>Root seed</a> — Bitcoin.org Developer Guide

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki'>BIP32: hierarchical deterministic wallets</a> — Bitcoin Improvement Proposals

- <a href='https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki'>BIP39: mnemonic code for generating deterministic keys</a> — Bitcoin Improvement Proposals

## RPC Byte Order
<b>RPC Byte Order</b>

### Definition

A hash digest displayed with the byte order reversed; used in Bitcoin Core RPCs, many block explorers, and other software.

### Synonyms

- RPC byte order

### Not To Be Confused With

- Internal byte order (hash digests displayed in their typical order; used in serialized blocks and serialized transactions)

### Links

- <a href='https://bitcoin.org/en/developer-reference#hash-byte-order'>RPC byte order</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Block_hashing_algorithm'>Block hashing algorithm (‘endian conversion’)</a> — Bitcoin Wiki

## Satoshis
<b>Denominations</b>

### Definition

Denominations of Bitcoin value, usually measured in fractions of a bitcoin but sometimes measured in multiples of a satoshi. One bitcoin equals 100,000,000 satoshis.

### Synonyms

- Denomination

- Bitcoins

- Satoshis

### Not To Be Confused With

- Binary bits, a unit of data with two possible values

### Links

- <a href='https://en.bitcoin.it/wiki/Units'>Bitcoin Units</a> — Bitcoin Wiki

## ScriptPubKey
<b>Pubkey Script, ScriptPubKey</b>

### Definition

A script included in outputs which sets the conditions that must be fulfilled for those satoshis to be spent. Data for fulfilling the conditions can be provided in a signature script. Pubkey Scripts are called a scriptPubKey in code.

### Synonyms

- Pubkey script

- ScriptPubKey

### Not To Be Confused With

- Pubkey (a public key, which can be used as part of a pubkey script but don’t provide a programmable authentication mechanism)

- Signature script (a script that provides data to the pubkey script)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-pubkey-script'>Pubkey script</a> — Bitcoin.org Developer Guide

## ScriptSig
<b>Signature Script, ScriptSig</b>

### Definition

Data generated by a spender which is almost always used as variables to satisfy a pubkey script. Signature Scripts are called scriptSig in code.

### Synonyms

- Signature script

- ScriptSig

### Not To Be Confused With

- ECDSA signature (a signature, which can be used as part of a pubkey script in addition to other data)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-signature-script'>Signature script</a> — Bitcoin.org Developer Guide

## Serialized Transaction
<b>Serialized Transaction, Raw Transaction</b>

### Definition

Complete transactions in their binary format; often represented using hexadecimal. Sometimes called raw format because of the various Bitcoin Core commands with “raw” in their names.

### Synonyms

- Serialized transaction

- Raw transaction

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-raw-format'>Serialized transactions</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#tx'>Tx message (serialized transaction)</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Transaction'>Transaction</a> — Bitconi Wiki

## Sighash
<b>Signature Hash</b>

### Definition

A flag to Bitcoin signatures that indicates what parts of the transaction the signature signs. (The default is SIGHASH_ALL.) The unsigned parts of the transaction may be modified.

### Synonyms

- Signature hash

- Sighash

### Not To Be Confused With

- Signed hash (a hash of the data to be signed)

- Transaction malleability / transaction mutability (although non-default sighash flags do allow optional malleability, malleability comprises any way a transaction may be mutated)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-signature-hash'>Signature hash</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/OP_CHECKSIG'>OP_CHECKSIG</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Contract#Theory'>Contracts</a> — Bitcoin Wiki

## Serialized Block
<b>Serialized Block, Raw Block</b>

### Definition

A complete block in its binary format—the same format used to calculate total block byte size; often represented using hexadecimal.

### Synonyms

- Serialized block

### Links

- <a href='https://bitcoin.org/en/developer-reference#serialized-blocks'>Serialized blocks</a> — Bitcoin.org Developer Reference

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#block'>Block message (serialized block)</a> — Bitcoin Wiki

## Sequence Number
<b>Sequence Number (Transactions)</b>

### Definition

Part of all transactions. A number intended to allow unconfirmed time-locked transactions to be updated before being finalized; not currently used except to disable locktime in a transaction

### Synonyms

- Sequence number
 
### Not To Be Confused With

- Output index number / vout (this is the 0-indexed number of an output within a transaction used by a later transaction to refer to that specific output)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-sequence-number'>Sequence number</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Protocol_documentation#tx'>Tx message (describes sequence number)</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/2025/what-is-txins-sequence'>What is the sequence number?</a> — Bitcoin StackExchange

## SIGHASH_ALL
<b>SIGHASH_ALL</b>

### Definition

Default signature hash type which signs the entire transaction except any signature scripts, preventing modification of the signed parts.

### Synonyms

- SIGHASH_ALL

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-sighash-all'>SIGHASH_ALL</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/OP_CHECKSIG'>OP_CHECKSIG</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Contract#Theory'>Contracts</a> — Bitcoin Wiki

## SIGHASH_ANYONECANPAY
<b>SIGHASH_ANYONECANPAY</b>

### Definition

A signature hash type which signs only the current input.

### Synonyms

- SIGHASH_ANYONECANPAY

### Not To Be Confused With

- SIGHASH_SINGLE (which signs this input, its corresponding output, and other inputs partially)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-sighash-all'>SIGHASH_ANYONECANPAY</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/OP_CHECKSIG'>OP_CHECKSIG</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Contract#Theory'>Contracts</a> — Bitcoin Wiki

## SIGHASH_NONE
<b>SIGHASH_NONE</b>

### Definition

Signature hash type which only signs the inputs, allowing anyone to change the outputs however they’d like.

### Synonyms

- SIGHASH_NONE

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-sighash-none'>SIGHASH_NONE</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/OP_CHECKSIG'>OP_CHECKSIG</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Contract#Theory'>Contracts</a> — Bitcoin Wiki

## SIGHASH_SINGLE
<b>SIGHASH_SINGLE</b>

### Definition

Signature hash type that signs the output corresponding to this input (the one with the same index value), this input, and any other inputs partially. Allows modification of other outputs and the sequence number of other inputs.

### Synonyms

- SIGHASH_SINGLE

### Not To Be Confused With

- SIGHASH_ANYONECANPAY (a flag to signature hash types that only signs this single input)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-sighash-single'>SIGHASH_SINGLE</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/OP_CHECKSIG'>OP_CHECKSIG</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Contract#Theory'>Contracts</a> — Bitcoin Wiki

## Signature
<b>Signature, ECDSA Signature</b>

### Definition

A value related to a public key which could only have reasonably been created by someone who has the private key that created that public key. Used in Bitcoin to authorize spending satoshis previously sent to a public key.

### Synonyms

- Signature

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-signature'>Signature</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Elliptic_Curve_Digital_Signature_Algorithm'>ECDSA</a> — Bitcoin Wiki

- <a href='https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm'>ECDSA</a> — Wikipedia

## Signature Hash
<b>Signature Hash</b>

### Definition

A flag to Bitcoin signatures that indicates what parts of the transaction the signature signs. (The default is SIGHASH_ALL.) The unsigned parts of the transaction may be modified.

### Synonyms

- Signature hash

- Sighash

### Not To Be Confused With

- Signed hash (a hash of the data to be signed)

- Transaction malleability / transaction mutability (although non-default sighash flags do allow optional malleability, malleability comprises any way a transaction may be mutated)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-signature-hash'>Signature hash</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/OP_CHECKSIG'>OP_CHECKSIG</a> — Bitcoin Wiki

- <a href='https://en.bitcoin.it/wiki/Contract#Theory'>Contracts</a> — Bitcoin Wiki

## Signature Script
<b>Signature Script, ScriptSig</b>

### Definition

Data generated by a spender which is almost always used as variables to satisfy a pubkey script. Signature Scripts are called scriptSig in code.

### Synonyms

- Signature script

- ScriptSig

### Not To Be Confused With

- ECDSA signature (a signature, which can be used as part of a pubkey script in addition to other data)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-signature-script'>Signature script</a> — Bitcoin.org Developer Guide

## Simplified Payment Verification
<b>SPV, Simplified Payment Verification</b>

### Definition

A method for verifying particular transactions were included in a block without downloading the entire block. The method is used by some lightweight Bitcoin clients.

### Synonyms

- SPV

- Simplified Payment Verification

- Lightweight client

- Thin client

### Links

- <a href='https://bitcoin.org/en/developer-guide#simplified-payment-verification-spv'>SPV</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Thin_Client_Security'>Thin client security</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/32529/what-is-a-thin-client'>What is a thin client?</a> — Bitcoin StackExchange

## Soft Fork
<b>Soft Fork, Soft-Forking Change</b>

### Definition

A temporary fork in the block chain which commonly occurs when miners using non-upgraded nodes violate a new consensus rule their nodes don’t know about.

### Synonyms

- Soft fork

### Not To Be Confused With

- Fork (a regular fork where all nodes follow the same consensus rules, so the fork is resolved once one chain has more proof of work than another)

- Hard fork (a permanent divergence in the block chain caused by non-upgraded nodes not following new consensus rules)

- Software fork (when one or more developers permanently develops a codebase separately from other developers)

- Git fork (when one or more developers temporarily develops a codebase separately from other developers

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-soft-fork'>Soft fork</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Softfork'>Soft fork</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/30817/what-is-a-soft-fork'>What is a soft fork?</a> — Bitcoin StackExchange

## SPV
<b>SPV, Simplified Payment Verification</b>

### Definition

A method for verifying particular transactions were included in a block without downloading the entire block. The method is used by some lightweight Bitcoin clients.

### Synonyms

- SPV

- Simplified Payment Verification

- Lightweight client

- Thin client

### Links

- <a href='https://bitcoin.org/en/developer-guide#simplified-payment-verification-spv'>SPV</a> — Bitcoin.org Developer Guide

- <a href='https://en.bitcoin.it/wiki/Thin_Client_Security'>Thin client security</a> — Bitcoin Wiki

- <a href='http://bitcoin.stackexchange.com/questions/32529/what-is-a-thin-client'>What is a thin client?</a> — Bitcoin StackExchange

## Stale Block
<b>Stale Block</b>

### Definition

Blocks which were successfully mined but which aren’t included on the current best block chain, likely because some other block at the same height had its chain extended first.

### Synonyms

- Stale block

### Not To Be Confused With

- Orphan block (a block whose previous (parent) hash field points to an unknown block, meaning the orphan can’t be validated)

### Links

- <a href='https://bitcoin.org/en/developer-guide#term-stale-block'>Stale blocks</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/5859/what-are-orphaned-and-stale-blocks'>What are orphaned and stale blocks?</a> — Bitcoin StackExchange

## Standard Transaction
<b>Standard Transaction</b>

### Definition

A transaction that passes Bitcoin Core’s IsStandard() and IsStandardTx() tests. Only standard transactions are mined or broadcast by peers running the default Bitcoin Core software.

### Synonyms

- Standard Transaction

### Links

- <a href='https://bitcoin.org/en/developer-guide#standard-transactions'>Standard transactions</a> — Bitcoin.org Developer Guide

- <a href='http://bitcoin.stackexchange.com/questions/5664/will-general-non-standard-transactions-ever-be-allowed'>Will general non-standard transactions ever be allowed?</a> — Bitcoin StackExchange

## Start String
<b>Start String, Network Magic</b>

### Definition

Four defined bytes which start every message in the Bitcoin P2P protocol to allow seeking to the next message.

### Synonyms

- Start string

- Network magic

### Links

- <a href='https://bitcoin.org/en/developer-reference#term-start-string'>Start string</a> — Bitcoin.org Developer Reference

- <a href='http://bitcoin.stackexchange.com/questions/2337/how-was-the-magic-network-id-value-chosen'>How was the start string chosen?</a> — Bitcoin StackExchange
