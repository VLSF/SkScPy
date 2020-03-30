[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dKSDj5sXcuB_dYfnzrkC-Zd1z30q9lL4)

# Introduction

In the Autumn of 2019, I was asked to provide a tutorial on Python for fresh master students of Skoltech (Moscow, Russia). Since the tutorial was a part of an extensive course focused on a broad introduction to scientific tools for researchers, I got only two three-hour sessions. The idea was to pick a few interesting (and simple) scientific problems and solve them with basic Python, gradually introducing more functionality along the way. Although this approach turned out to be a complete failure, I decided to share the problems with solutions, in the hope that someone uses them more wisely. The list of problems includes:

# Problem 1: Shotgun sequencing
This problem is about the reconstruction of DNA from overlapping samples. Of course, the real problem is ill-posed, but in the tutorial, we focus on the simplified version where everything is more or less straightforward. Here we introduce all basic syntax: variables and operations, loops, conditions, and functions.

# Problem 2: Ballooning spiders
Watch out! Spiders can fly, using the electric field of the Earth. Here one can see famous NumPy arrays, simple tricks with them, and Matplotlib. The goal of the task is to reproduce figures from the article that estimates realistic conditions under which spiders can join the high fliers.

# Problem 3: Chemical bonds
Some quantum mechanics can't hurt. The problem investigates the toy parametric Hamiltonian, which shows why chemical bonds are real things. The problem mostly exploits previously defined concepts, which includes NumPy and Matplotlib. As a discretization technique, we use finite differences.

# Problem 4: Snowball Earth
Here we consider a famous energy balance model with a feedback loop. The sun is shining. The albedo depends on average temperature (ice reflects more than water/vegetation/soil). It turns out that one can push this system into a desperately cold state known as Snowball Earth. The problem involves Newton's method, bifurcation diagrams, and ODE solvers. Along the way, we introduce more advanced functions, dictionaries, and SciPy.

# Problem 5: Newton's fractal
Well, this is standard. One needs to plot a basin of attraction for Newton's method using a simple function on a complex plane.
