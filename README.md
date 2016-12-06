StackFizzBuzz
=============
(c) 2015 Tim Babb

The famous [FizzBuzz problem](https://en.wikipedia.org/wiki/Fizz_buzz#Programming_interviews) requires the construction of an ordered list, such that the n<sup>th</sup> element of the list reads "Fizz" if 3 divides `n`, "Buzz" if 5 divides `n`, "FizzBuzz" if both 3 and 5 divide `n`, and `n` otherwise. The list has been studied extensively, and recent work at CERN has constrained the utility of the FizzBuzz sequence to less than 10<sup>-16</sup> of a mosquito's left nut. Herein we'll denote the problem of generating this list to be the "0th-order FizzBuzz problem".

Modern technology has superceded the need for hand calculation or paper-bound lookup tables, and the task of the list's production is typically relegated to computer programs. Such programs that solve FizzBuzz are typically constructed by hand in an ad-hoc manner, often by inexperienced computer scientists. We'll designate the task of producing these programs to be the first-order FizzBuzz problem.

Below is presented an algorithmic solution to the problem of generating such programs, which constitutes the first solution to the second-order FizzBuzz problem. In general, we define a class of n<sup>th</sup>-order FizzBuzz problems which require the production of a program which solves the (n-1)<sup>th</sup>-order FizzBuzz problem.

We use a variation on the stacksort algorithm due to [Munroe (2013)](https://xkcd.com/1185/) and first implemented by [Koberger (2013)](https://gkoberger.github.io/stacksort/), which mimics a technique commonly employed in the wild. Here, the availability of solutions on StackOverflow is exploited to solve the second-order FizzBuzz problem in quadratic time<sup>[*citation needed*]</sup>.

With reasonable probability, StackFizzBuzz finds, downloads, and executes a FizzBuzz solution from StackOverflow. Also, with small but nonzero probability, FizzBuzz may root your computer. It is recommended that StackFizzBuzz not ever be run.
