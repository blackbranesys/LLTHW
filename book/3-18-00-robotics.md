<ol class="breadcrumb">
  <li><a href="/">Home</a></li>
  <li><a href="/book/">Book</a></li>
  <li><a href="/book/3-00-00-overview/">Part Three: Lisp So(u)rcery</a></li>
  <li class="active">Robotics</li>
</ol>

## Chapter 3.18

# Robotics

> "Engineering is the art of the practical and depends more on the total state of the art than it does on the individual engineer."
> <footer>Robert A. Heinlein, <em>The Door Into Summer</em></footer>

**Note:** *the exercises in this chapter will require specialized hardware components to complete, and due to the prohibitive cost and lack of availability for some readers, it should be considered optional*.

To many people in the tech community, robotics is the ultimate expression of human innovation and ingenuity; and in many ways, the progress of the field is also a direct reflection of how well we understand ourselves as a species, as roboticists work towards an idealized simulacrum of the human form captured in engineering.  Humanoid robots are also, of course, a cornerstone of the Technological Singularity; and having this technology will redefine what it means to be human.  It combines so many disparate areas of research into a single, autonomous physical agent---at the very least, robotics is a technological marvel, but some day, once our computers rival the raw power of the human brain, and we are able to harness portable power supplies of sufficient output, they could also become new homes for our True Selves---our Minds.

At present, however, robotics is not nearly as advanced as we need it to be to achieve those goals---or advanced enough to give us any reason to fear robotics and the cynical science fiction trope of a robotic uprising.  Certain companies have been making great strides in the field, such as Boston Dynamics (recently acquired by Google); and we can be certain that for all the progress that has been made, that is public knowledge, there are likely even more impressive and terrifying classified military projects---but any ventures into that topic would be pure speculation.

What is of more interest is the vast selection of components that are already available to hobby roboticists, a very different situation from only two decades ago, when you would have to build nearly every component from scratch, even down to designing, assembling, and sautering your own logic control board.  Now you can buy all these components, logic boards, servos, sensors, and more, to design, build, and program your own robots in a fraction of the time it used to take.  This allows you to put more time and energy into programming the AI of your robot, up to the computational limits of the platform.

Programming in general is a highly satisfying career choice, as there is nothing quite like the feeling of building something that people need and want to use every day; but taking the next step, programming a robot, and watching it move around on its own, learning and adapting, is orders of magnitude greater.  A certain part of you can't help but feel like Dr. Frankenstein, laughing maniacally as you bring life to the inanimate---but that feeling is overwhelmed by an even greater wonder at the marvels of science and engineering, that awakens your inner child.

In this chapter, we will review the field of robotics, AI-controlled automatons, and learning algorithms; suppliers for components and robot kits; write a library to allow us to program a kit robot in Common Lisp; extend this library with an architecture to support intent-based motion; and finally, integrate a basic AI that will allow your kit robot to walk around, explore, and make its own decisions based on the environment you put it in.

## Exercise 3.18.1

**The Basic Principles of Robotics**

```lisp

```

## Exercise 3.18.2

**Programmable Kit Robots**

The Bioloid Premium Robot Kit is probably the most cost-effective solution that offers a full complement of programmable kit robot features.

http://www.robotshop.com/

```lisp

```

## Exercise 3.18.3

**Handling Controllers, Servos, and Sensors**

```lisp

```

## Exercise 3.18.4

**The Control Board**

```lisp

```

## Exercise 3.18.5

**Dispatching to Servos**

```lisp

```

## Exercise 3.18.6

**Sensors: Gyroscope**

```lisp

```

## Exercise 3.18.7

**Sensors: Infrared**

```lisp

```

## Exercise 3.18.8

**Sensors: Distance Measurement**

```lisp

```

## Exercise 3.18.9

**USB Interfaces**

```lisp

```

## Project 3.18.10

**A Library for the BIOLOID Premium Robot Kit**

```lisp

```

## Exercise 3.18.11

**Robot AI**

```lisp

```

## Exercise 3.18.12

**Motion Teaching and Learning**

```lisp

```

## Exercise 3.18.13

**Intent-Based Motion**

```lisp

```

## Exercise 3.18.14

**Decision-Making, for Robots**

```lisp

```

## Project 3.18.15

**An Independent, Learning Automaton**

```lisp

```

<ul class="pager">
  <li class="previous"><a href="/book/3-17-00-ai.md">&laquo; Previous</a></li>
  <li><a href="/book/">Table of Contents</a></li>
  <li class="next"><a href="/book/3-19-00-space-tech.md">Next &raquo;</a><li>
</ul>
