# algorithms

1. BruteForceHull ... Brute force convex hull implementation having run time of O(n^3). Can be easily upgraded to work with a UI. More can                       be read at https://en.wikipedia.org/wiki/Convex_hull_algorithms.
2. sort ... Bubble sort, Insertion sort, Merge sort, Selection sort

3. quickSort ... Recursive implementation of quick sort. More can be read at https://en.wikipedia.org/wiki/Quicksort.

4. sieve ... Sieve of Eratosthenes. An algorithm to find all primes smaller than or equal to a given number. More can be read at
             https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes.
             
5. KMP ... Implementation of Knuth–Morris–Pratt (KMP) string matching algorithm. Worst case complexity: O(n). More can be read at
           https://en.wikipedia.org/wiki/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm.

6. RSA ... Implementation of RSA algorithm to encode and decode a message. First a large prime number is generated between 1000-10,000 using Sieve of Eratosthenes. The number added to a large number (10^5) then acts as a seed to find large prime numbers. After that linear search from the seed to next numbers is done to find prime numbers using Fermat and Miller-Rabin theorem. The prospective number is tested through Miller-Rabin theorem several times(100) with different bases to make sure that the number is prime. Based on the two numbers, key and lock are generated. More can be read at https://simple.wikipedia.org/wiki/RSA_(algorithm). The algorithm is a bit slow due to too many tests of miller-rabin and exhaustive search of fermat's theorem. I will try to write it in C and use pthreads to parallelize the work soon to make it faster.
7. LCS ... Program to find the Longest Common Substring of two strings using dynamic programming.
