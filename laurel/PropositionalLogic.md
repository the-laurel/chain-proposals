# Governance Consensus: Propositional Decisions

## Dependence: Dependent On:
- Cosmos SDK v0.45.10 or any compatible version
- Cosmos SDK Governance

## Exposition
When a governance proposal has a form fully compatible with a logic proposition, the decision is binding according to the zeroth-order logic. 
According to https://en.wikipedia.org/wiki/Propositional_calculus:
Propositional logic is closed under truth-functional connectives. That is to say, for any proposition φ, ¬φ is also a proposition.
If φ becomes a proposal (while remaining a proposition), by rejecting φ, the governance automatically passes ¬φ. Passing happens by a quorum being met and a majority of "Yes" votes or by the rejection of the negation of the proposition.

If that would not be the case:
- If φ is rejected: the proposer of φ may also propose ¬φ
- if ¬φ is also rejected: the governance loses legitimacy by admitting logical contradictions to pass.
- if ¬φ passes: it is fully compatible with accepting the closure under truth-functional connectives, but consuming 2 voting rounds instead of 1.

## Measures
1. Any propositional proposals φ shall be reasoned according to Propositional Calculus
2. If φ does not pass governance, it means that ¬φ passed
