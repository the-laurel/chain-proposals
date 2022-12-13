# The Principle of Determinism

## Precedence

- [The Existence of (Governance) Principles](https://github.com/the-laurel/chain-proposals/blob/main/laurel/ExistenceOfPrinciples.md)

## Exposition

The automatic consensus performed by the validators of a blockchain is based on 2 assumptions:
1. state does not change if no transformation is explicitly applied: immutability of state
2. any transformation of state (transaction) is deterministic: for the same inputs the same output (or state change) is always obtained

Without both those assumptions remaining true (and maintained true by the blockchain mechanism), the consensus would not be valid and the blockchain would suffer an interruption of computational integrity.

The same has to apply to the consensus on governance. The source code (proposal text) for the transformation (the governance decision) should be as close to fully deterministic as possible. That means the text has to have a unique meaning and intent (exclude all ambiguities).

Governance is the pre-eminent mechanism for establishing the rules of the game. There is governance by code (and that is already deterministic for blockchains case) and governance by vote (and that too should strive to be fully deterministic). The rules of the game should be universally-understood in the same way by the players before a game is enjoined.

## Rules
1. If 2 paragraphs of text for a prospective proposal can carry the same meaning but one is more deterministic than the other, the proposal has to choose the former.
2. A computer language is preferable to a natural language for any governance proposal.
3. Terseness up to the point of achieving the unicity of meaning (but not more terse than that) is more deterministic.
