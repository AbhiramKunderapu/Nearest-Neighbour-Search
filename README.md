# Nearest Neighbour Search

## Core Concept
This project implements algorithms for the Nearest Neighbour Search problem, which is fundamental in areas such as machine learning, pattern recognition, and information retrieval. The goal is to efficiently find the closest data point(s) in a dataset to a given query point, based on a defined distance metric (typically Euclidean distance).

The project includes:
- Data structures for representing vectors and datasets
- Algorithms for brute-force and tree-based nearest neighbour search
- Example datasets and test cases

## Project Structure
- `nearest_neighbour1.cpp`: Implements the first approach for nearest neighbour search (e.g., brute-force or linear scan).
- `nearest_neighbour2.cpp`: Implements the second approach (e.g., tree-based or optimized search).
- `DataVector.cpp`/`.h`, `VectorDataset.cpp`/`.h`, `TreeIndex.cpp`/`.h`: Supporting classes for data representation and indexing.
- `assignment-3.pdf`, `assignment-5.pdf`: Assignment descriptions and problem statements.

## How to Build the Executables

### Prerequisites
- A C++ compiler (e.g., g++, clang++)
- CMake (optional, if you want to use a build system)

### Building with g++ (Command Line)
Open a terminal in the project directory and run:

For `nearestneighbour1.exe`:
```sh
g++ -o nearestneighbour1.exe nearest_neighbour1.cpp DataVector.cpp VectorDataset.cpp TreeIndex.cpp
```

For `nearestneighbour2.exe`:
```sh
g++ -o nearestneighbour2.exe nearest_neighbour2.cpp DataVector.cpp VectorDataset.cpp TreeIndex.cpp
```

This will generate the two executable files in your project directory.

### Notes
- Make sure all `.cpp` and `.h` files are in the same directory or update the include paths as needed.
- The `.exe` files can be run from the terminal or by double-clicking (on Windows).

## Usage
Run the executables with the required input files or parameters as described in your assignment PDFs.

---

Feel free to modify this README to better fit your specific implementation details or usage instructions. 