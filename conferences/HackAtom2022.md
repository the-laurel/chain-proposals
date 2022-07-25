# HackAtom 2022 Seoul

## Trailblazing the EVM Inter-Chain
_A practical guide for modifying EVM standards like ERC20, ERC721, etc. so they work in a IBC universe._

Optional preliminaries: https://www.youtube.com/playlist?list=PL323JufuD9JCrElzoheW-oJMujGjHtp-k
Be ready to program the Solidity interfaces for a generalized IBC bridge. You will learn the rules for changing any one-chain standard contract into a multi-chain standard. Then share with others your discoveries in after-thon virtual interactions.

### Introducing the n-way Bridge: nBridge

- trustless
- based on IBC, Inter-Chain Accounts
- implementing Account Abstraction [EIP2938](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2938.md)
- executing transaction replay
- on n chains with n >= 2

### Types of Transactions for the Inter-Chain

1. localized: on 1 chain
1. inter-chain (limited to 2 chains)
1. all-chain (inter-chain to all chains in the ring)
1. all-chain (unlimited to the present chains in the ring)

In fact: the types of transactions are a side-effect of the types of variables:

1. localized: example: the link between an asset and a local address
2. unique (guaranteed localization on 1 chain): an asset
3. all-chain (gauranteed mirroring): total supply

### Popular Transactions and Their Mapping

- mint/burn an asset: are at least all-chain
- move an asset from one chain to another: inter-chain (limited to 2 chains)
- transfer an asset to one owner to another on the same chain: localized
- 

### Forwarding View and Pure Calls

- by IBC
- by wallet

### Introducing the ganas Wallet

- connects to Ethereum, Cosmos
- encodes Cosmos SDK, Ethereum call/tx data
- is Inter-Chain aware
  - forwards view and pure calls
  - presents the inter-chain transactions
- doubles as mobile IDE
- easy to extend: publishes dApps and native extensions to IPFS
- reads/shows QR codes
- 
