
# Practical Security

<div align="right">- Hinse ter Schuur</div>

===

## Who doesn't like cookies
<img class='stretch' src='/images/pixabay/cookie-3790631_1280.jpg'/>

Note:
* Don't put cookies on the kitchen counter
* Better put in cupboard
* Lock on cupboard door?
  * Where to put key? 
* Put in safe?
  * How to handle access code?
  * Rotate secret?
  * Add biometric means

vvv

### A bit overkill?
<img class='stretch' src='/images/pixabay/safe-913452_1280.jpg'/>

Note:
* This is overkill
* What is the sweetspot?
* Depend on the environment
* How to keep it practical

===

## Who am I?
```json
{
  "name": "Hinse ter Schuur",
  "role": "Developer",
  "company": "SDB Java",
  "expertise": ["Java", "Scala", "Security"]
}
```

Note:
* I'm a DEV engineer
* Which happens to like security stuff
* Not a security engineer

===

## Disclaimer 
> This presentation represent my personal opinion based on things I've seen in different companies and on blogs & videos on the web...

vvv

### Disclaimer (1)
> ... It's not a complete approach, just things which I think could contribute to a practical approach to security.

===

## DevOps
<img class='stretch' src='/images/pixabay/server-1235959_1280.jpg'/>

Note:
* Combine software development and operations
* Not all companies do DevOps
* A lot do
* One of the goals: eliminate handover and distinct responsibilities

vvv

### Deployments
* From couple of times per year

to

* Multiple times per day

Note:
* Continuous deployment 
* How do we make sure our apps and landscape are secure?
* We can't have the traditional tollgate which is called 'Security'

vvv

### DevSecOps / SecDevOps
* Incorporate security in the DevOps way of working
* Security first?

Note:
* As developer I know that naming is hard
* In this case I don't think it's in the name, it's about making it work
* Security first sounds good
* And how about business... and testing? (see next)

vvv

### BizArchSecDevTestOps? 
<!-- .element: class="no-caps" -->

Note:
* Before you know it looks like 'waterfall' process in one camelcased
* Lets focus on Security today and less on naming

vvv

### No Silver Bullet
* People
* Processes
* Tools

Note:
* Integrate in whole software development lifecycle
* Touches people, processes, tools