# Precedence Graph

## Trusted Circles


```mermaid
classDiagram

class Tgrade Constitution {
  created
}
link Tgrade Constitution "https://github.com/Ocean-Blue-Foundation/resources.tgrade.finance/blob/master/Tgrade%20Constitution.pdf" 



Tgrade Constitution <|-- Trusted Circles Constitution 
Trusted Circles Constitution <|-- Constitutional Framework
Primary Trusted Circle1 Constitution <|-- Trusted Circles Constitution 
Primary Trusted Circle2 Constitution <|-- Trusted Circles Constitution 
Primary Trusted Circle3 Constitution <|-- Trusted Circles Constitution 
Trusted Circle102 Constitution <|-- Primary Trusted Circle1 Constitution 
Trusted Circle102 Constitution <|-- Primary Trusted Circle2 Constitution 

Proposal 1 <|-- Trusted Circle102 Constitution
Proposal 2 <|-- Trusted Circle102 Constitution

Proposal 01 <|-- Tgrade Constitution
Proposal 02 <|-- Tgrade Constitution


```
