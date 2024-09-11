This repository contains work used to solve various problems on projecteuler.net. The problem statements are 
listed below. The work for each problem is located in a file named according to the problem number.


## Problem #2:

Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with 1 and 2, 
the first terms will be:

1, 2, 3, 5, 8, 13, 21, 34, 55, 89,...

By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.


## Problem #18:

By starting at the top of the triangle below and moving to adjacent numbers on the row below, the maximum total from top to bottom is 
23.

       3
      7 4
     2 4 6
    8 5 9 3

That is, 3 + 7 + 4 + 9 = 23.

Find the maximum total from top to bottom of the triangle below:

                    75
                   95 64
                  17 47 82
                 18 35 87 10
                20 04 82 47 65
               19 01 23 75 03 34
              88 02 77 73 07 63 67
             99 65 04 28 06 16 70 92
            41 41 26 56 83 40 80 70 33
           41 48 72 33 47 32 37 16 94 29
          53 71 44 65 25 43 91 52 97 51 14
         70 11 33 28 77 73 17 78 39 68 17 57
        91 71 52 38 17 14 91 43 58 50 27 29 48
       63 66 04 68 89 53 67 30 73 16 69 87 40 31
      04 62 98 27 23 09 70 98 73 93 38 53 60 04 23


## Problem #39:

If p is the perimeter of a right angle triangle with integral length sides, 
{a,b,c}, there are exactly three solutions for p = 120.

{20,48,52}, {24,45,51}, {30,40,50}

For which value of p <= 1000, is the number of solutions maximised?


## Problem #69:

Euler's totient function, phi(n) [sometimes called the phi function], is defined as the number of 
positive integers not exceeding n which are relatively prime to n. For example, as 1, 2, 4, 5, 7, and 
8, are all less than or equal to nine and relatively prime to nine, phi(9) = 6.

| n   | Relatively Prime | phi(n) | n/phi(n) |
|-----|------------------|--------|----------|
| 2   | 1                | 1      | 2        |
| 3   | 1, 2             | 2      | 1.5      |
| 4   | 1, 3             | 2      | 2        |
| 5   | 1, 2, 3, 4       | 4      | 1.25     |
| 6   | 1, 5             | 2      | 3        |
| 7   | 1, 2, 3, 4, 5, 6 | 6      | 1.1666.. |
| 8   | 1, 3, 5, 7       | 4      | 2        |
| 9   | 1, 2, 4, 5, 7, 8 | 6      | 1.5      |
| 10  | 1, 3, 7, 9       | 4      | 2.5      |


It can be seen that n = 6 produces a maximum n/phi(n) for n <= 10.
Find the value of n <= 1000000 for which n/phi(n) is a maximum.

