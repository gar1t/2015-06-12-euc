# But Will It Scale?

---

## Alternatively

- Build It
- Deploy It
- Observe It
- Fix It

---

# Gee Thanks

---

## Scalable → _Awesome_

---

# More fun!

---

- Myth Of Scalability
- Scalability Obsession
- Anti Patterns

---

# The Myth Of Scalability

---

# Outages

---

<img src="twitter.jpg" height="100%">

---

<img src="amazon.png" width="100%">

---

<img src="ebay.png" width="100%">

---

# Read about it!

---

# Nothing Scales

---

# <strike>Scalable</strike> Awesome!

---

# <strike>Scalable</strike> Suitable

---

<img src="cheetah.jpg" height="640px">

---

<img src="springbok.jpg" height="640px">

---

<img src="blackberries.jpg" height="640px">

---

<img src="turtle.jpg" height="640px">

---

<img src="alligator-vs-turtle.jpg" height="640px">

---

<div style="position:relative;width:100%">
<img src="joe.jpg" style="width:100%">
<blockquote style="position:absolute;top:100px;left:50px;width:45%;opacity:0.7;">
<dl>
<dt>There’s no such thing as fast, only fast enough.</dt>
<dd>— Joe Armstrong, Inventor of Erlang</dd>
</dl>
</blockquote>
</img>
</div>

---

# Optimization Fixation

---

<img src="olympics.jpg" height="640px">

---

<img src="hunters.jpg" height="640px">

---

<!--

## Nature's Caprice

<img src="peahen.jpg" height="550px">

---

## Nature's Caprice

<img src="peacock.jpg" height="550px">

---

## Mate Selection Programming

---

-->

## Scalability Anti Patterns

- Not a Problem
- Build It Naive
- Dependencies Bad
- Think "System"
- Physics Not Magic

---

# Not A Problem

---

# Not A Problem... Right Now

---

# Build It Naive

---

## The Unclever Approach

- Obvious, line-of-sight
- Usually works
- Often works forever
- Cheap
- Gets you to the actual problems

---

## Pointy Hair Argument

- Cost of work is _almost always_ under estimated
- Value of work is _often_ over estimated
- Keep work as small as possible, improve incrementally

---

# Dependencies Bad

---

## Down, but how?

---

<img src="xml.png" width="100%">

---

<img src="xml-highlight.png" width="100%">

---

<!--
## Dependencies

- Moving part = part + interactions
- Part = tree of parts
- Parts you use can hurt you
- Parts you don't use can hurt you

---
-->

## Fight Dependencies

- Make due with what you have
- Fight each dependency until it overwhelms you
- When forced to give in, do it bitterly

---

# Think "System"

---

## Independencies

- Boundaries in time and space
- Not source code abstractions
- Some language cultures embrace "system", others do not

---

# Physics Not Magic

---

### Approximate Latencies

```
L1 cache reference                            0.5 ns
Branch mispredict                             5   ns
L2 cache reference                            7   ns
Mutex lock/unlock                            25   ns
Main memory reference                       100   ns
Compress 1K bytes with Zippy              3,000   ns
Send 1K bytes over 1 Gbps network        10,000   ns
Read 4K randomly from SSD*              150,000   ns
Read 1 MB sequentially from memory      250,000   ns
Round trip within same datacenter       500,000   ns
Read 1 MB sequentially from SSD*      1,000,000   ns
Disk seek                            10,000,000   ns
Read 1 MB sequentially from disk     20,000,000   ns
Send packet CA->Netherlands->CA     150,000,000   ns
```

---

## Buy These!

<img src="raspberrypi.jpg" height="350" style="float:left">
<img src="odroid.jpg" height="350" style="float:right">

---

## Build This!

<img src="cluster.jpg" height="550">

---

# Final Thoughts

---

# Scalable

---

# Awesome!

---

# Suitable

---

# Evolvable

---

# Discussion

### Yell at me on Twitter!
## @gar1t
