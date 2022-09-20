# Evmos Academic Projects

## Blockchain Classification System [BCS]

Our chain owes its very existence to previous research and implementation:

- Bitcoin
- Ethereum
- Cosmos SDK
- Ethermint

Even presently: most research is done by a handful of projects (See [ETH Research](https://ethresear.ch/)), and most other communities and derived chains benefit as freeloaders.

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

- [Computing Classification System](https://raw.githubusercontent.com/SubjectRaw/SubjectRaw/gh-pages/subject/data/eng/computing.md) in MD format
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

Each of these domains of knowledge has its own classification graph. If that graph has a node related to Blockchain, that node has to be presented in the BCS.

### Implementation

As in any SKOS system, we can opt for a flexible RDF triples database for information persistence that is further linked with the official classifications graphs (such as those referred to in the previous section) in such a way that the web2 and/or web3 navigation can access the actual research papers that are hosted on sites like https://arxiv.org/
That means a full-text search for the (labels of the) nodes in the database.

### Funding Items

Those are in the ascending order of expected value:
- hosting a database with good indexing for full-text search: maybe a distributed PostgreSQL-like
- hosting 2 websites (one for the research graph and one for discussions)
- creating the site for discussions with the academic interest of Evmos, Ethermint, and Cosmos SDK as core (same model as https://ethereum-magicians.org/)
- creating a web service that is able to add, modify, search, dump data, interface with https://arxiv.org/, maybe even with Semantic Web
- expertise in data creation:
  - additions/modifications to the RDF graph (knowledge domain linking with already-accepted terminologies and classifications)
  - motivation for peer review entries of new research
  - linking each paper also to public discussions
  - proposing papers for blockchain developers and communities for implementation or financial support

### Management

To start this project, Christian Tzurcanu (the author of this proposal), will work as a volunteer tasked from The Laurel Project in the interest and for the honor and fame of the Evmos Community. He will maintain the transparency of accounting on [this GitHub page](BCS_Accounting.md).
Therefore, the management will be free of payment and with provable results.

### Discussion

This discussion will not be included on-chain, but will be referenced in the on-chain text. It has these main directions: 

- improvements to the proposal text to arrive at its final (on-chain) form
- price discovery of the first useable version
- the initial list of domain experts or teams willing to participate in this first version
- additional ideas, improvements of the end product
