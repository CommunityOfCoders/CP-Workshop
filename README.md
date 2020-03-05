# CP-Workshop

## BASICS
* [Binary Exponentiation](https://cp-algorithms.com/algebra/binary-exp.html)
* [Greatest Common Divisor](https://cp-algorithms.com/algebra/euclid-algorithm.html)
* [Nth Fibonacci Number](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)
* [Sieve of Eratosthenes](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html)
* [Integer Factorization](https://cp-algorithms.com/algebra/factorization.html)
* Modular Arithmetic
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
* Modular Inverse
```
Using Fermat's Little  theorem
If m is prime
modInv(a, m) {
    return fastpow(a, m - 2, m);
    // pow(a, m - 2) % m
}
(a / b) % m = ((a % m) * modInv(b, m)) % m
```