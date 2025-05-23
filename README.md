# Web3 Interoperability: Bridge Analysis & Design

## Instructions

1. Analyze the most relevant web3 bridges. For each, compare each of the following:
    - Security
    - Decentralization
    - Trust assumptions

2. Design:
    - How would you design an ideal bridge from scratch in a world where gas is free?
    - How would you design a bridge from scratch in a world where gas is extremely expensive (in L1 only)?

3. Modeling:
    - Cost of attacking a bridge with minting rights and the potential profit for the attacker.

## Clarification on Trust Assumptions

Along this document, certain trust assumptions are considered common to all bridges given the nature of the systems we are working with. These are:

- Source and target domain consensus mechanisms (trust-minimized).
- Extremely unlikely security leaks in the software (protocol contracts, node implementations, etc.).
- Correctness of signature creation and verification systems.

## Context

This [document](./document.md) was created as part of a technical challenge for a Blockchain Researcher position.

The time dedicated to this work was ~3.5 days of full-time effort, with ~1 of a pure research phase and the remaining time spent combining research with document elaboration.

## Resources

[Not exhaustive list]

- ["Understanding Blockchain Bridges: the Key to Interoperability in Web3" by Hiro](https://www.hiro.so/blog/understanding-blockchain-bridges-a-key-to-interoperability-in-web3)
- ["Bridges" by ethereum.org](https://ethereum.org/en/developers/docs/bridges/)
- ["The Interoperability Trilemma" by Arjun Bhuptani](https://medium.com/connext/the-interoperability-trilemma-657c2cf69f17)
- ["Why the future will be multi-chain, but it will not be cross-chain" by Vitalik](https://old.reddit.com/r/ethereum/comments/rwojtk/ama_we_are_the_efs_research_team_pt_7_07_january/hrngyk8/)
- [REKT Leaderboard](https://rekt.news/leaderboard/)
- [DefiLlama Bridges](https://defillama.com/bridges)
- [L2Beat Bridges](https://l2beat.com/bridges/summary)
- [Wormhole Official Docs](https://wormhole.com/docs/)
- [IBC Official Docs](https://tutorials.cosmos.network/academy/3-ibc/1-what-is-ibc.html)
- [Hop Official Docs](https://docs.hop.exchange/)
- [Hop V1 Whitepaper](https://hop.exchange/whitepaper.pdf)
- ["Introducing Everclear: The First Clearing Layer" by Arjun Bhuptani](https://medium.com/everclear/introducing-everclear-the-first-clearing-layer-b8d6e1d78ca1)

## Disclaimer

This was a timeboxed effort, and some elaborations were set aside to prioritize creating a complete and deliverable version of the document. Some of the nice-to-have elaborations that were omitted are:

- Diagrams illustrating the architecture and functionality of the analyzed bridges.
- Greater detail and thoroughness in the descriptions of analyzed bridges' protocols.