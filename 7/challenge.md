[link](https://dev.to/thepracticaldev/daily-challenge-7-factorial-decomposition-176o)

The aim of this [challenge] is to decompose n!(factorial n) into its prime factors. Prime numbers should be in increasing order. When the exponent of a prime number is 1, don't print the exponent.

Examples:
n = 22; decomp(22) -> "2^19 * 3^9 * 5^4 * 7^3 * 11^2 * 13 * 17 * 19"
n = 25; decomp(25) -> "2^22 * 3^10 * 5^6 * 7^3 * 11^2 * 13 * 17 * 19 * 23"

Explanation:
n = 12; decomp(12) -> "2^10 * 3^5 * 5^2 * 7 * 11"
12! is divisible by 2 ten times, by 3 five times, by 5 two times and by 7 and 11 only once.
