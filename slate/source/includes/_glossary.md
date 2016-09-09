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

## Compressed Public Keyy
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
