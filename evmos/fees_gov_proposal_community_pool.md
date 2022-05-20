# Fee Rewards - Governance Proposal for Redirecting Rewards to the Community Pool

Proposal to solve https://commonwealth.im/evmos/discussion/4966-fee-rewards-for-functional-monopolies-not-sourceinvented-by-deployer-should-go-to-the-community-pool.

Introduce a governance proposal for the fees module, where a smart contract registered for fee distribution can be marked as public good, so that fee rewards are sent to the Community Pool.


```go
func NewFeesCommunityPoolProposalHandler(k *keeper.Keeper) govtypes.Handler {}
```

## Possible implementations to mark the contract as public good:

1) introducing an `isPublicGood` attribute in a KVStore `contract common.Address => isPublicGood bool`
2) changing the withdraw address to the `Distribution` module address (because the Community Pool does not have its own address)

**Note:** I suggest 1), because the governance proposal can then toggle the`isPublicGood` status easily. So, it can also revert a decision by vote.

## Proposed Features:

1) No one can propose to mark a contract as public good for the first `x` blocks (e.g. for the equivalent of 6 months). It is fair to reward for deployment & maintenance (if any) effort.
2) After a contract is marked as public good:
  - fee rewards are sent to the Community Pool
  - deployer cannot change the withdraw address
  - deployer cannot unregister the contract
3) The decision to mark a contract as public good can be reverted through governance by setting `isPublicGood = false`. Fee rewards will be sent to original withdraw address.
