# Processes
<img class='stretch' src='/images/pexels/camera-car-connection-924676.jpg'/>

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
* Hacktivists
* Nation states
* Competing companies

vvv

### Attack vectors
* Type of vulnerabilities that would give access
* Rank them by impact and likelihood (risk)

Note:
* Pretend there are no countermeasures yet
* Ranking relative to each other

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
  <small>https://www.infoq.com/articles/threat-modeling-express/</small> 

===

## Design reviews

vvv

### Authentication and authorization
* Mechanisms
  * Username password
  * Tokens
  * MFA
* Role-based access

vvv

### Data
* Which data is stored
* 

Note:
* Not storing data is more secure than NOT storing

vvv

### Communication
* Which systems communicate with each other


Note:
* 

===

## Identify & monitor critical parts
<!-- TODO: improve --> 
* Don't require manual security approval for every change
* Identify & monitor critical parts of codebase
  * Authentication filters
  * Authorization filters
