# The 100 Master Calculation Methods

A categorized index of **100 core calculation methods** useful for high-speed software development, algorithms, computer science, mathematics, graphics, statistics, signal processing, machine learning, and optimization.

---

## Category 1: Fundamental Arithmetic & Bitwise

*Methods 1–15 — Low-level `O(1)` bit manipulation and core arithmetic shortcuts.*

### 1. Bitwise Shift Multiplication — `x << n`

Fast multiplication by powers of `2`.

### 2. Bitwise Shift Division — `x >> n`

Fast integer division by powers of `2`.

### 3. Parity Check — `x & 1`

`O(1)` even/odd check without using the modulo operator.

### 4. Fast XOR Swap

Swaps two variables without a temporary variable.

### 5. Power of Two Check — `(x & (x - 1)) == 0`

`O(1)` check for whether an integer is a power of `2`.

### 6. Lowest Set Bit — `x & -x`

Isolates the lowest non-zero bit, useful in tree structures and bit manipulation.

### 7. Population Count — `popcount`

Counts the total number of set bits in an integer.

### 8. Integer Square Root — Newton's Method

Fast square-root approximation without relying on floating-point calculations.

### 9. Fast Inverse Square Root — `1 / sqrt(x)`

Fast approximation used historically for vector normalization.

### 10. Absolute Value — Bitwise

Branchless calculation of the absolute value of an integer.

### 11. Signum Function

Returns `-1`, `0`, or `1` based on the sign of a value.

### 12. Saturated Addition

Clamps the result to prevent integer overflow.

### 13. Circular Bit Shift — Rotate Left/Right

Rotates bits around an integer, commonly used in cryptography and hashing.

### 14. Fast Ceiling Division — `(a + b - 1) / b`

Integer ceiling division without floating-point conversion.

### 15. Kernighan's Bit Count

Counts set bits using a loop proportional to the number of set bits.

---

## Category 2: Core Algorithmic & Number Theory

*Methods 16–30 — Techniques that reduce computational complexity to `O(log N)` or `O(1)` where applicable.*

### 16. Gauss Series Sum — `N(N + 1) / 2`

`O(1)` summation of the sequence `1 ... N`.

### 17. Euclidean GCD — `gcd(a, b)`

Efficient logarithmic algorithm for finding the greatest common divisor.

### 18. Binary LCM — `(a × b) / gcd(a, b)`

Calculates the least common multiple using the GCD.

### 19. Binary Exponentiation — `x^n` in `O(log n)`

Fast power calculation using repeated squaring.

### 20. Modular Exponentiation — `(x^n) mod m`

Efficiently calculates large powers under a modulus.

### 21. Sieve of Eratosthenes

Generates all prime numbers up to `N` in `O(N log log N)` time.

### 22. Segmented Sieve

Memory-efficient prime generation for large ranges.

### 23. Extended Euclidean Algorithm

Finds coefficients `x` and `y` such that:

`ax + by = gcd(a, b)`

### 24. Modular Multiplicative Inverse

Solves:

`a × x ≡ 1 (mod m)`

### 25. Chinese Remainder Theorem

Solves systems of simultaneous congruences.

### 26. Fast Fibonacci — Matrix Exponentiation

Calculates `F(n)` in `O(log n)` time.

### 27. Pascal's Triangle — `nCr`

Uses Pascal's Triangle and dynamic programming to calculate combinations.

### 28. Lucas' Theorem

Calculates `nCr mod p` efficiently for large `n` and `r` when `p` is prime.

### 29. Miller-Rabin Primality Test

Fast probabilistic primality test for large integers.

### 30. Karatsuba Multiplication

Multiplies large integers in approximately `O(n^1.58)` time.

---

## Category 3: Array & Matrix Operations

*Methods 31–45 — High-performance array processing and linear algebra techniques.*

### 31. Prefix Sum Array

Preprocesses an array in `O(N)` to answer range-sum queries in `O(1)`.

### 32. 2D Prefix Sum — Summed-Area Table

Enables `O(1)` sub-grid or rectangle sum queries after preprocessing.

### 33. Difference Array

Performs range updates efficiently, often in `O(1)` per update.

### 34. Kadane's Algorithm

Finds the maximum subarray sum in `O(N)` time.

### 35. Matrix Addition Vectorization

Uses SIMD-style parallel operations for element-wise matrix addition.

