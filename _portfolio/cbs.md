---
title: "Improvements on Conflict-Based Search for Multi-Agent Path Finding"
excerpt: ""
collection: portfolio
---

* Symmetry-Breaking Constraints for Grid-Based Multi-Agent Path Finding <br/>
<img src='/images/rectangle.png'> <br/> 
We describe a new way of reasoning about symmetric collisions for Multi-Agent Path Finding (MAPF) on 4-neighbor grids. We also introduce a symmetry-breaking constraint to resolve these conflicts. This specialized technique allows us to identify and eliminate, in a single step, all permutations of two currently assigned but incompatible paths. Each such permutation
has exactly the same cost as a current path, and each one results in a new collision between the same two agents. We show that the addition of symmetry-breaking techniques can lead to an exponential reduction in the size of the search space of CBS, a popular framework for MAPF, and report significant improvements in both runtime and success rate versus CBSH and EPEA* – two recent and state-of-the-art
MAPF algorithms.
