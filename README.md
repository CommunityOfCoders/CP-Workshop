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

2. DSU (disjoint set union)
3. DP,  DP on Trees
4. Segment Tree
5. Divide and Conquer
6. Mod Inverse
7. Tries
8. FFT (very basic)