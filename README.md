# Collatz conjecture with a brute force approach

My crack at solving one of the world's unsolved problems in mathematics in Julia:

Unsolved problem in mathematics: Does the Collatz sequence eventually reach 1 for all positive integer initial values?

## Description

According to Wikipedia, the Collatz conjecture is a conjecture in mathematics that concerns a sequence defined as follows: start with any positive integer n.
Then each term is obtained from the previous term as follows: if the previous term is even, the next term is one half the previous term.
If the previous term is odd, the next term is 3 times the previous term plus 1. The conjecture is that no matter what value of n,
the sequence will always reach 1.

It is also known as the 3n + 1 problem, the 3n + 1 conjecture, the Ulam conjecture (after Stanislaw Ulam), Kakutani's problem (after Shizuo Kakutani),
the Thwaites conjecture (after Sir Bryan Thwaites), Hasse's algorithm (after Helmut Hasse), or the Syracuse problem. The sequence of
numbers involved is sometimes referred to as the hailstone sequence or hailstone numbers (because the values are usually subject to multiple
descents and ascents like hailstones in a cloud), or as wondrous numbers.

## Reference

See https://en.wikipedia.org/wiki/Collatz_conjecture for more information.

## Contributing

Pull requests are welcome. For major issues, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
