# Tools

===

## Dependency scanning

vvv

### Dependencies
* Direct and indirect dependencies
* Do you trust _all_ the dependencies?
  * Should you?

Note:
* 25% direct dependencies
* 75% indirect dependencies

vvv

### Scan
* Known vulnerabilities
* Build time
* Keep scanning after deployment

vvv

### Trustworthiness
* Check central repos on:
  * Usage/downloads
  * Update frequency
  
vvv

### For example
* OWASP dependency checker
* **TODO** Screenshot report

Note:
* There are some tools around
* Most common one I've seen

===

## Code analysis

vvv

### Static code scanning
* Scan application code
* Could range from:
  * Simple regex
    to
  * Advanced code path analysis

Note:
* SQL injection
* Use of `System.exec`
* Weak encryption
* Potentially leaking information (returning env vars)
* Costs vary a lot

vvv

### When to scan
* Developers machine
* Build pipeline
* At least regular

vvv

### Alerting
* Start simple
* Few false positives
* Priorities based on threat model

Note:
* Start simple with things that can be detected nicely
* Prevent alert fatigue
* No false positives

vvv

### For example
* FindSecurityBugs
* **TODO** Screenshot report

===

## Dynamic scanning
* PEN-test
* Bug bounty


Note:
* Everything TLS with good cyphers

Note:


===

## Select / provide libraries
* Make it easy to do things secure
* Select hardened frameworks
* Provide secure libraries

Note: