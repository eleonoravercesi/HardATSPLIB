# On the integrality Gap of Small Asymmetric TSPs: A Polyhedral and Computational Approach
This folder contains the instances proposed in Table 2 and Table 3 of the paper

Eleonora Vercesi, Janos Barta, Luca Maria Gambardella, Stefano Gualandi, Monaldo Mastrolilli,
[On the integrality Gap of Small Asymmetric TSPs: A Polyhedral and Computational Approach](https://www.sciencedirect.com/science/article/pii/S1572528625000246)
Discrete Optimization, Volume 57, 2025, 100901.

## Table 3
In the `table3` folder, the instances are provided in `npy` format.

The cost vector as well as the vertex attaining the optimal ASEP solution, are provided

In practice, you can simply use the following code to read the instances:
```python
X = np.load('table3/X_11.npy')
C = np.load('table3/C_11.npy')
```
Where `X` is the vertex and `C` is the cost vector.

The dimension of `X` is $n \times (n-1)$ where $n$ is the number of nodes in the graph. The values of the edges are displayed here in lexicographical order.
The dimension of `C` is $n \times n$.

## Table 4
The instances of Table 4 can be found in the `table4` folder. 

As explained in the paper, the ATSP instances have been transformed and rescaled so as to be parsed by Concorde.

The original instances can be found in the `table4/ATSP` folder in the `.atsp` format, while the corresponding transformed instances are in the `table4/STSP` folder in the `.tsp` format.

Note that Concorde only deals with `.tsp` format.
