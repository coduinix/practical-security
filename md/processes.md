# Processes
<img class='stretch' src='images/pexels/camera-car-connection-924676.jpg'/>

===

## Threat model

vvv

### Threat agents
* Who could it be?
* What are they looking for?
  * Money
  * Data
  * Stepping stone

Note:
* Script kiddies
* Professional Hackers, just for:
  * the money
  * data
* Hacktivists, because they care about environment
* Nation states
* Competing companies
* Stepping stone: supply chains
* Just bad luck :(

vvv

### Attack vectors
* Type of vulnerabilities that would give access
* Rank them by impact and likelihood (risk)

Note:
* Pretend there are no countermeasures yet
* Ranking relative to each other

vvv

### Countermeasures
* Risk order
* Input for design

vvv

### Document
* Keep it for future reference
* Adjust with new insights

vvv

### Collaborative effort
* Stakeholders
* DevOps team
* Security specialist

Note:
* Shared awareness
* Stakeholders provide input and learn the importance
* DevOps gets understanding of the (threat) landscape
* Security specialist help identifying vulnerabilities and scenarios

vvv

### Methodologies
* A lot on the web
* Can start lightweight: Threat Modelling Express 

===

## Design reviews

Note:
* With focus on security 

vvv

### Authentication and authorization
* Mechanisms
  * Username password
  * Tokens
  * MFA
* Role-based access

vvv

### Data
* Which data needs to be stored
* Where is it stored
* Encryption

Note:
* Does it contain sensitive data
* How sensitive is it
* Could you store it in the cloud?
* Do you need encryption? What type?

vvv

> Most secure way to store data is to NOT store the data


vvv

### Communication
* Which systems
* Transport-level security

Note:
* Don't connect with systems when not necessary
* Each node could be a potential stepping stone

===

## Monitor

vvv

### Identity & monitor 
* Identify critical parts of codebase
* Monitor
* Notify
  
Note:
* Critical parts like:
  * Authentication filters
  * Authorization filters
* Preferably automated

vvv

### Notify vs block
* No manual security approval for every change
* Notify if interesting things happen
* Trigger for discussion

Note:
* Typical reaction should be to trigger discussion
* Only block when obviously dangerous
* Interesting things:
  * Authentication/Authorization comp
  * New use of encryption or hashing