# Graph Coloring DSatur and Backtracking

## Overview

This project explores and compares different graph coloring algorithms. Specifically, it examines the performance and effectiveness of the DSatur heuristic algorithm and a backtracking algorithm. The comparison includes the time complexity, solution quality, and the number of colors used by each algorithm on various graph sizes and edge densities.

## Algorithms

### DSatur Algorithm

The DSatur (Degree of Saturation) algorithm is a heuristic approach used to solve the graph coloring problem. It aims to minimize the number of colors used while satisfying the constraints of the problem.

### Backtracking Algorithm

The backtracking algorithm is an exact method that systematically searches for a valid coloring by trying all possible combinations of colors and backtracking when a conflict is encountered.

## Testing

### Black-Box Testing

Black-box testing was performed with various graph structures to validate the algorithm's correctness without knowledge of the internal workings. The following test cases were used:
- **Empty Graph**: Tests with graphs having zero vertices.
- **Single Vertex**: Tests with graphs having a single vertex.
- **Two Connected Vertices**: Tests with graphs having two connected vertices.
- **Triangle Graph**: Tests with simple cycle graphs.
- **Complete Graph**: Tests with graphs where every vertex is connected to every other vertex.
- **Bipartite Graph**: Tests with graphs that can be divided into two disjoint sets.
- **Line Graph**: Tests with graphs forming a linear chain.
- **Cycle Graph**: Tests with graphs forming a cycle.
- **Sparse and Dense Graphs**: Tests with graphs of varying edge densities.

### White-Box Testing

White-box testing was conducted to ensure the correctness of the algorithms by inspecting the internal logic:
- **Edge Cases**: Testing with minimal and maximal edge cases.
- **Algorithm Flow**: Ensuring that the DSatur and backtracking algorithms correctly handle various graph configurations and constraints.
- **Polynomial Time Complexity**: Verification that the DSatur algorithm, when applied, reduces to polynomial time complexity in practical scenarios.

## Polynomial Time Complexity

Efforts have been made to optimize the algorithms, particularly focusing on reducing the DSatur algorithm's complexity to polynomial time. This optimization improves performance, especially for larger graphs, by refining the algorithm's steps and utilizing efficient data structures.

## Results

The detailed results of the experiments, including performance metrics and algorithm comparisons, are documented in the report.

## Contributors

This project was developed and completed by the following contributors:

- **İpek Uzun** - (https://github.com/ipek-uzun)
- **Selman Yılmaz** - (https://github.com/mesely)

