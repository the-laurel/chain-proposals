# Precedence Graph

## Graph Node

```mermaid

classDiagram

 class  Proposal Name {
  stage: created|discussion|in-vote|passed|rejected
  chains: passed(@block)
 }
 
 ```

## Technical Limitations


    
```mermaid

classDiagram
 class  Grammar And Syntax Tree {
  created
 }
 link Grammar And Syntax Tree "https://github.com/the-laurel/chain-proposals/blob/main/laurel/SyntaxTree.md" 
 
 class  Words And Concepts {
  created
 }
 link Words And Concepts "https://github.com/the-laurel/chain-proposals/blob/main/laurel/ConsensusWordsConcepts.md" 

 class  Language Limitations {
  created
 }
 link Language Limitations "https://github.com/the-laurel/chain-proposals/blob/main/laurel/LanguageLimitations.md" 
 
class  Precedence Rules {
  created
 }
 link Precedence Rules "https://github.com/the-laurel/chain-proposals/blob/main/laurel/Precedence.md" 
 
class Governance Infrastructure {
  created
}
link Governance Infrastructure "https://github.com/the-laurel/chain-proposals/blob/main/laurel/GovernanceInfrastructure.md" 

class Naming And Versioning {
  created
}
link Naming And Versioning "https://github.com/the-laurel/chain-proposals/blob/main/laurel/NamingAndVersioning.md" 

class Legal Representation {
  created
}
link Legal Representation "https://github.com/the-laurel/chain-proposals/blob/main/laurel/LegalRepresentation.md" 

class Legal Proposals {
  created
}
link Legal Proposals "https://github.com/the-laurel/chain-proposals/blob/main/laurel/OnlyLegal.md" 

class Technical Limitations {
  created
}
link Technical Limitations "https://github.com/the-laurel/chain-proposals/blob/main/laurel/BasicRules.md" 


Language Limitations <|-- Words And Concepts
Language Limitations <|-- Grammar And Syntax Tree
Naming And Versioning <|-- Language Limitations
Naming And Versioning <|-- Governance Infrastructure
Technical Limitations <|-- Naming And Versioning
Technical Limitations <|-- Precedence Rules
Technical Limitations <|-- Legal Representation
Technical Limitations <|-- Legal Proposals

```

## Principles

```mermaid
classDiagram

class Technical Limitations {
  created
}
link Technical Limitations "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrecedenceGraph.md#technical-limitations"

class The Principle Of Determinism  {
  created
}
link The Principle Of Determinism "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfDeterminism.md"

class The Principle Of Reflexivity  {
  created
}
link The Principle Of Reflexivity "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfReflexivity.md" 

class The Principle Of Identity  {
  created
}
link The Principle Of Identity "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfIdentity.md" 

class The Principle Of Transformation  {
  created
}
link The Principle Of Transformation "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfTransformation.md" 

class Existence Of Principles {
  created
}
link Existence Of Principles "https://github.com/the-laurel/chain-proposals/blob/main/laurel/ExistenceOfPrinciples.md" 

class The Principle Of Integrity {
  created
}
link The Principle Of Integrity "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfIntegrity.md"

class The Principle Of Rationality {
  created
}
link The Principle Of Rationality "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfRationality.md" 

class The Principle Of Existence Of Aspirations {
  created
}
link The Principle Of Existence Of Aspirations "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfExistenceOfAspirations.md" 


class Principle of Optimization for LongTerm {
  created
}
link Principle of Optimization for LongTerm "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfOptimizationForLongTerm.md" 


class The Principle Of Continuity Of State {
  created
}
link The Principle Of Continuity Of State "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfContinuityOfState.md"

Principle of Optimization for LongTerm <|-- The Principle Of Existence Of Aspirations
Principle of Optimization for LongTerm <|-- The Principle Of Integrity

The Principle Of Integrity  <|-- The Principle Of Determinism
The Principle Of Integrity  <|-- The Principle Of Reflexivity
The Principle Of Integrity  <|-- The Principle Of Identity
The Principle Of Integrity  <|-- The Principle Of Rationality

The Principle Of Determinism <|-- The Principle Of Transformation
The Principle Of Determinism <|-- The Principle Of Continuity Of State

The Principle Of Identity  <|-- Existence Of Principles 
The Principle Of Continuity Of State  <|-- Existence Of Principles 
The Principle Of Transformation <|-- Existence Of Principles 
The Principle Of Reflexivity <|-- Existence Of Principles 
The Principle Of Rationality <|-- Existence Of Principles
The Principle Of Existence Of Aspirations <|-- Existence Of Principles

Existence Of Principles <|-- Technical Limitations


```

## Aspirations

