# On the integrality Gap of Small Asymmetric TSPs: A Polyhedral and Computational Approach
This folder contains the instances proposed in Table 2 and Table 3.

In the `table2` folder, the instances are provided in `npy` format.

The cost vector as well as the vertex attaining the optimal ASEP solution are provided

In practice, you can simply use the following code to read the instances:
```python
X = np.load('table2/X_11.npy')
C = np.load('table2/C_11.npy')
```
Note that the vertex is rectified, while the cost vector is not (namely, it is a 2 dimensional array of dimension $n \times n$).

The instances of Table 3 can be found in the `table3` folder. The instances are provided in `.atsp` format and in `.tsp` format.
Note that Concorde only deal with `.tsp` format.