### 36. Dot Product — BLAS Level 1

Calculates the inner product of two vectors.

### 37. Matrix Multiplication — Strassen Algorithm

Performs matrix multiplication in sub-cubic time.

### 38. Matrix Transpose — Cache-Oblivious

Uses blocking techniques to improve hardware cache locality.

### 39. Determinant — LU Decomposition

Computes a matrix determinant using LU decomposition, typically in `O(N^3)` time.

### 40. Matrix Inversion — Gauss-Jordan

Finds a matrix inverse through elementary row operations.

### 41. Eigenvalue Computation — Power Iteration

Iteratively estimates the dominant eigenvalue and corresponding eigenvector.

### 42. Conjugate Gradient Method

Efficiently solves certain large sparse linear systems.

### 43. Sparse Matrix-Vector Multiplication — CSR

Uses Compressed Sparse Row (`CSR`) representation to avoid unnecessary operations on zero values.

### 44. Convolution via FFT

Uses the Fast Fourier Transform to reduce convolution from `O(N^2)` to approximately `O(N log N)`.

### 45. Sliding Window Minimum/Maximum

Uses a monotonic queue to answer sliding-window minimum or maximum queries in `O(N)`.

---

## Category 4: Geometry & Spatial Calculations

*Methods 46–60 — Mathematical techniques for game engines, physics, computer graphics, and mapping.*

### 46. Euclidean Distance — `2D / 3D`

```text
2D: √(Δx² + Δy²)

3D: √(Δx² + Δy² + Δz²)
```

Calculates the straight-line distance between points.

### 47. Manhattan Distance

```text
|Δx| + |Δy|
```

Grid-based distance where movement is restricted to horizontal and vertical directions.

### 48. Chebyshev Distance

```text
max(|Δx|, |Δy|)
```

Distance metric commonly associated with chessboard movement.

### 49. Haversine Formula

Calculates great-circle distance between two coordinates on a sphere.

Useful for GPS and geographic calculations.

### 50. Shoelace Formula

Calculates the area of a polygon in `O(N)` time.

### 51. 2D Cross Product — Orientation Test

Determines the orientation of three points and whether a turn is clockwise or counterclockwise.

### 52. Ray-AABB Intersection — Slab Method

Efficient ray intersection test for axis-aligned bounding boxes.

### 53. Barycentric Coordinates

Represents a point relative to a triangle and enables interpolation across 2D/3D triangles.

### 54. Quaternion Multiplication

Combines 3D rotations while avoiding the gimbal-lock problems associated with Euler angles.

### 55. Bounding Sphere — Ritter's Algorithm

Fast linear-time approximation for creating a bounding sphere around a collection of points.

### 56. Point-in-Polygon — Ray Casting

Determines whether a point lies inside or outside a polygon.

### 57. Linear Interpolation — `Lerp`

```text
a + t(b - a)
```

Smoothly interpolates between two values.

### 58. Spherical Linear Interpolation — `Slerp`

Smoothly interpolates between two rotations represented on a sphere.

### 59. Convex Hull — Graham Scan

Finds the smallest convex boundary containing a set of points in `O(N log N)` time.

### 60. Voronoi Tessellation — Fortune's Algorithm

Constructs a Voronoi diagram in `O(N log N)` time.

---

## Category 5: Statistics, Probability & Financial Math

*Methods 61–75 — Statistical calculations, probability techniques, time-series modeling, and financial mathematics.*

### 61. Welford's Algorithm

Calculates running mean and variance in a numerically stable single pass.

### 62. Rolling Moving Average — SMA

Maintains a moving average with `O(1)` updates for streaming data.

### 63. Exponential Moving Average — EMA

Applies greater weight to recent values for time-series smoothing.

### 64. Percentile / Median — Quickselect

Finds an order statistic in `O(N)` average time.

### 65. Compound Interest Formula

```text
A = P(1 + r/n)^(nt)
```

Calculates accumulated value with compound interest.

### 66. Net Present Value — NPV

Calculates the present value of future cash flows using a discount rate.

### 67. Internal Rate of Return — IRR

Iteratively calculates the discount rate at which an investment's NPV becomes zero.

### 68. Pearson Correlation Coefficient

Measures the strength and direction of a linear relationship between two datasets.

### 69. Covariance Matrix

Represents the variance and covariance relationships between multiple variables.

