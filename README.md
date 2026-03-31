# Campus Navigation AI Agent

This is a project that solves problems. It was made using Python for a course called Fundamentals of Artificial Intelligence and Machine Learning.

## Overview

The goal of this project is to make a campus navigation system. This system has an agent that finds the shortest path from the start point, which is the Hostel, to the goal point, which is the AI Lab. The agent has to avoid things that're in the way like buildings and areas that are not allowed.

## Problem

The campus is like a grid that is 7 by 7.

* 0 Means the path is clear

* 1 means there is something in the way like a building

* S means the start, which's the Hostel

* G means the goal, which's the AI Lab

The agent has to figure out the best way to get from S to G.

## Algorithm

We used two kinds of search algorithms.

### Breadth-First Search

This is a way to search. It looks at all the options level by level. It always finds the path but it might look at some things that are not necessary.

### A* Search

This is a way to search. It uses a trick called Manhattan Distance to help it guess which way to go. It is more efficient than the way.

## Project

Our project has a files.

Campus-Navigation-AI/

│── solver.py

│── README.md

│──.gitignore

## Running the Project

To run the project do these steps:

1. Open a terminal in the project folder

2. Run this command:

python solver.py

## Output

The output will show:

* S for the start which's the Hostel

* G for the goal, which is the AI Lab

* # for things that are in the way

* * for the path that the algorithm found

*. For spaces

## Features

Our project has these features:

* It simulates a grid-based environment

* It uses Breadth-First Search to find the path

* It can rebuild the path from start to goal

* It shows the path that was explored

* It keeps track of which nodes were explored

## Concepts

We learned about these concepts:

* Intelligent Agents

* How to represent the state of a space

* Uninformed Search, which's like Breadth-First Search

* Informed Search, which is like A* Search

* Algorithms for finding paths

## Author

Swarit Singh Chauhan

B.Tech in CSE (AIML).

## Course

Fundamentals of Artificial Intelligence and Machine Learning
CSA2001.
