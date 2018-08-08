
# Sampling at unknown locations: Uniqueness and reconstruction under constraints

This repository contains all the code to reproduce the second part of the 
results of the paper
**Sampling at unknown locations: Uniqueness and reconstruction under 
constraints**
 by G. Elhami, M. Pacholska, A. Scholefield, B. Bejar and M. Vetterli.

In more detail, this code is generating all the figures related to polynomials 
with rational warping,
as it builds on top of code for a paper
**Sampling at Unknown Locations**, by M. Pacholska, A. Scholefield, B. Bejar and 
M. Vetterli.

Code that generated the figures form the previous paper can be found under fist 
version `v1.0`

## Abstract

    Traditional sampling results assume that the sample locations are known. 
Motivated by simultaneous localization and mapping (SLAM) and structure from 
motion (SfM), we investigate sampling at unknown locations. Without further 
constraints, the problem is often hopeless. For example, we recently showed 
that, for polynomial and bandlimited signals, it is possible to find two 
signals, arbitrarily far from each other, that fit the measurements. However, we 
also showed that this can be overcome by adding constraints to the sample 
positions.

    In this paper, we show that these constraints lead to a uniform sampling of 
a composite of functions. Furthermore, the formulation retains the key aspects 
of the SLAM and SfM problems, whilst providing uniqueness, in many cases.

    We demonstrate this by studying two simple examples of constrained sampling 
at unknown locations. In the first, we consider sampling a periodic bandlimited 
signal composite with an unknown linear function. We derive the sampling 
requirements for uniqueness and present an algorithm that recovers both the 
bandlimited signal and the linear warping. Furthermore, we prove that, when the 
requirements for uniqueness are not met, the cases of multiple solutions have 
measure zero.

    For our second example, we consider polynomials sampled such that the 
sampling positions are constrained by a rational function. We previously proved 
that, if a specific sampling requirement is met, uniqueness is achieved. In 
addition, we present an alternate minimization scheme for solving the resulting 
non-convex optimization problem.

    Finally, simulation results are provided to support our theoretical 
analysis.

## Authors

Michalina Pacholska, EPFL

<img 
src="http://lcav.epfl.ch/files/content/sites/lcav/files/images/Home/
LCAV_anim_200.gif">


#### Contact

Michalina Pacholska, michalina.pacholska at epfl.ch

## About

* Instructions on how to recreate the figures in the paper.

## Requirements

* Instructions on how to install this package (including dependencies)

## License

* Add the LICENSE file to the root of your repository, to make github understand 
that there is one. *Don't forget to fill in the year and author names in that 
file and in the snippet below.*

```
Copyright (c) 2018, Michalina Pacholska

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
