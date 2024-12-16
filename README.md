# Skyline Problem Using Divide and Conquer

## Project Description
This project implements a solution to the **Skyline Problem** using the **divide-and-conquer technique**. The algorithm determines the visible outline of a set of rectangular buildings in a 2D plane. The solution is efficient, with a time complexity of \(O(n \log n)\), and outputs the skyline as a sequence of key points where the height changes.


## Files
- **[AlgoTeamProject](/AlgoTeamProject.ipynb)**: Contains the implementation of the skyline problem algorithm, including functions `get_skyline` and `merge_skylines`.

---

## How It Works
### Algorithm
- The input is a list of buildings represented as `(L, H, R)` tuples, where `L` is the left x-coordinate, `H` is the height, and `R` is the right x-coordinate.
- The algorithm recursively divides the list of buildings into two halves, solves for each half, and merges the results to produce the final skyline.

**Input Buildings:**  
```[(1, 11, 5), (3, 8, 10), (7, 15, 20), (15, 20, 22)]```

**Output:**  
```
Skyline:
(1, 11, Δx=1)
(5, 8, Δx=4)
(10, 15, Δx=5)
(20, 20, Δx=10)
(22, 0, Δx=2)

**X-coordinates where height changes:**  
1, 5, 10, 20, 22

**Output list:**
[1, 11, 4, 8, 2, 15, 8, 20, 7, 0]
```

## Contact
For questions or assistance, please contact:  
**M Reda KATBY, Nafea ALAMRI**  
**Email:** morikapt@gmail.com
**GitHub:** [[Your GitHub Profile Link](https://github.com/RiadKatby)]
