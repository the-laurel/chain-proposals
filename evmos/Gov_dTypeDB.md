# dTypeDB - the first inter-chain database

https://commonwealth.im/evmos/discussion/4980-dtypedb-the-first-interchain-database

I am Loredana, my contribution to Evmos is: 1500 hours of volunteer effort over the past 4 months, I single-handedly wrote the fees module and produced demos of never before seen features to demonstrate what could be built on a Cosmos-EVM chain, like Evmos. I run the evmos4volunteers validator on behalf of The Laurel Project, which is a project built by and for volunteers.
I have been building for the Ethereum blockchain space since 2017 and my video demos prove that.

Together with The Laurel Project, we propose the creation of the first inter-chain database. We have started such a database for the EVM in Ethereum, by working directly in assembly and our own custom language: Taylor. That made it exceptionally gas-efficient and free from the inherent limitations of both Solidity and Yul.
The beginnings were with dType EIPs:
https://github.com/pipeos-one/dType#ercs

Since then, we created a generalized state bridge that works by transaction replay: Golden Gate Bridge (https://github.com/pipeos-one/goldengate). We modified that bridge for the IBC and abstract accounts: 
The result of combining dTypeDB with the Golden Gate Bridge will be the inter-chain DB. We want to develop it in Go to make it compatible with any Cosmos SDK chain. We need support to bring it to Evmos first.

The chain that will support this database first will enjoy the network benefits of becoming the hub for inter-chain communication. It will also hold the most important and central data (like data about types). See our idea about the Master Shard for Ethereum 2
https://github.com/pipeos-one/dType/blob/master/docs/dType_Ethereum_2.0.md#ethresearch-proposals

Most of the code that we produced to date is open source only for active volunteers of The Laurel Project, and closed source for the public. Why? Because some of our ideas have been stolen by other developers to be used for-profit and nobody defended our intellectual property. If the Evmos community supports this proposal with enough resources that will ensure no one else can present these ideas & code as theirs, we will open-source this effort.

Pieces of this technology demoed:

We start with a new type of object that can live on several smart contracts, built with a hierarchical type model. This object will be used to sync or change data across chains. 

https://youtu.be/qGKdLK_aG10 The Ethereum Deep Object Pattern
https://youtu.be/AzUdkyJFoMA The Ethereum Deep Object Pattern (EDO) - Deep Get and Deep Set [DEMO]

Stored on a decentralized data service - built on primitive types. This is demoed as a smart contract built with EVM Taylor, but the same footprint will apply to the database counterpart built in Go (as an EDS Cosmos SDK module).

https://youtu.be/EI74YA1nbVo The Ethereum Data Service [EDS]
https://youtu.be/Q53ylKzhJv0 The Ethereum Data Service (EDS) - Human & Machine-Readable Yaml Output (blockchain pattern)
https://youtu.be/z4mt9rLRI0Y The Scientific EVM - with The Ethereum Data Service (EDS)

Examples of several ways (one less costly than the others) to store on-chain data contiguously and efficiently.
https://youtu.be/KB-hG-rQ-yA The Decentralized Database [dDB] - on the Ethereum Virtual Machine [EVM]

Having a decentralized database can introduce a new type of compiler: a decentralized one. This compiler does the compilation directly on-chain using decentralized libraries and functions:

https://youtu.be/ilC9p2_Ya34 dComp: The Decentralized Compiler


https://youtu.be/i919HWLUv1w Important blockchain pattern: the Decentralized (Deep) Function - dFun (built on the EDS)

All of the above demos were done based on the same technology: dTypeDB for EVM. dTypeDB for Cosmos in Go will be able to do the same and more.

This last demo is all about generalized (state) bridging. This is not the normal bridging that is asset-only. This is a bridge for absolutely ANY transaction. This is the only bridge flexible enough to accommodate bridging a database:

https://youtu.be/I7zYXEtMeD4 Trustless Bridging (1) with InterChain Transactions for EVM Smart Contracts, with Cosmos IBC & Evmos

We open-sourced the theory for this special bridge at: https://github.com/pipeos-one/goldengate/tree/master/research/cosmos

Our proposal is for creating dTypeDB in Go for Evmos and integrating it with The Golden Gate Bridge to obtain the first inter-chain database.
While I am ready to remain a volunteer until dTypeDB becomes ready to use, we need more developers - either volunteers or paid through a grant from the Evmos Community. We (The Laurel Project) also have a duty to treasure resources for future innovation and services to volunteers.

Should Evmos be the chain we are looking for as the main host of inter-chain dTypeDB? It all depends on how you vote on this proposal. The proposal will be formalized after 6-7 days of discussions here, in the Commonwealth of Evmos. Thank you for your input. The core developers are especially welcome to voice their opinion.
