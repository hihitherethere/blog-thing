---
layout: post
title: "My Strategy"
---

### how to better faster

#### Pattern Finding
* Scale problem down
  * Small cases
  * Edge cases
* Invariants/Monovariants
  * Euclidean algorithm if $f(p,q) = f(q,p)$ and $f(p,q) = f(p-q, q)$
  * Is something always true?
  * What relationship does the ending state have with the initial conditions?
  * How does changing initial conditions affect the ending?
  * Take mod something
  * Invariants on only a subset of things
* Repeating states
  * Bash out first few terms
  * Does it blow up or does it stay small?
  * If it stays small, does it ever repeat?