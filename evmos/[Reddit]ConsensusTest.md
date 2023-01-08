# Consensus Test [Evmos Governance Post]


Discussion: [the discussion is this Reddit thread](https://www.reddit.com/r/cosmosnetwork/comments/106mko3/consensus_test_evmos_governance_post/)

## Exposition
In a positional numeral system with integer radix greater than 2:
1 + 1 = 2


## Meaning of the Decision

* 1. if this proposal passes: the chain affirms that 1+1=2 is true (under given conditions)
* 2. if this proposal is rejected: the chain affirms that 1+1=2 is false
* 3. if this proposal is rejected by veto: the chain wanted to punish the proposer and used any rationalization to do so. (Even at the expense of governance duties and at the cost of reducing present and future decisional legitimacy of governance.)

## Additional Note

Since this proposal is a proposition, it has to obey the rules of Propositional Calculus including that it is closed under truth-functional connectives.

As a result of this, the proposer could have made 2 proposals to achieve the same 'meaning of decision':

prop 1 (p1):

'In a positional numeral system with integer radix greater than 2:
1 + 1 = 2'

prop 2 (p2 that is the negation of p1: not-p1):

'In a positional numeral system with integer radix greater than 2:
1 + 1 does not equal 2'

Both with chain decision choices:

1. pass
2. reject
3. reject by veto

The table of equivalence (for any practical purposes) would be:

1. (for point 1 of the original proposal's decision meaning) if p1 passes and not-p1 is rejected 
2. if not-p1 passes and p1 is rejected
3. if anything else

Therefore the proposer presented the meaning of the decision of this proposal with the intent to save voters' time and avoid proposing 2 proposals instead of 1.

## Context

[https://www.reddit.com/r/cosmosnetwork/comments/1032ehn/how_to_centralize_a_chain_by_manipulating_cosmos/](https://www.reddit.com/r/cosmosnetwork/comments/1032ehn/how_to_centralize_a_chain_by_manipulating_cosmos/)
[https://github.com/the-laurel/chain-proposals/blob/main/evmos/%5BReddit%5DHow_to_centralize_a_chain_by_manipulating_Cosmos_Governance.md](https://github.com/the-laurel/chain-proposals/blob/main/evmos/%5BReddit%5DHow_to_centralize_a_chain_by_manipulating_Cosmos_Governance.md)

In Evmos Governance:

1. https://www.mintscan.io/evmos/proposals/83 was passed which contained a lot of text.

> One of the paragraphs [there](https://github.com/EvmosGov/proposals/blob/main/ECP/ECP-1.md#2-the-ecp-lifecycle) reads:
> 
> **Phase 1: Discussion & Ideation | Min. 48 hours | Forum Tag: [IDEATION]**
> The purpose of this phase is to vet ideas with the active Evmos community members. Each idea for a proposal should have its own Commonwealth thread, and discussions should be as narrowly focused as possible. 

2. There is an unknown actor, not elected by the chain, who deletes or hides from the public the proposal threads from https://commonwealth.im/evmos/discussions, therefore nobody may be able to propose anything that is not in line with the will of that actor. Therefore the chain requirement for creating a proposal cannot be fulfilled.
3. Presumably the same unknown actor (or a different one) banned 2 Evmos validator accounts from doing anything on https://commonwealth.im:
![https://raw.githubusercontent.com/the-laurel/chain-proposals/main/evmos/assets/banned_CW.png](https://raw.githubusercontent.com/the-laurel/chain-proposals/main/evmos/assets/banned_CW.png)
So the voting power represented by those 2 validators is eliminated from any future discussions.
4. Conclusion: whoever can do this to the Evmos Commonwealth fully controls Evmos Governance.

For these reasons, for the last proposals for Evmos, we had to depart from the normal governance process.

## Governance Context

After Evmos decided: 
- that the governance process [may not be in English](https://www.mintscan.io/evmos/proposals/93)
- that anybody and/or nobody may [officially represent the will of the chain](https://www.mintscan.io/evmos/proposals/98)
- that the chain may be allowed to [take criminal decisions](https://www.mintscan.io/evmos/proposals/99)

One cannot but wonder if the chain will decide to manufacture its own facts and Mathematics.

## Author
Christian Tzurcanu, volunteer for The Laurel Project. Efforts performed for The InterChain Pact office.

