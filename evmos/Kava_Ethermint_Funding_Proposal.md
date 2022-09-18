# Ethermint Funding Proposal For Past Development, Addressed from The Evmos Community to The Kava Community

https://www.mintscan.io/evmos/proposals/62

This is an inter-chain diplomacy proposal for the Evmos Community to ask the Kava Community to reward [Ethermint past development efforts](https://github.com/evmos/ethermint/graphs/contributors) (done until September 1st 2022), with 2.5M (2,500,000) EVMOS.

$Kava tokens will be used to buy $EVMOS.
On Evmos, the 2.5M $EVMOS will be used for Ethermint development, following a similar procedure to Evmos Grants:
- stake the $EVMOS to active validators that have under 0.66% voting power, to improve Evmos's Nakamoto Coefficient
- fund Ethermint development from staking rewards

Multisig on Evmos: 0xd04DB421f518D0E3449D2A3cefEac25b31485c71
- Mr.Sir | Orbital Apes
- InstaFinanzas | Stakin
- LPX | Evmos Governance
- arda | Validator.run
- luisqa | OzMage Validation

Multisig on Kava will be created with the same composition if this proposal will pass.

Discussion on Evmos: https://commonwealth.im/evmos/discussion/6867-external-ethermint-funding-proposal-on-kava-price-discovery-vote
Governance Council Discussions: https://youtu.be/Pn_u6WyiQ6c?t=544, https://youtu.be/n-XaFrDV7mE?t=677
Multisig signers discussion: https://discord.com/channels/809048090249134080/913597332073898034/1020236682907353212

## Summary of Facts

- [Ethermint](https://github.com/evmos/ethermint/graphs/contributors) is a Go module that bridges the Cosmos APIs (Cosmos SDK, Tendermint, IBC, etc) to EVM (using the [go-ethereum](https://github.com/ethereum/go-ethereum) library as module). It is the de-facto way to have EVM-powered Cosmos chains.
- Ethermint's is developed and maintained by Tharsis & other contributors & volunteers.
- [Kava](https://www.kava.io/) is "One Network. Two Chains. Ethereum and Cosmos."
- Kava is today valued at ~$400M market cap
- Estimated total value locked: ~$140M
- Initial investment in building and marketing Kava is less than $1M
- "Kava Rise Program: $750M Developer Incentive Program. The structure of the Rise program will focus primarily on driving adoption and growth for the new Ethereum Co-Chain."
- Kava Community Pool has ~80M KAVA tokens
- Kava uses Ethermint for their Ethereum Co-Chain and Cosmos SDK for Cosmos in [their code](https://github.com/Kava-Labs)
- Tharsis made [this Commonwealth proposal](https://commonwealth.im/evmos/discussion/6684-external-evm-infrastructure-funding-proposal-on-kava) to the Evmos and Kava communities, "requesting 3M out of ~80M KAVA tokens (3.7%) from the Kava Community Pool Treasury to fund, develop and advance critical EVM Infrastructure through the Ethermint Engineering and R&D team for 1 year.", followed by opening a [Kava Community Discussion](https://www.reddit.com/r/kava_platform/comments/wsa37v/evm_infrastructure_funding_proposal_on_kava/). Resulting in the formal [on-chain Kava proposal #96](https://www.mintscan.io/kava/proposals/96)
- Proposal #96 was rejected. 13/21 of the top validators votes YES, 1/21 voted ABSTAIN, and 7/21 did not vote. The top 21 validators have 88.90% voting power. Kava's co-founder & CEO's [response](https://twitter.com/Scott_Stuart_/status/1563228443436728321).
- Kava Labs made its own "Kava Infrastructure Security rewards" [proposal #97](https://www.mintscan.io/kava/proposals/97), with no mention of funding Ethermint, as critical infrastructure. With no link to any Kava Community discussion. This proposal passed.
- "The Kava DAO is a fully decentralized autonomous organization (DAO) that governs the Kava Network. Made up of the Kava stakers and validators that help to secure and run the network"
- Kava did not make any concrete offers to reward past development efforts for Ethermint

## Why the Evmos Community has standing?

- Evmos uses Ethermint as core infrastructure
- Tharsis has most funds from the $EVMOS coin growth, so the Evmos chain became the de-facto treasurer for Tharsis
- The Evmos Community are the guardians of Evmos interests, which include Ethermint and the well-being of Tharsis devs

## Inter-Chain Diplomacy

Right now, Ethermint tech is an exportable product from the Evmos chain to all other chains that do not make development effort towards it (but use it), therefore the payment should be in $EVMOS.

The Evmos community now has the standing to make a funding proposal in the name of Tharsis, in $EVMOS, first on the Evmos governance, then on Kava.

Given that the Kava Community rejected the request for funding Ethermint's future development, for 1 year, we propose that another funding request should be made to Kava by the Evmos Community, for past development efforts, that have already taken place and have already brought value to Kava. Any other future funding requests will be discussed separately.

Off-chain polls & discussion for price discovery were opened in [Evmos Commonwealth](https://commonwealth.im/evmos/discussion/6867-external-ethermint-funding-proposal-on-kava-price-discovery-vote).

## What will Kava stand to gain?

Ethermint will enter the most technically interesting phase: custom precompiles and EVM-Inter-Chain. Working prototypes already exist and were presented https://youtu.be/x75UobIr4qo?t=14670 and the ground work for Ethermint was set with https://github.com/evmos/ethermint/pull/1272.

(proposal lead:) I have personally developed the Go groundwork for inter-chain cooperation and deployed three public technical blockchains with EVM-Cosmos (Mythos, Ethos, and Logos), for demoing the inter-chain tech and I will re-base my work on the Ethermint extensibility of EVM precompiles.
Some precompiles that I created that are pertinent to this:
- abstract accounts (implementing account abstraction for EVM https://hackmd.io/@matt/r1neQ_B38)
- quasar: ability to run Cosmos transactions from EVM
- IBC precompile for EVM
- nBridge: n-way (n>=2) generalized bridge by transaction replay
(Demos at: https://www.youtube.com/c/LoredanaCirstea/videos)

Next generation protocols are inter-chain. If Kava rewards past Ethermint development efforts, and demonstrates will to collaborate, it has a chance to be invited to benefit from the EVM-Inter-Chain innovations. This is no longer Ethermint, it is next-generation Ethermint (with extensions) and licensing may be subjected to change if context requires it.
We hope the Kava Community will not choose the short-term frugality over long-term greater benefits. Especially that this is an ethical opportunity that benefits Kava as image, Evmos, and the whole Cosmos.


## Why should the Cosmos Community care?

1. Blockchains are entities with communities. So, we need to have rules for behaving between chains. The proposal is bringing clarity to what is civil between chains (in this case, pertaining to funding previous dev efforts). Rejecting a proposal from Tharsis is different than rejecting a proposal from the Evmos Community. Kava and Evmos are part of the larger Cosmos Inter-Chain ecosystem.
2. This proposal's purpose is to find a general way to determine a fair ask for any other chains, not only Kava.
3. Ethermint is a core piece of infrastructure that brings value to Cosmos. The Cosmos Community should fight to keep it open-source and well-developed.
4. Fairly rewarding effort made to evolve Cosmos is critical to inter-chain cooperation.
5. Upholding the values of decentralized governance in each chain is a critical requirement for any inter-chain cooperation.


## Votes

If you vote YES: This proposal will be posted on Kava's subreddit, for Kava Community feedback. And then, as an on-chain proposal to the Kava Community.


## Proposal Lead

This proposal was led on behalf of the Evmos Community, by Loredana Cirstea - elected by vote in the Evmos Interchain Office (Evmos Governance proposal #45) and a volunteer from The Laurel Project (https://evolve.provable.dev/). This proposal is made from a volunteer capacity (independent, unpaid, self-funded, and from the heart).
