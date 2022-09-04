# Phase-space-visualization-of-cellular-automata

This repository contains phase space visualisations of cellular automata. 

Consider a one dimensional binary cellular automata model with neighbourhood radius $r = 2$. We assume the spacce is made of 9 cells with periodic boundary conditions (i.e., the space is a ring made of 9 cells). In this setting, the size of the phasee space is just $2^9 = 512$, so this is easy to visualize.   
In order to enumerate all possible configurations, it is convenient to define functions that map a specific configuration of the CA to a unique configuration ID number, and vice versa.   
