# Chapter 1: The Role of Algorithms in Computing

## 1.1 Algorithms 

### Definition of an Algorithm:
- An algorithm is a sequence of computational steps that transform the input into the output.
- The algorithm describes a specific computational procedure for achieving that input/output relationship for all problem instances.
- **An algorithm for a computational problem is correct if,**
  1. for every problem instance procided as input,
  2. it halts-finishes its computing in finite time.
  3. outputs the correct solution to te problem instance.
  4. Thus, A correct algorithms solves the given computational problem.

### What kinds of problems are sovled by algorithms?
- The Human Genome Project
- Finding good routes on which the data travles
- Electronic commerce
- Manufacturing and other commercial enterprises often need to allocate scarce resources in the most beneficial way.
- Determine the shortest route from one intersection to another.

### Data structures:**
- is a way to store and organise data in orser to facilitate access and modifications.
- Using the appropriate data structure or structures is an important part of algorithm design.

### Hard problmes
- No one knows whether efficient algorithms exist for **NP-Complete** problmes.
- NP-Complete problems has the remarkable property that if an efficient algorithm exists for any one of them, then efficient algorithms exist for all of them.
- Computer scientists are intrigued by how a small change to the problem statement can cause a big change to the efficiency of the best known algorithm.
- To reduce costs, the company wants to select an order of delivery stops that yields the lowest overall distance traveled by each truck. e.g.'traveling-salesperson problem, it is NP-complete

### Alternative computing models
- In order to perform more computations per second, therefore, chips are being designed to contain not just one but several processing 'cores'. We can liken these multicore computers to several sequential computers on a single chip. In other words, they are a type of 'parallel computer'.
- Algorithms that reveive their input over time, rather than having all the input present at the start, are **online algorithms**.

**Exercises**

**1.1-1**
Describe your own real-world example that requires sorting. Describe one that requires finding the shortest distance between two points

**Model Anser**: An example of a real world situation that would require sorintg would be if you wanted to keep track of a bunch of people's file folders and be able to look up a given name quickly. A convex hull might be needed if you needed to secure a wildlife sanctuary with fencing and had to contain a bunch of specific nesting locations.

**1.1-2**
Other than speed, what other mesures of efficiency might you need to consider in a real-world setting?

**1.1-3**
**1.1-4**
**1.1-5**
**1.1-6**

## 1.2 Algorithms as a technology

**Efficiency and Analysis:**
- An algorithms' efficiency is crucial, as it determines how well it scales with input size.
- Analysis focuses on both **time complexity**(speed) and **space complexity**(memory usage).

**Algorithms and Problems:**
- some problems are computationally hard(e.g., NP-complete), while others are solvable efficiently.
- Algorithms procide structure to problem-solving and help assess what is computable.

