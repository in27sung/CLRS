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

### Data structures:
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

## 1.2 Algorithms as a technology

### Efficiency:
- Different algorithms devised to solve the same problem often differ dramatically in their efficiency.
- An algorithms' efficiency is crucial, as it determines how well it scales with input size.
- Analysis focuses on both **time complexity**(speed) and **space complexity**(memory usage).
- In general, as the problem size increases, so does the relative advantage of efficient algorithms.

### Algorithms and other technologies:
- Total system performance depends on choosing efficient algorithms as much as on choosing fast hardware
  - advanced computer architectures and fabrication technologies,
  - eay-to-use, intutitive, graphical user interfaces (GUIs),
  - object-oriented systems,
  - integrated web technologies,
  - fast networking, both wired and wireless,
  - machine learning,
  - and mobile devices.
- An application that does not require algorithmic content at the application level relies heavily upon algorithms.
  - The hardware design used algorithms.
  - The design of any GUI relies on algorithms.
  - Routing in networks relies heavily on algorithms.
  - Then it was processed by a compiler, interpreter, or assembler, all of which make extensive use of algorithms.
- **Machine learning** can be thought of as a method for performing algorithmic tasks without explicitly designing an algorithm, but instead inferring pattens from data and thereby automatically learning a solution.
- **Data science** is an interdisciplinary field with the goal of extracting knowledge and insigts from strucured and unstructured data.
- It is at larger problem sizes that the differences in efficiency bewteen algorithms become particularly prominent.
- some problems are computationally hard(e.g., NP-complete), while others are solvable efficiently.
- Algorithms procide structure to problem-solving and help assess what is computable.
