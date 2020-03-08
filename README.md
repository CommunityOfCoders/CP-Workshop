# CP-WORKSHOP

## BASICS
### [Binary Exponentiation](https://cp-algorithms.com/algebra/binary-exp.html)
### [Greatest Common Divisor](https://cp-algorithms.com/algebra/euclid-algorithm.html)
### [Nth Fibonacci Number](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)
### [Sieve of Eratosthenes](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html)
### [Integer Factorization](https://cp-algorithms.com/algebra/factorization.html)
### Modular Arithmetic
```cpp
// Addition
(a + b) % m = ((a % m) + (b % m)) % m

// Subraction
(a - b) % m = ((a % m) - (b % m)) % m

// Multiplication
(a * b) % m = ((a % m) * (b % m)) % m

// Division (We need to use Mod Inverse)
(a / b) % m != ((a % m) / (b % m)) % m
```
### [Modular Inverse](https://cp-algorithms.com/algebra/module-inverse.html)
```cpp
// Using Fermat's Little  theorem
// If m is prime
modInv(a, m) {
    return fastpow(a, m - 2, m);
    // pow(a, m - 2) % m
}
(a / b) % m = ((a % m) * modInv(b, m)) % m
```

## TOPICS
### Binary Search
* [Tutorial](https://www.topcoder.com/community/competitive-programming/tutorials/binary-search) (Topcoder)
* [AGGRCOW](https://www.spoj.com/problems/AGGRCOW/)
* [SNAKEEAT](https://www.codechef.com/problems/SNAKEEAT)

### Divide and Conquer
* [Merge Sort](https://www.geeksforgeeks.org/merge-sort/)
* [Inversion Count](https://www.geeksforgeeks.org/counting-inversions/)
* [TASTYD](https://www.codechef.com/problems/TASTYD)

### Disjoint Set Union (DSU)
* [Tutorial](https://www.hackerearth.com/practice/notes/disjoint-set-union-union-find/) (Hackerearth)
* [Implementation](https://github.com/yash0530/CP/blob/master/01%20DSA/001%20DSU.cpp)
* [DISHOWN](https://www.codechef.com/problems/DISHOWN)
* [ABC 120D](https://atcoder.jp/contests/abc120/tasks/abc120_d)

### Tries
* [Tutorial](https://www.hackerearth.com/practice/data-structures/advanced-data-structures/trie-keyword-tree/tutorial/) (Hackerearth)
* [Implementation](https://github.com/yash0530/CP/blob/master/01%20DSA/016%20Trie.cpp)
* [MAX-XOR](https://www.hackerrank.com/challenges/maximum-xor/problem)
* [ENGLISH](https://www.codechef.com/problems/ENGLISH)

### Graphs
* [TOPOSORT](https://www.spoj.com/problems/TOPOSORT/) (Topological Sort)
* [BUGLIFE](https://www.spoj.com/problems/BUGLIFE/) (Bipartite Graph)

## ADVANCED TOPICS
### Dynammic Programming
* [Top 20 must do DP problems](https://www.geeksforgeeks.org/top-20-dynamic-programming-interview-questions/) (GFG)
* [Educational DP contest](https://atcoder.jp/contests/dp/tasks) (AtCoder)
* [EXPCAN](https://www.codechef.com/problems/EXPCAN)
* [Burst Balloons](https://leetcode.com/problems/burst-balloons/)
* [PEPPERA](https://www.codechef.com/COOK115A/problems/PEPPERA)
* [ABC 158F](https://atcoder.jp/contests/abc158/tasks/abc158_f)

### Segment Tree
* [Tutorial](https://cp-algorithms.com/data_structures/segment_tree.html) (cp-algorithms)
* [Tutorial](https://kartikkukreja.wordpress.com/2014/11/09/a-simple-approach-to-segment-trees/)
* [Tutorial](https://www.youtube.com/playlist?list=PLMCXHnjXnTnuASA1NghV3Vs9J3D_ij5w2) (Youtube)
* [Implementation with Lazy Prop](https://github.com/yash0530/CP/blob/master/01%20DSA/004%20LAZY.cpp)
* [ABC 157E](https://atcoder.jp/contests/abc157/tasks/abc157_e)
* [FLIPCOIN](https://www.codechef.com/problems/FLIPCOIN)
* [GSS1](https://www.spoj.com/problems/GSS1/)
* [CYCLCSUM](https://www.codechef.com/COOK115A/problems/CYCLCSUM)

### Tree DP
* [Tutorial](https://codeforces.com/blog/entry/20935) (Codeforces)

### Polynomial Multiplication (FFT)
* [Tutorial](https://cp-algorithms.com/algebra/fft.html) (Don't worry too much about math behind it, learn how to use it)
* [Codeforces 993E](https://codeforces.com/problemset/problem/993/E)


### LCA (Binary Lifting)
* [Tutorial](https://www.youtube.com/watch?v=ctZ7fjMbPWE) (Youtube)
* [Tutorial](https://cp-algorithms.com/graph/lca_binary_lifting.html) (cp-algorithms)

## RESOURCES

### Youtube
* [GauravSen](https://www.youtube.com/channel/UCRPMAqdtSgd0Ipeef7iFsKw)
* [Errichto](https://www.youtube.com/channel/UCBr_Fu6q9iHYQCh13jmpbrg)
* [William Lin](https://www.youtube.com/channel/UCKuDLsO0Wwef53qdHPjbU2Q)

### Contests and Practice
* [Codechef](https://www.codechef.com/)
* [Codeforces](https://codeforces.com/)
* [AtCoder](http://atcoder.jp/)
* [LeetCode](https://leetcode.com/)
* [SPOJ](https://spoj.com)

### Reading
* Editorials on Codechef and Codeforces
* [Book](https://cses.fi/book/book.pdf)
* [cp-algorithms](http://cp-algorithms.com/)
* [Topcoder Articles](https://www.topcoder.com/community/competitive-programming/tutorials/)