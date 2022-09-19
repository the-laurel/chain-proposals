# Evmos Academic Projects

## Blockchain Classification System [BCS]

Our chain owes its very existence to previous research and implementation:

- Bitcoin
- Ethereum
- Cosmos SDK
- Ethermint

Even presently: most research is done by the Ethereum community and most other communities and chains benefit as freeloaders.

This situation is not morally acceptable. We should and we want to give back resources and a direction for research.

We suggest the creation of a classification system for the domain of knowledge of blockchain that is intuitive, simple to navigate, and able to attract resources and support for further research.

### Method

Given the root concept of "Blockchain Research", construct a SKOS graph (as free of internal loops as possible) that will have the research papers as nodes.

The system should be in version 1:

1. decentralized
2. searchable
3. data dump downloadable
4. linking at least to the most important papers

We should seek to also provide for the next versions:

- incentivized peer review
- incentivized maintenance

### Resources

We may find the following resources useful:

- [Computing Classification System](https://github.com/SubjectRaw/SubjectRaw/blob/gh-pages/subject/data/eng/computing.md) in MD format
- [Computing Classification System](https://dl.acm.org/pb-assets/dl_ccs/acm_ccs2012-1626988337597.xml) in XML SKOS format
- [An initial map of the blockchain knowledge](https://github.com/the-laurel/governance/blob/main/docs/StrategicLandscape.md)

### Start

Since the normal placement of blockchain tech is usually:

- everything knowable
...
  - Mathematics
    - Applied Mathematics
      - Computer Science
      ...
        - Decentralized Systems
          - Decentralized Ledger
            - Blockchain Technologies

But Blockchain tech has obvious relationships with governance, ethics, Economics, etc. So, when we put it at the root level, the immediate next level will have to be the linked Sciences (including Computer Science)

- Blockchain Technologies
  - Mathematics
  - Computer Science (deepest and most populated tree expected under this node)
  - Philosophy, Ethics
  - Economics
  - Sociology

Each of these domains of knowledge has their own classification graph. If that graph has a node related to Blockchain, that node has to be presented in the BCS.

### Implementation

As in any SKOS system, we can opt for a flexible RDF triples database for information persistence that is further linked with the official classifications graphs (such as those referred to in the previous section) in such a way that the web2 and/or web3 navigation can access the actual research papers that are hosted on sites like https://arxiv.org/


