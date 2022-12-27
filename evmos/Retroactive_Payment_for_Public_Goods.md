# Retroactive Payment for Public Goods (Evmos Development for March 2022)

Since [proposal 88](https://www.mintscan.io/evmos/proposals/88) has been rejected, the volunteers for Tharsis and Evmos will have the opportunity to ask the Evmos chain for clarification of the status of their efforts.

## Exposition

The for-profit developers of Tharsis were paid by salary for their development work. Then Tharsis extracted tens of millions of dollars from the apparent value of the Evmos chain to pay themselves again.

The Laurel Project which volunteered for Tharsis for developing a good portion of the Evmos chain tech and some Ethermint coding will also ask the Evmos Community if their efforts will be accepted in perpetuity as volunteering or if they will be paid as retroactive public goods funding.

## The Public Goods Created

[22 Feb - 21 March 2022: ~359.5h](https://github.com/loredanacirstea/CV/blob/5a6aa821f7c22515b557f443c63de081e8a5700f/evmos/2.%20March_2022.md)

### Ethermint: ~100h

- AnteHandler - GasMeter with unenforced gasWanted limit, to be used for bounding block gas in the block proposal phase [https://github.com/tharsis/ethermint/pull/964](https://github.com/tharsis/ethermint/pull/964) (reading docs, implementing, debugging - 55h)
- eth_feeHistory - fix reward calculation [https://github.com/tharsis/ethermint/pull/990](https://github.com/tharsis/ethermint/pull/990) after 2 quick fixes ([https://github.com/tharsis/ethermint/pull/970](https://github.com/tharsis/ethermint/pull/970), [https://github.com/tharsis/ethermint/pull/975](https://github.com/tharsis/ethermint/pull/975)) - trying to reproduce the issue ([https://github.com/MetaMask/metamask-extension/issues/13649#issuecomment-1067953572](https://github.com/MetaMask/metamask-extension/issues/13649#issuecomment-1067953572), [https://github.com/MetaMask/metamask-extension/issues/13874#issuecomment-1067390401](https://github.com/MetaMask/metamask-extension/issues/13874#issuecomment-1067390401)), sync mainnet/testnet nodes, implement fix, write issues, help document postmortem - 45h

### Integration Testing for Evmos Vesting Module: ~30h

[https://github.com/tharsis/evmos/pull/317/commits/2f3682d63906d11eb764f40d83928345465f30ad](https://github.com/tharsis/evmos/pull/317/commits/2f3682d63906d11eb764f40d83928345465f30ad)

I have discovered the following implementations that did not conform with the intent (bug):
- vested but unlocked coins were allowed to be delegated - [https://github.com/tharsis/evmos/pull/286#pullrequestreview-893077040](https://github.com/tharsis/evmos/pull/286#pullrequestreview-893077040)
- clawback before unlock would also clawback vested coins

### Integration Testing for Evmos Claims Module: ~55h

[https://github.com/tharsis/evmos/pull/373](https://github.com/tharsis/evmos/pull/373)

### PR Reviews: ~3h

- [https://github.com/tharsis/ethermint/pull/935](https://github.com/tharsis/ethermint/pull/935)
- https://github.com/tharsis/ethermint/pull/953
- https://github.com/tharsis/ethermint/pull/968
- https://github.com/tharsis/ethermint/pull/991
- https://github.com/tharsis/evmos/pull/317
- https://github.com/tharsis/evmos/pull/339
- https://github.com/tharsis/evmos/pull/360

### JS notebooks for testing: 8h

Script for sending multiple transactions to evmos with random gas prices/fees, or testing Metamask: [https://observablehq.com/@loredanacirstea/evmos-stress-test](https://observablehq.com/@loredanacirstea/evmos-stress-test)
Playground for testing evmosjs libs: [https://observablehq.com/@loredanacirstea/evmos-js](https://observablehq.com/@loredanacirstea/evmos-js).


### Evmos Core Team Calls

Presence in calls: 9*0.5 + 1 * 2 = 6.5h

### Other tasks for Evmos: 5h

- [my moral take on Evmos launch and upgrade fail](https://github.com/the-laurel/governance/blob/main/docs/EthicsOfBlockchainGovernance.md): 3h
- the present document: 2h

### Video Demos of What can be built on Evmos

(the ideas presented in the videos are the intellectual property of The Laurel Project and are outside the scope of this proposal)

#### EVM interpreter precompile (demoed on an Evmos fork): 43h

- video Feb 26, 2022: [https://youtu.be/uzc1ijYhZE8](https://youtu.be/uzc1ijYhZE8)
- video script, recording, editing, publishing: 4h
- precompile programming: 36h
- dapp: 3h


#### EVM Interpreter Precompile used as a Trustworthy Compute Engine (with a spreadsheet engine): 33h

- video Mar 5, 2022: [https://youtu.be/kHDxDiM5xvQ](https://youtu.be/kHDxDiM5xvQ)
- video script, recording, editing, publishing: 4h
- precompile programming: 20h
- dapp: 9h

#### Generalized Replay Bridge with Ethereum VM, IBC (Cosmos) & Evmos: 49h

- video Mar 13, 2022: [https://youtu.be/ayFzY4btFX4](https://youtu.be/ayFzY4btFX4)
- video script, recording, editing, publishing: 5h
- precompile programming: 40h
- dapp: 4h

#### Gas Refill Precompile - Prepay Ethereum VM transactions: 27h

- video Mar 19, 2022: [https://youtu.be/S9HLBwG6Ifo](https://youtu.be/S9HLBwG6Ifo)
- video script, recording, editing, publishing: 4h
- precompile programming: 20h
- dapp: 3h


## Proofs

1. The proof that the output of the effort exists as a public good: the videos exist and are public on YouTube, and the code exists and is public.
2. The proof that it is about the Evmos chain/tech: the code is used by Ethermint/Evmos.
3. The proof that the effort is of the quality and quantity claimed: Federico Kunze signed the confirmations for the effort, as a comment on [https://github.com/loredanacirstea/CV/issues/2](https://github.com/loredanacirstea/CV/issues/2), but he recently deleted that comment (he deleted all his public confirmations of my volunteering).
4. The proof that this chain accepts claims for retroactive public goods is [proposal 88](https://www.mintscan.io/evmos/proposals/88).

## Retroactive Payment

359.5h * 255 euro/h = 91,672.5 eur


## The Meaning of the Vote

1. If this proposal passes: the Evmos chain pays retroactively for this public good.
2. If this proposal does not pass: the Evmos chain recognizes in perpetuity this public good as a volunteering effort of The Laurel Project in the interest of the Evmos Community. (or is bound to produce counter-proofs to the ones above)

## Author

Loredana Cirstea, volunteer for The Laurel Project.

