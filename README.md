# Random-Programming-Challenges
This is a collection of random programming challenges I think of and will update from time to time.

DISCLAIMER: I might accidentally use an idea that someone else has already used somewhere.

For each challenge, a working solution should run in well under a minute (like Project Euler problems except I haven't programmed any solutions yet so I'm not too sure if this is a good time limit).

## 1. Range Counting

Say that we have an empty collection and a file with some lines of integers. Each line has either 1 or 2 integers.

If there is one number, add it to the collection. Include duplicate numbers if they come up.

If there are two numbers, a and b, then output into another file the amount of numbers in the collection that are >=a and <=b.

All numbers in the input file are between 0 and 10^100. The file will have up to 100,000 lines.

## 2. Strings in Digits

Given three whole numbers a, b, and c, such that 0<=a<=b<=10^100 and c<=a, how many times does c appear in the integers between a and b, inclusive?

An integer x appears in another integer y for k times if x can be seen in k different places when writing the digits of y. For example, if x=888 and y=588890238883, then x appears in y two times.

If two appearances of x overlap, count both of them. For example, if x=888 and y=588889, then x also appears in y two times.

Assume base 10 is always used. c can have leading zeros, but the integers between a and b cannot. (ex. if c=0019, it appears in 1900190 only once, not twice).
