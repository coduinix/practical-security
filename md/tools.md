# Tools
<img class='stretch' src='images/pixabay/tools-1209764_1280.jpg'/>

===

## Static scanning

Note:
* whitebox (access to all sources)

vvv

### Code scanning
* Scan application code
* Could range from:
  * Simple regex
    to
  * Advanced code path analysis

Note:
* Most close to developers
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

### Alerting/blocking
* Start simple
* Few false positives
* Priorities from threat model

Note:
* These should block (in contrast to logical changes in monitoring)
* don't go wild with all rules on
* Start simple with things that can be detected nicely
* Prevent alert fatigue
* No false positives

vvv

### For example
* Find Security Bugs

<img class='stretch' src='images/find-security-bugs.png'/>

Note:
* Is a plugin for SpotBugs fomerly known as FindBugs

===

## Dependency scanning

vvv

### Dependencies
<img class='stretch' src='images/dependencies.png'/>


Note:
* 25% direct dependencies
* 75% indirect dependencies
* Should you trust the maintainers?
  * Just engineers like you and me
  * Not security specialists

vvv

### Scan
* Known vulnerabilities
* Build time
* Keep scanning after deployment

vvv

### For example
* OWASP dependency checker

<img class='stretch' src='images/dependency-check.png'/>


Note:
* There are some tools around
* Most common one I've seen
* Probably more on that in Marten's talk

vvv

### Trustworthiness
* Check central repos on:
  * Usage/downloads
  * Update frequency

===

## Dynamic scanning

Note:
* scan against a running application
* covers more infra-like and some application parts
* more or less black-box

vvv

### Automated
* TLS
* Security HTTP headers

Note:
* Everything TLS with good cyphers
* require important HTTP headers
  * No wildcard for CSP
* Probably more on that in Marten's talk

vvv

### Manual
* PEN-test
* Bug bounty

Note:
* It's a tool, but not automated
  * There are tools for this.
* PEN test zoom in on specific elements
  * Set of endpoints
  * Specific vulnerability
* Bug bounty
  * invite hackers to break your app, pay them when they succeed
  * broad coverage
* These are complementary
  
===

## Select / provide libraries
* Make it easy to do things secure
* Select hardened frameworks
* Provide secure libraries

Note:
