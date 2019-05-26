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
* Which data needs to be stored
* Where is it stored
* Encryption

Note:
* Does it contain sensitive data
* How sensitive is it
* Could you store it in the cloud?
* Do you need encryption? What type?
* Not storing data is more secure than NOT storing

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
* Identify & monitor critical parts of codebase, e.g.
  * Authentication filters
  * Authorization filters

vvv

### Prefer notify over blocking
* No manual security approval for every change
* Notify if interesting things happen
  * Authentication/Authorization comp
  * New use of encryption or hashing
* Trigger for discussion

Note:
* Typical reaction should be to trigger discussion
* Only block when obviously dangerous