# Effort Evaluation

```mermaid

graph TD
    A[Claim of Effort Made] --> B{Does the Output Exist?}
    B -->|No| Z[Done]
    B --> |Yes| C{Is the Output Useful?}
    C -->|Yes| D{Is the Effort Attributable to Claimant?}
    C -->|No| Z[Done]
    D -->|No| E[Modify the Claimant]
    D -->|Yes| F{Is the Effort in the claimed quality and quantity?}
    E -->D
    F -->|No| G[Modify quantity/quality of Effort]
    F -->|Yes| H{Decide to pay for it or not}
    H -->|No| I[Recognize it as a volunteer effort]
    H -->|Yes| J[Pay and Recognize it as a for-profit effort]
    J -->Z
    I -->Z
    G -->F
    

```
### Role of The Laurel Foundation

The Laurel Project is not a charity. The volunteers are not charity workers. If their volunteering effort is not recognized at any point in future as such: the volunteers deserve to be repaid for their efforts.
The Laurel Foundation is offering legal services to The Laurel Project and any other volunteer organizations that are deemed to qualify. The Foundation will defend the legal and moral rights of the volunteers.
In the event of volunteer work being unrecognized or discontinued from recognition, The Laurel Foundation will sue the offending parties for repayment or for slander.

```mermaid

graph TD
    A[Recognize it as Volunteer Effort] --> B{Discontinue Recognition?}
    B -->|No| Z[Done]
    B --> |Yes| B2[Recalculate payment at present value or payment with interest: whichever is bigger]
    B2 --> C{Pay now?}

    C -->|No| K[You will be sued by The Laurel Foundation]
    K -->L{You loose the case?}
    L -->|Yes| M[Pay legal fees]
    M -->A
    L -->|No| P[The Laurel Foundation pays legal fees and records the outcome on-chain]
    P -->Z


    C -->|Yes| J[Pay and Recognize it as a for-profit effort]
    J -->Z[Done]
  
    


```
