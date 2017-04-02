<ol class="breadcrumb">
  <li><a href="/">Home</a></li>
  <li><a href="/book/">Book</a></li>
  <li><a href="/book/3-00-00-overview/">Part Three: Lisp So(u)rcery</a></li>
  <li class="active">Space-Tech</li>
</ol>

## Chapter 3.19

# Space-Tech

> "People don't really want change, any change at all... But we progress, as we must---if we are to go out to the stars."
> <footer>Robert A. Heinlein, <em>Double Star</em></footer>

All software has bugs in it---it's just a part of life in a technologically-driven society---but not all bugs are actual mistakes, per se. Sometimes they can be no more than an application of the wrong algorithm to a given problem, which provides an apparently correct answer, say, 99% of the time, but then produces something completely wrong in that last 1% of the cases.  Here, on Earth, bugs in software can cause significant problems as it is, which is why so much time and effort is spent on QA and software updates; but imagine how much trouble a bug could be in a Probe, Satellite, or Space-Craft, where a technical support and development team can't directly access the hardware, and in dealing with the vast distances of space, have so much lag between any event, the notification of it, and the hardware getting the updated code.

Traditional software development lifecycles and technologies are inherently at a disadvantage in Space Tech, an industry where you can't afford to make any mistakes.  One of the most important features needed in any space-based platform is the ability to immediately get inside the running application, identify a bug and fix it while the application is running.  *Lisp was designed to do this*.  And certainly, NASA validated this point quite strongly with Deep Space 1 and the Remote Agent Experiment (RAX).

Now, imagine the relative convenience of a space-craft where all the systems are programmed in Lisp, and are thus live hackable; astronauts are already highly trained, highly intelligent and resourceful individuals who can cope with the stresses of life in space---and it would not be much of a stretch to add programming in Lisp to their list of necessary skills.  If they had the option to control all systems from a REPL, extend, test, and fix mission critical software interactively, on an as-needed basis, they would be significantly better equipped to handle any of the many issues that can arise in space, in a much more timely fashion than mission control on Earth can respond.  Those precious seconds of lag in communication between Earth and a space-craft can mean the difference between mission failure and success.

Space Tech is a complex field of interrelated, specialized disciplines---and inevitably, after a cursory introduction to the field as a whole in an undergraduate program, students are expected to focus on one of the many specializations, such as astrophysics, propulsion, aerospace engineering, communications, etc.  But it is advantageous to have a big picture, wide-view of the field before choosing a specialization.

In this chapter, we will explore a very high-level overview of a selection of the topics in the field of Space Tech, namely astrophysics, microgravity, properties of vacuums and near-vacuums, propulsion, aerospace engineering, and communication; design idealized model satellites and probes, integrating a basic AI that can be overridden by a controller on Earth; and implement an environment to simulate space-like conditions for testing these models.  And lastly, we will extend this text-based simulator to a 3D simulation, where you can see your model space-craft in action.

## Exercise 3.19.1

**Simulating Physics and Astrophysics**

```lisp

```

## Exercise 3.19.2

**Microgravity**

```lisp

```

## Exercise 3.19.3

**Vacuums and Near-Vacuums**

```lisp

```

## Exercise 3.19.4

**Orbits**

```lisp

```

## Exercise 3.19.5

**Simulating Space-Tech**

```lisp

```

## Exercise 3.19.6

**Basic Principles of Aerospace Engineering**

```lisp

```

## Exercise 3.19.7

**Propulsion**

```lisp

```

## Exercise 3.19.8

**Communication**

```lisp

```

## Exercise 3.19.9

**A Controller AI**

```lisp

```

## Exercise 3.19.10

**Unmanned Spacecraft**

```lisp

```

## Exercise 3.19.11

**Simulating Life-Support for Manned Spacecraft**

```lisp

```

## Exercise 3.19.12

**Live Hacking Mission-Critical Systems**

```lisp

```

## Project 3.19.13

**A 3D Space Simulator**

```lisp

```

<ul class="pager">
  <li class="previous"><a href="/book/3-18-00-robotics.md">&laquo; Previous</a></li>
  <li><a href="/book/">Table of Contents</a></li>
  <li class="next"><a href="/book/3-20-00-neurotech.md">Next &raquo;</a><li>
</ul>
