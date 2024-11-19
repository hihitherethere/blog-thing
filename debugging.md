---
layout: post
title: "Debugging"
---

### Debugging pains

#### TLE
* Big constants
  * Replace vector<int> with pair<int, int>
  * set.distance() is O(n)
  * Reading floats is super slow
  * Overflow/floats make code slow
* Binary search slow point
* Use unordered_map instead of map