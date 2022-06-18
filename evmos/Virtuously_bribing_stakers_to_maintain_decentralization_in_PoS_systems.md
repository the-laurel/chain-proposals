# The Virtuous Bribe: Decentralization and Chain Security in Blockchain Proof of Stake

https://youtu.be/R4clQ47s7w4

## The Bribe

Any incentivization is a bribe. Any bribe is an incentivization.
Incentivization, interest, quantitative easing, rewards, these are facets of the same concept.

The concept is using resources and services for aligning intent between two or more parties that otherwise would diverge, or would at least be neutral.

The miracle of blockchains and especially Proof of Stake blockchains is the transformation of personal greed into computing power and public, transparent, proof of consensus.

It is digital, decentralized, grassroots-governed capitalism. 

Validators and delegators in Proof of Stake systems, have one main role: securing the network. And in exchange for their service, they receive rewards. And in systems like Cosmos, they have power to govern and vote, proportional to their stake.

So, there are two main reasons for staking: direct greed and indirect greed, by being able to govern the chain.

## The Virtuous Bribe

To determine if a bribe is "positive" or "negative", we need to determine the effects of the bribe or incentivization over time. We need to see how decentralized is the bribe, how fair and meritocratic are the conditions for the bribe.

A virtuous bribe is
- largely-distributed / popular
- unequal: judiciously apportioned
- advantageous to the virtues
- controlled by feedback loop
- benefiting most (generating token value) 
- sustainable

Airdrops are bribes. But if they decentralize funds enough, have a large number of beneficiaries, the airdrop has some meritocratic conditions like past contributions or past gas usage on other networks and the airdrop is marketed so that people have a good chance to know about it, then airdrops can be a tool for decentralization. A good example of such an airdrop is what the Evmos blockchain has done to bootstrap its initial user base and you can read more about it in their blog.

## The Virtues of Blockchain

What are we protecting here, when talking about bribes? 
We are protecting  first principles derived from how blockchains function. A bribe has a negative effect, if it goes against one or more of these principles.

- Decentralization
- Immutability of logs, or records, or transactions
- Consensus on mutations of state
- Asset materiality: move instead of copy
- Provability
- Robustness which is the usual implication of decentralization and means survivability across:
  - Time
  - Space (across jurisdictional impositions or local calamities)
  - Digital attacks
  - Governance malevolence
  - Economic attacks

### Governance Malevolence

Now let's talk about Governance Malevolence and some of the rules that, if broken, will constitute an attack on the blockchain principles we discussed earlier.

Not recusing yourself from voting “Yes” when the proposal benefits your validator or delegators in a greater degree than the rest

Blackmailing: “I will redelegate my funds if you do not vote to my benefit, to the expense of the community”

Bribing: “I will airdrop some tokens to those who voted “Yes” on this proposal that benefits me or my group”

Duplication of will: same identity owns multiple validators

Oligarchy: < 10% of active validators own > 51% of the bonded value


These malevolent governance practices and their effects become even more clear when you turbocharge staking rewards.
In the Evmos blockchain case, the staking rewards are currently very large. Today's APR is 727%, based on how much you staked. This fast-tracks whales to become even bigger whales.

This mechanism of rewarding the first to come in a disproportionate way, if not countered by other types of bribes, leads to centralization of power or puts the chain's security at risk.

![Evmos_Validator_Delegations_2022-06-18.png](https://raw.githubusercontent.com/the-laurel/chain-proposals/main/evmos/assets/Evmos_Validator_Delegations_2022-06-18.png)

Just look at the situation today in this chart of active validators (150 active validators, from the existing 250), ordered by the tokens delegated to them.
In orange, you see an estimation of the estimated  weekly rewards.

The inflation itself is the same for all stakers or delegates, so, it does not matter if you stake with a validator with higher or lower voting power. Your rewards are the same. Unless the validators bribe you in other ways.
And when you see such discrepancy between validators, it means that we are talking about bribes or whales or both.

This is a blockchain in danger of wandering out of its survivability range. Just imagine what happens if the gap between the first 1-2 validators and the rest gets big enough so it will not be covered by rewards well enough for the rest of validators to justify continuing their validating services: Evmos would collapse. Or worse: make-believe (ghost) validators would appear entirely under the control of the 1-2 most powerful and doing only the bidding of those for any governance proposal. (This situation is the end-point to many scenarios.)

## Inflation as a Virtuous Utility

But inflation done right can be a Virtuous Utility

Because anything that leads towards the creation of more virtues or to the continuity of virtues across time and space is virtuous.

Staking rewards links personal greed with utility offered to the community by preservation across time of the existence of a blockchain with all its virtues.

As governable domain extends, governance may be used to weaken the intended virtues of the blockchain. 
But we are here to correct this situation.

![Evmos_Validator_VotingPower_2022-06-18.png](https://raw.githubusercontent.com/the-laurel/chain-proposals/main/evmos/assets/Evmos_Validator_VotingPower_2022-06-18.png)

This is the equivalent of the previous graph, but aligned by voting power. The first validators have more than 20% of the network. The first 4-5 validators are enough to pass any governance proposal.

## The Ideal Validator Structure for Maintaining Decentralization 

Validators should:
- have approximately the same voting power
- have different dedicated machines around the world
- have different identities
- if multiple clients, have a homogeneous distribution

If your chain's economics brings you to a handful of validators being able to pass or reject any governance proposal, then your chain is done. It is not decentralized. And if no mechanism is able to correct it, it will not survive in long run to be something more than a playground for whales to make money.
So, what can you do? Because you cannot steal the whales tokens. That is immoral. Using the same principles we talked about for Virtuous Bribes, we need a general mechanism, that applies to everyone. 

If not the same voting power:
- protect the stable middle
- grow the small tail
- lower the highest outliers 

And you get stable security for the chain and a base for future transparent political abstractions on top of it.

## Solutions: 

### 1) Inverse Proportional Inflation

A wholesome way to solve this validator centralization issue is decrease inflation rewards for all delegators of validators that are above the ideal voting power and increase inflation rewards for all below this ideal value. In the case of Evmos, the average voting power would be 100 divided by 150 active validators: 0.667 %.

So, all these validators below 0.667% would get higher than average rewards. And those above it, lower.

It is a wholesome solution, because it is a decentralized, unequal but with positive effects bribe. Directed at the entire user base.

The second solution, that can be implemented without protocol changes, right now is:

### 2) Inverse Proportional Delegations from the Chain's Foundation.

But these delegations need to be done inversely proportional to the voting power and need to protect the stable middle too.
You intent is to increase the small validators and decrease the large outliers without compromising the middle.

Each two weeks, recalculate these delegations and redelegate accordingly.

This second solution is less wholesome, because it does not engage the entire user base to change its behavior to protect the chain. But, it is still a virtuous bribe.

In future articles and videos we will expand these solutions and show how they can be implemented.


If greed can be transformed into powerful consensus, the bribe can be transformed into a virtuous one.

- largely-distributed / popular
- unequal, but positive effect: advantageous to the virtues
- benefiting most (generating token value)
- sustainable
- controlled by feedback loop


We will continue to refine and share our solutions for rightful governance. We will soon propose a fully-specced implementation for making inflation gain virtue for any Cosmos SDK chain.
