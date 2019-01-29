# Collatz-conjecture
The Collatz conjecture is a conjecture in mathematics that concerns a sequence defined as follows: start with any positive integer n. Then each term is obtained from the previous term as follows: if the previous term is even, the next term is one half the previous term. If the previous term is odd, the next term is 3 times the previous term plus 1. The conjecture is that no matter what value of n (here from 1 to 100), the sequence will always reach 1. 
The conjecture is named after Lothar Collatz, who introduced the idea in 1937, two years after receiving his doctorate. It is also known as the 3n + 1 conjecture, the Ulam conjecture (after Stanisław Ulam), Kakutani's problem (after Shizuo Kakutani), the Thwaites conjecture (after Sir Bryan Thwaites), Hasse's algorithm (after Helmut Hasse), or the Syracuse problem;the sequence of numbers involved is referred to as the hailstone sequence or hailstone numbers (because the values are usually subject to multiple descents and ascents like hailstones in a cloud), or as wondrous numbers.

Paul Erdős said about the Collatz conjecture: "Mathematics may not be ready for such problems."[8] He also offered $500 for its solution. Jeffrey Lagarias in 2010 claimed that based only on known information about this problem, "this is an extraordinarily difficult problem, completely out of reach of present day mathematics."
Consider the following operation on an arbitrary positive integer:

    If the number is even, divide it by two.
    If the number is odd, triple it and add one.

In modular arithmetic notation, define the function f as follows:

    f ( n ) = { n / 2 if  n ≡ 0 ( mod 2 ) and 3 n + 1 if  n ≡ 1 ( mod 2 ) . 
    Now form a sequence by performing this operation repeatedly, beginning with any positive integer, and taking the result at each step as the input at the next. 
    The Collatz conjecture is: This process will eventually reach the number 1, regardless of which positive integer is chosen initially.
a(i) is the value of f  applied to  n recursively i  times; a (i) = (f(n))^(i).
That smallest i such that a(i) = 1 is called the total stopping time of n. The conjecture asserts that every n has a well-defined total stopping time. If, for some n, such an i doesn't exist, we say that n has infinite total stopping time and the conjecture is false.

If the conjecture is false, it can only be because there is some starting number which gives rise to a sequence that does not contain 1. Such a sequence might enter a repeating cycle that excludes 1, or increase without bound. No such sequence has been found. 
