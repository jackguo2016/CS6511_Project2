# CS6511 Project 2 · Graph Coloring and AC-3

This repository is a placeholder for a Java artificial intelligence coursework project on graph coloring. The task is to give each vertex a color from a fixed set so that vertices connected by an edge have different colors.

## Where to find the project

The related implementation is in [`CS6511_AI_Project2`](https://github.com/jackguo2016/CS6511_AI_Project2). It reads a text file containing a color count and an edge list, then uses backtracking to search for a valid assignment. Its methods explore AC-3 to narrow the available colors, MRV to pick the most constrained vertex, and an LCV-style ordering to decide which color to try first.

The implementation repository contains [the Java entry point](https://github.com/jackguo2016/CS6511_AI_Project2/blob/master/src/Main.java), [a sample graph](https://github.com/jackguo2016/CS6511_AI_Project2/blob/master/src/test4.txt), and [JUnit tests](https://github.com/jackguo2016/CS6511_AI_Project2/blob/master/src/MainTest.java). Follow its README for setup and input details.

This placeholder contains the project pointer only. The Java sources, sample data, and tests live in the implementation repository.
