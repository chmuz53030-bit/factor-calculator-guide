# Factor Calculator Guide

A short, practical guide to the factor math behind a factor calculator: finding factors, prime factorization, greatest common factor (GCF), and least common multiple (LCM).

## What are factors?

A factor of a number is an integer that divides it evenly. For example, the factors of 12 are 1, 2, 3, 4, 6, and 12. To find them by hand, test each integer from 1 up to the square root of the number; every divisor `d` you find gives you a factor pair `(d, n/d)`.

## Prime factorization

Every integer greater than 1 can be written as a product of primes. For example: 360 = 2³ × 3² × 5. Prime factorization is the foundation for computing GCF and LCM.

## Greatest Common Factor (GCF)

The GCF of two numbers is the largest integer dividing both. The fastest way to compute it is the Euclidean algorithm: repeatedly replace the larger number with the remainder of dividing it by the smaller until the remainder is zero. Example: gcf(48, 18) = 6.

## Least Common Multiple (LCM)

The LCM of two numbers is the smallest positive integer divisible by both. It can be derived from the GCF:

    lcm(a, b) = |a × b| / gcf(a, b)

Example: lcm(4, 6) = 24 / 2 = 12.

## Free online calculator

If you'd rather get the answer instantly instead of working it out by hand, try the free [Factor Calculator](https://factorcalculator.org/) — it finds factors, GCF, and LCM for any numbers you enter.
