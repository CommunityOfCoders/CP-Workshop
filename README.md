# CP-WORKSHOP

## BASICS
### [Binary Exponentiation](https://cp-algorithms.com/algebra/binary-exp.html)
### [Greatest Common Divisor](https://cp-algorithms.com/algebra/euclid-algorithm.html)
### [Nth Fibonacci Number](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)
### [Sieve of Eratosthenes](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html)
### [Integer Factorization](https://cp-algorithms.com/algebra/factorization.html)
### Modular Arithmetic
```
Addition
(a + b) % m = ((a % m) + (b % m)) % m

Subraction
(a - b) % m = ((a % m) - (b % m)) % m

Multiplication
(a * b) % m = ((a % m) * (b % m)) % m

Division (We need to use Mod Inverse)
(a / b) % m != ((a % m) / (b % m)) % m
```
### Modular Inverse
```
Using Fermat's Little  theorem
If m is prime
modInv(a, m) {
    return fastpow(a, m - 2, m);
    // pow(a, m - 2) % m
}
(a / b) % m = ((a % m) * modInv(b, m)) % m
```

## TOPICS
### Binary Search
* [Tutorial](https://www.topcoder.com/community/competitive-programming/tutorials/binary-search)
* [AGGRCOW](https://www.spoj.com/problems/AGGRCOW/)
* [SNAKEEAT](https://www.codechef.com/problems/SNAKEEAT)

### Disjoint Set Union (DSU)
* [Tutorial](https://www.hackerearth.com/practice/notes/disjoint-set-union-union-find/)
* [Implementation](https://github.com/yash0530/CP/blob/master/01%20DSA/001%20DSU.cpp)
* [DISHOWN](https://www.codechef.com/problems/DISHOWN)
* [ABC 120D](https://atcoder.jp/contests/abc120/tasks/abc120_d)

### Divide and Conquer
* [Merge Sort](https://www.geeksforgeeks.org/merge-sort/)
* [Inversion Count](https://www.geeksforgeeks.org/counting-inversions/)
* [TASTYD](https://www.codechef.com/problems/TASTYD)

3. DP,  DP on Trees
4. Segment Tree
7. Tries
8. FFT (very basic)