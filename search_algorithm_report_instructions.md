# Search Algorithm Report Instructions

Search problems apply to far more applications than pathfinding and routing. From the Jupyter Notebook provided by the authors, `search4e.ipynb`, there are many examples that may not have been discussed in the textbook or lecture slides. Examples include N-Puzzle Problems, Water Pouring Problems, Pancake Sorting Problems, the Jumping Frogs Puzzle, and more.

For this assignment, write a report on any problem that can be solved with a Search Algorithm studied in Chapter 3. This excludes routing/pathfinding and 8-puzzle problems, since those were covered in the textbook.

## Example Topics

You are not limited to this list, but these are acceptable examples:

- N-Queens
- Missionaries and Cannibals
- Water Jug / Water Pouring Problem
- Pancake Sorting
- Jumping Frogs Puzzle
- Towers of Hanoi
- Sudoku as Search
- Word Ladder
- Knight's Tour
- Any other problem that can be connected back to Chapter 3 search algorithms

## Source and AI Policy

You may use any sources for information, but all sources must be cited.

AI models may help with code, but you must cite which model you used. AI models are not allowed as direct sources for the required informational content, but they may be used to help find good internet or book sources.

## Required Format

The report must be written in a Jupyter Notebook.

You may write the report text in Markdown cells.

The notebook must include at least one figure that helps visualize the problem. More figures are welcome.

Visual Studio Code or another local Jupyter Notebook editor is recommended. Google Colab has proprietary image-handling methods that may break when downloaded.

## Problem Description

Include a detailed description of the problem and any necessary background information.

The description must include the problem constraints.

The problem must be solvable using at least one tree or graph search algorithm studied in Chapter 3, such as:

- Breadth-First Search
- Depth-First Search
- Uniform-Cost Search
- Greedy Search
- A*
- Variants of these algorithms

## Problem Definition

Define the problem using the book's definition of a problem. Include all of the following:

- What a node represents in terms of a state
- What information a state provides
- The initial state
- The possible actions/operators
- The transition model
- The goal state or goal states
- The path cost function, if there is one

Be thorough when explaining the state representation.

## Search Tree / Graph Visualization

Provide a visualization of the initial state with edges to adjacent states.

Continue the visualization to a minimum depth of `d = 2`, with all nodes expanded.

Recall that the initial state is depth `d = 0`.

If fully visualizing the branching is unreasonable, such as when states have more than 3 branches, then a minimized set of 3 visualized branches is acceptable.

## Working Code Example

Include code for a working example.

Text output is acceptable, and visualizations are welcome.

You may get the code from any source, but you must cite the source of the code. This includes AI assistance, with the specific model used.

You may also use the authors' code from `search4e.ipynb` or `search.ipynb`, but do not append your assignment to the end of one of their files. You must create your own Jupyter Notebook.

The notebook must include at least one complete run of the algorithm.

Choose an appropriate problem size `n` so the code completes in a reasonable amount of time. Under one minute is preferred.

The code should be runnable directly from the Jupyter Notebook. Special packages or libraries are acceptable if needed.

## Output Explanation

Explain the output of the code.

Describe what the result means.

Explain whether the result is a valid solution.

## Code Discussion

Include a detailed discussion of how the code works.

Identify which search algorithm is being used, such as Breadth-First Search, A*, or another Chapter 3 algorithm.

Explain the main:

- Data structures
- Functions
- Algorithmic steps

You are responsible for understanding the code. Submissions with working code but little explanation will not receive much credit.

## Search Algorithm Discussion

Discuss whether there is a commonly used or especially appropriate search algorithm for this problem.

If there is no universally best algorithm, choose one reasonable Chapter 3 algorithm and justify why it is appropriate.

For the algorithm you choose, discuss:

- Whether the algorithm is complete, as defined in the chapter
- Whether the algorithm is guaranteed to return an optimal solution
- The time complexity in Big-O notation
- The memory complexity in Big-O notation
- Any popular heuristics used with the problem
- How those heuristics affect completeness, time complexity, and memory complexity
