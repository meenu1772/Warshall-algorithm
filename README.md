
# Floyd-Warshall Algorithm

This repository contains a C++ implementation of the Floyd-Warshall algorithm, which is used to find the shortest paths between all pairs of vertices in a weighted graph.

## How to Use

1. Clone this repository to your local machine.

2. Open the `FloydWarshall.cpp` file in a C++ compiler.

3. Input the number of vertices and edges, followed by the edge information (source, destination, and weight).

4. Compile and run the program. It will output the shortest distances between all pairs of vertices in the given graph.

## Sample Input
4 5
0 1 3
0 2 6
1 2 1
2 3 2
3 0 4


## Sample Output

0 3 4 6
3 0 1 3
6 1 0 2
4 7 2 0


Feel free to modify the input in the `main` function to test the algorithm with different graphs.

## Contribution

If you find any issues or improvements, please feel free to contribute by opening a pull request. Your contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

