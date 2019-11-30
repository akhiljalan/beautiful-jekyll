---
layout: page
title: Research
subtitle: 
---

**NOTE**: This page is under construction. For a less detailed but more complete listing of my research, please see my CV. 

# Bachelor's Thesis: Structure of the Sandpile Group 

![Alt Text](img/1000000_grains_400_sidelen_RdPu.png)

**Advisor**: [Nikhil Srivastava](https://math.berkeley.edu/~nikhil/)

**Link**: See the full PDF [here](https://akhiljalan.github.io/files/akhil_thesis_sandpile_group.pdf)

**Abstract**: The abelian sandpile model is a discrete dynamical system defined on a graph, in which grains of “sand” are placed on the vertices and move along edges. Despite its simple combinatorial description, the sandpile model has surprising connections to a variety of areas, including spectral graph theory, finite group theory, computational complexity, and more. I survey some of these connections through the lens of the sandpile group, a finite abelian group associated to a graph, whose elements can be identified with recurrent states of the sandpile model. After presenting various equivalent formulations of the sandpile group, I focus on a particular description of the sandpile group, as the cokernel of the graph Laplacian matrix. Under this description, it is (in principle) easy to compute the invariant factor decompositon of the sandpile group, by computing the Smith Normal Form of the reduced Laplacian matrix. Using this technique, I study the invariant factors of the sandpile groups for various families of graphs, especially expanders. I prove lower bounds on the number of trivial invariant factors for families of graphs, such as the hypercube and grid graphs. For more interesting graph families, such as two explicit constructions of expanders, I 	 formulate conjectures about their invariant factors on the base of computer experiments.

# Equity in Facility Location

**Advisors**: [Gireeja Ranade](https://people.eecs.berkeley.edu/~gireeja/), [Swati Gupta](https://swatigupta.tech)

**Collaborators**: Helen Yang, Simon Zhuang

The classical facility location problem seeks to assign *users* to a collection *facilities* (such as public schools or hospitals), so as to minimize the total distance traveled by users. Many variations exist: one can consider a variable opening cost for each facility, included in the objective function, or a set of constraints based on the total service capacity of each candidate facility. For applications involving key public services, it is crucial to consider the socieconomic disparities in a placement. This motivates the addition of an *equity term* in the facility location objective function to explicitly measure fairness, e.g. the extent to which low-income and high-income users must travel different distances to reach their nearest facility. 

In general, it is difficult to define fairness across demographic groups. There are thousands of unique ways to measure equity, based on the choice of demographic grouping (gender, ethnicity, income, etc.), the choice of equity metric, and the relative weights of the equity term and other terms in the objective function. Our work considers the multi-objective optimization problem which attempts to address these unique objective simultaneously. While the optimal solutions to these objective functions are distinct in general, one can look for an *approximately optimal* solution which is within some constant multiplicative factor of the optimum solution for each objective function. If this constant factor is close to 1, then we have found a good "consensus choice" among the many distinct objective functions. 

Our work studies equity in facility location, and especiall approximately optimal solutions, from both a theoretical and applied perspective. In particular, I have led a case study on hospital placement in East Bay, California, motivated by the impending closure of the Alta Bates hospital in Berkeley, CA. We have found that while good approximately optimal solutions do exist in certain regimes, they are sensitive to changes in the problem setup. Moreover, it is difficult to obtain good theoretical bounds on approximation factors, which tend to degrade in the regime where equity is weighted very highly relative to other terms in the objective function.

# Machine Learning in Communication and Control

**Advisor**: [Anant Sahai](https://www2.eecs.berkeley.edu/Faculty/Homepages/sahai.html)

**Collaborators**: Vignesh Subramanian, Sameer Reddy, Laura Brink, Nikunj Jain, Kailas Vodrahalli, Nikhil Shinde

As part of the ML4Wireless Center, I worked on two projects which applied machine learning to wireless communication and controls. 

*Deep Network Defined Radio*: I built neural networks to perform radio demodulation, which decodes signals (complex numbers) into digital data (binary strings). 

*Witsenhausen's Counterexample*: The Witsenhausen Counterexample is a decentralizd control problem in which two controllers in sequence act on an input generated from a Gaussian distribution. The difficulty lies in the noisy communication between controllers: after the first controller acts on the input, the second receives a noisy version of this output. It is believed that a combination of a quantized strategy for C1 and conditional expectation maximization for C2 are near-optimal. Our group studied the effectiveness of this joint strategy, and the extent to which neural networks can learn this strategy with and without biasing. 
