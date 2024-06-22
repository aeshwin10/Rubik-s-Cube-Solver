# Rubik's Cube Solver

A versatile Rubik's Cube solver that uses multiple representation models and solving algorithms.

## Description

This project implements a Rubik's Cube solver with three different cube representation models and four solving algorithms. It can take a scrambled cube state as input and output the solving steps along with the solved cube.

## Features

- **Multiple Cube Representations:**
  - 3D representation
  - 2D representation
  - Bitboard representation

- **Solving Algorithms:**
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Iterative Deepening Depth-First Search (IDDFS)
  - Iterative Deepening A* (IDA*) - Fastest and preferred method


## Cube Representations

General Representation:
![Screenshot 2024-06-22 161753](https://github.com/aeshwin10/Rubik-s-Cube-Solver/assets/94974005/618cd721-7946-4ca9-956f-543efa8ab5a6)

Solved Cube along with the moves:
![Screenshot 2024-06-22 161817](https://github.com/aeshwin10/Rubik-s-Cube-Solver/assets/94974005/c80ed018-9626-425c-bbab-6474d8915ef6)


## Usage
Example of the solver from the main function:
![Screenshot 2024-06-22 161835](https://github.com/aeshwin10/Rubik-s-Cube-Solver/assets/94974005/dc1bfa6c-3b8c-4d32-ab9b-85b1eb004063)

Example of moves which can be done:
![Screenshot 2024-06-22 161859](https://github.com/aeshwin10/Rubik-s-Cube-Solver/assets/94974005/6de38670-375e-45c4-a736-e078f2a86fe4)



## Installation

- You only need a C++ IDE to run this project. 
- CLion Preferred.

## Performance

- BFS, DFS, and IDDFS: Solve 8-times jumbled cubes in under 3 seconds
- IDA*: Solves 13-times jumbled cubes in under 10 seconds

## Contributing

Contributions to this project are welcome! Feel free to submit pull requests or open issues to improve the solver.

## License

This project is licensed under the MIT License. 

