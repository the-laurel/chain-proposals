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
  discussion
 }
 link Grammar And Syntax Tree "https://commonwealth.im/evmos/discussion/6690-metameta-english-grammar-and-syntax-tree" 
 
 class  Words And Concepts {
  discussion
 }
 link Words And Concepts "https://commonwealth.im/evmos/discussion/6610-metameta-consensus-on-words-and-concepts" 

 class  Language Limitations {
  discussion
 }
 link Language Limitations "https://commonwealth.im/evmos/discussion/6690-metameta-english-grammar-and-syntax-tree" 
 
class  Precedence Rules {
  discussion
 }
 link Precedence Rules "https://commonwealth.im/evmos/discussion/6711-metameta-precedence-rules" 
 
class Governance Infrastructure {
  discussion
}
link Governance Infrastructure "https://commonwealth.im/evmos/discussion/6708-metameta-governance-infrastructure" 

class Naming And Versioning {
  discussion
}
link Naming And Versioning "https://commonwealth.im/evmos/discussion/6710-metameta-naming-and-versioning" 

class Technical Limitations {
  discussion
}
link Technical Limitations "https://commonwealth.im/evmos/discussion/6712-metameta-basic-rules" 


Language Limitations <|-- Words And Concepts
Language Limitations <|-- Grammar And Syntax Tree
Naming And Versioning <|-- Language Limitations
Naming And Versioning <|-- Governance Infrastructure
Technical Limitations <|-- Naming And Versioning
Technical Limitations <|-- Precedence Rules


```

## Principles

```mermaid
classDiagram

class The Principle Of Reflexivity  {
  created
}
link The Principle Of Reflexivity "https://github.com/the-laurel/chain-proposals/blob/main/evmos/PrincipleOfReflexivity.md" 

class The Principle Of Identity  {
  created
}
link The Principle Of Identity "https://github.com/the-laurel/chain-proposals/blob/main/evmos/PrincipleOfIdentity.md" 

class The Principle Of Transformation  {
  created
}
link The Principle Of Transformation "https://github.com/the-laurel/chain-proposals/blob/main/evmos/PrincipleOfTransformation.md" 

class Existence Of Principles {
  created
}
link Existence Of Principles "https://github.com/the-laurel/chain-proposals/blob/main/evmos/ExistenceOfPrinciples.md" 

class The Principle Of Integrity {
  created
}
link The Principle Of Integrity "https://github.com/the-laurel/chain-proposals/blob/main/evmos/PrincipleOfIntegrity.md"

class The Principle Of Rationality {
  created
}
link The Principle Of Rationality "https://github.com/the-laurel/chain-proposals/blob/main/evmos/PrincipleOfRationality.md" 

The Principle Of Integrity  <|-- The Principle Of Transformation
The Principle Of Integrity  <|-- The Principle Of Reflexivity

The Principle Of Identity  <|-- Existence Of Principles 
The Principle Of Transformation <|-- Existence Of Principles 
The Principle Of Reflexivity <|-- Existence Of Principles 
The Principle Of Rationality <|-- Existence Of Principles

Existence Of Principles <|-- Technical Limitations



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


```