### 70. Monte Carlo Simulation

Uses repeated random sampling to approximate probabilities and solve numerical problems.

### 71. Box-Muller Transform

Transforms uniformly distributed random values into normally distributed values.

### 72. Reservoir Sampling

Selects `K` random items from a stream without knowing the stream's total size in advance.

### 73. Black-Scholes Model

Mathematical model used for theoretical pricing of certain financial options.

### 74. Z-Score Normalization

```text
z = (x - μ) / σ
```

Rescales data so that the transformed distribution has mean `0` and standard deviation `1`.

### 75. Min-Max Feature Scaling

```text
x' = (x - min) / (max - min)
```

Rescales values into the `[0, 1]` range.

---

## Category 6: Signal Processing & Transforms

*Methods 76–85 — Digital signal processing, filtering, and frequency-domain calculations.*

### 76. Cooley-Tukey Fast Fourier Transform — FFT

Transforms a signal from the time domain into the frequency domain in `O(N log N)` time.

### 77. Inverse Fast Fourier Transform — IFFT

Converts frequency-domain data back into the time domain.

### 78. Discrete Cosine Transform — DCT

Transforms data into cosine frequency components and is widely used in compression techniques.

### 79. Low-Pass RC Filter

Reduces high-frequency components and can be used for basic signal smoothing.

### 80. High-Pass RC Filter

Reduces low-frequency components and emphasizes rapid changes.

### 81. Kalman Filter

Estimates the state of a system from noisy measurements.

### 82. Windowing Functions — Hann / Hamming

Reduces spectral leakage before performing an FFT.

### 83. Savitzky-Golay Filter

Smooths noisy data while preserving important features such as trends and peaks.

### 84. Auto-Correlation Function

Measures similarity between a signal and a delayed version of itself, helping detect repeating patterns.

### 85. Bilinear Transform

Converts analog filter designs into digital IIR filter implementations.

---

## Category 7: Optimization, Machine Learning & Graphs

*Methods 86–100 — Algorithms for optimization, artificial intelligence, pathfinding, compression, and network analysis.*

### 86. Gradient Descent Update

```text
θ = θ - α∇J(θ)
```

Updates model parameters to minimize a loss function.

### 87. Softmax Function

Converts raw model scores into a probability distribution.

### 88. Sigmoid / Logistic Activation

Maps real-valued inputs into the range `(0, 1)`.

### 89. ReLU / Leaky ReLU

```text
ReLU(x) = max(0, x)
```

Simple neural-network activation functions.

### 90. Cross-Entropy Loss

Measures the difference between predicted probabilities and the target distribution.

### 91. Dijkstra's Pathfinding — Min-Heap

Finds shortest paths from a source node when edge weights are non-negative.

Typical complexity with a binary heap:

```text
O((V + E) log V)
```

### 92. A* Search — Heuristic Distance

An informed shortest-path algorithm that combines actual cost with a heuristic estimate.

### 93. Bellman-Ford Algorithm

Finds shortest paths even when graphs contain negative edge weights.

### 94. Floyd-Warshall Algorithm

Computes shortest paths between every pair of vertices in `O(V^3)` time.

### 95. PageRank Algorithm

Uses iterative calculations to estimate the importance of nodes in a network.

### 96. Cosine Similarity

Measures similarity between high-dimensional vectors using the angle between them.

### 97. K-Means Distance Update

Calculates distances between data points and cluster centroids and updates cluster assignments/centroids.

### 98. Gradient Boosting Step

Calculates residual errors that are used to train subsequent decision trees.

### 99. Lossless Run-Length Encoding — RLE

Compresses repeated consecutive values by representing them as value-count pairs.

### 100. L2 Regularization — Ridge

```text
λ ||w||₂²
```

Adds a penalty based on the squared magnitude of model weights to help reduce overfitting.

---

# Summary

These **100 calculation methods** cover a wide range of computer science and software development topics:

* **Bit manipulation**
* **Arithmetic**
* **Number theory**
* **Algorithms**
* **Arrays**
* **Matrices**
* **Geometry**
* **Statistics**
* **Probability**
* **Financial mathematics**
* **Signal processing**
* **Machine learning**
* **Optimization**
* **Graph algorithms**
* **Data compression**

> **Goal:** Build a strong calculation toolkit for solving programming and algorithmic problems efficiently.