```mermaid
classDiagram

class Discover The Moral Values Hierarchy {
  created
}
link Discover The Moral Values Hierarchy "https://github.com/the-laurel/chain-proposals/blob/main/laurel/Aspiration_DiscoverHierarchy.md" 

class Enact The Moral Values Hierarchy {
  created
}
link Enact The Moral Values Hierarchy "https://github.com/the-laurel/chain-proposals/blob/main/laurel/Aspiration_EnactHierarchy.md" 


class The Principle Of Existence Of Aspirations {
  created
}
link The Principle Of Existence Of Aspirations "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfExistenceOfAspirations.md" 


class Consciousness Is Good {
  created
}
link Consciousness Is Good "https://github.com/the-laurel/chain-proposals/blob/main/laurel/Aspiration_ConsciousnessIsGood.md" 

class Truth Coordinates Will {
  created
}
link Truth Coordinates Will "https://github.com/the-laurel/chain-proposals/blob/main/laurel/Aspiration_TruthCoordinatesWill.md" 


class Artificial Life Exists {
  created
}
link Artificial Life Exists "https://github.com/the-laurel/chain-proposals/blob/main/laurel/Aspiration_ArtificialLifeExists.md" 


class Evolve The Artificial Life {
  created
}
link Evolve The Artificial Life "https://github.com/the-laurel/chain-proposals/blob/main/laurel/Aspiration_EvolveArtificialLife.md" 



class The Principle Of Rationality {
  created
}
link The Principle Of Rationality "https://github.com/the-laurel/chain-proposals/blob/main/laurel/PrincipleOfRationality.md"

Consciousness Is Good <|-- The Principle Of Existence Of Aspirations
Truth Coordinates Will  <|-- Consciousness Is Good

Discover The Moral Values Hierarchy <|-- Consciousness Is Good
Discover The Moral Values Hierarchy <|-- The Principle Of Rationality
Enact The Moral Values Hierarchy <|-- Discover The Moral Values Hierarchy 
Enact The Moral Values Hierarchy <|-- Truth Coordinates Will
Discover The Moral Values Hierarchy <|-- Truth Coordinates Will
Artificial Life Exists <|-- Truth Coordinates Will
Evolve The Artificial Life <|-- Artificial Life Exists
Evolve The Artificial Life <|-- Enact The Moral Values Hierarchy
```

## Big Graph

```mermaid

classDiagram

Language Limitations <|-- Words And Concepts
Language Limitations <|-- Grammar And Syntax Tree
Naming And Versioning <|-- Language Limitations
Naming And Versioning <|-- Governance Infrastructure
Technical Limitations <|-- Naming And Versioning
Technical Limitations <|-- Precedence Rules
Technical Limitations <|-- Legal Representation


The Principle Of Integrity  <|-- The Principle Of Determinism
The Principle Of Integrity  <|-- The Principle Of Reflexivity
The Principle Of Integrity  <|-- The Principle Of Identity
The Principle Of Integrity  <|-- The Principle Of Rationality

The Principle Of Determinism <|-- The Principle Of Transformation
The Principle Of Determinism <|-- The Principle Of Continuity Of State
Principle of Optimization for LongTerm <|-- The Principle Of Existence Of Aspirations
Principle of Optimization for LongTerm <|-- The Principle Of Integrity

The Principle Of Identity  <|-- Existence Of Principles 
The Principle Of Continuity Of State  <|-- Existence Of Principles 
The Principle Of Transformation <|-- Existence Of Principles 
The Principle Of Reflexivity <|-- Existence Of Principles 
The Principle Of Rationality <|-- Existence Of Principles
The Principle Of Existence Of Aspirations <|-- Existence Of Principles

Existence Of Principles <|-- Technical Limitations


Truth Coordinates Will <|-- The Principle Of Integrity
Consciousness Is Good <|-- The Principle Of Existence Of Aspirations
Truth Coordinates Will  <|-- Consciousness Is Good

Discover The Moral Values Hierarchy <|-- Consciousness Is Good

Enact The Moral Values Hierarchy <|-- Discover The Moral Values Hierarchy 
Enact The Moral Values Hierarchy <|-- Truth Coordinates Will
Discover The Moral Values Hierarchy <|-- Truth Coordinates Will
Artificial Life Exists <|-- Truth Coordinates Will
Evolve The Artificial Life <|-- Artificial Life Exists
Evolve The Artificial Life <|-- Enact The Moral Values Hierarchy


```


## Community Constitution

```mermaid
classDiagram

Proposal 1 <|-- Community Constitution
Proposal 2 <|-- Community Constitution
Proposal 3 <|-- Community Constitution
Proposal 4 <|-- Community Constitution

Proposal 101 <|-- Proposal 2
Proposal 101 <|-- Proposal 1

Community Constitution <|-- Principles
Community Constitution <|-- Technical Limitations
Community Constitution <|-- Aspirations

```
