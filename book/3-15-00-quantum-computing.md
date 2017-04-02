<ol class="breadcrumb">
  <li><a href="/">Home</a></li>
  <li><a href="/book/">Book</a></li>
  <li><a href="/book/3-00-00-overview/">Part Three: Lisp So(u)rcery</a></li>
  <li class="active">Quantum Computing</li>
</ol>

## Chapter 3.15

# Quantum Computing

> "Who taught me that the world is not only stranger than we imagine but stranger than we <em>can</em> imagine? Who has already taken me into two universes that are <em>not</em> this one... and brought me safely home?"
> <footer>Robert A. Heinlein, <em>The Number of the Beast</em></footer>

Quantum Computing is built on functional programming.  Since the release of Selinger's seminal paper on the Quantum Lambda Calculus in 2007, the progress within the field shifted suddenly from puttering along like the earliest steam-engines, to a rocket blasting off into space; and along with it, the *circuit* model of quantum computation, that reformulates the gate model in terms of the actual quantum circuits that would be needed to build these gates, has allowed for concise expression and simulation of quantum hardware in a classical computer program.

Meanwhile, a team in Vancouver was working on another model of quantum computation, that utilized quantum annealing on a chimera graph of superconducting flux qubits to solve *energy problems*; this work resulted in the first commercial adiabatic quantum computer, the D-Wave One, purpose-built for solving computationally expensive optimization problems efficiently. And its operating system was written entirely in Common Lisp, compiled with SBCL.  We are now on the eve of the release of the D-Wave Three, built on the Washington adiabatic processor---giving quantum hackers a full 2,048 physical qubits to play with.  With recent announcements from Google, and a handfull of VC-funded startups all announcing their upcoming quantum hardware, it is an exciting time in quantum computing---particularly for Lisp Hackers.

Naturally, there are limitations to what can be simulated on a classical computer; on a quad-core processor with hyperthreading, the most you can simulate in realtime is a 4-qubit system---anything more than this has to be time-lagged to compensate for the inherent limitations of classical computing.  As the number of qubits grows, the number of simultaneous operations computable in a quantum system grows exponentially---and very quickly you get to a hard wall, where a quantum algorithm is no longer computable on classical hardware within the estimated lifespan of the universe.  This problem can be mitigated by simply adding more classical cores, such as is done when building supercomputer labs, but this is extremely inefficient and expensive. When running quantum algorithms, you need to be able to exploit the quantum phenomena directly, to get meaningful and timely results.

That being said, time on D-Wave hardware is not exactly available to the general public; and the institutions which have made time available on the D-Wave One and Two to researchers and specialists are completely booked up.  At present, the average Lisp Hacker with an interest in quantum computer programming has no means to test any quantum algorithms they may write---and this is a problem.  Quantum Computing is the future of computing as a whole, so it needs to be accessible to everyone with an interest in it.

With that aim in mind, in this chapter we will review the basic theory of quantum computing, including important phenomena such as superposition of states, entanglement, teleportation, and various models of quantum computing such as the Gate Model, the Circuit Model, the Adiabatic Model, and Quantum Turing Machines; the programming paradigms needed and used, such as quantum energy programming and the quantum lambda calculus; and write basic simulators in Common Lisp for the different models of quantum computers that are either being built or already commercially available, forcefully time-lagged to simulate superpositioning, and time-limited to the maximum number of qubits that can be handled by your system within a customizeable unit of classical computer time in seconds.

Additional material for specialization in Quantum Computer Science will be listed under the Resources section of this site.

## Exercise 3.15.1

**The Qubit**

```lisp

```

## Exercise 3.15.2

**State Preparation**

```lisp

```

## Exercise 3.15.3

**Measurement**

```lisp

```

## Exercise 3.15.4

**Probability and Superposition**

```lisp

```

## Exercise 3.15.5

**Entanglement**

```lisp

```

## Exercise 3.15.6

**Quantum Registers**

```lisp

```

## Exercise 3.15.7

**Quantum Gates**

```lisp

```

## Exercise 3.15.8

**The Hadamard Gate**

```lisp

```

## Exercise 3.15.9

**The CNOT Gate**

```lisp

```

## Exercise 3.15.10

**Single-Qubit T-Gates**

```lisp

```

## Exercise 3.15.11

**Additional Quantum Gates**

```lisp

```

## Exercise 3.15.12

**Quantum Memory**

Storing Unmeasured Quantum States

```lisp

```

## Exercise 3.15.13

**Universal Quantum Computers**

Quantum Turing Completeness

```lisp

```

## Exercise 3.15.14

**Outputting Circuit Diagrams with LaTeX**

```lisp

```

## Project 3.15.15

**A Quantum Computer Simulator**

```lisp

```

<ul class="pager">
  <li class="previous"><a href="/book/3-14-00-computational-physics.md">&laquo; Previous</a></li>
  <li><a href="/book/">Table of Contents</a></li>
  <li class="next"><a href="/book/3-16-00-nlp.md">Next &raquo;</a><li>
</ul>
