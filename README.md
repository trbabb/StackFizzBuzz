StackFizzBuzz
=============
(c) 2015 Tim Babb

The [FizzBuzz problem](https://en.wikipedia.org/wiki/Fizz_buzz#Programming_interviews) 
requires the construction of a well-known list of interleaved numbers and 
nonsense words. The list has been studied extensively, and recent work at 
CERN has constrained its utility to less than 10<sup>-16</sup> of a 
mosquito's left nut. In modern times, the task of its production is 
typically relegated to computer programs. It is also an open question why 
some institutions continue to use FizzBuzz as a test of programming 
ability, given universal knowledge of the test and the wide availability of 
solutions on Google and StackOverflow. 

Programs that solve FizzBuzz are typically constructed by hand in an ad-hoc 
manner, often by inexperienced computer scientists. Below is presented an 
algorithmic solution to the second-order problem of generating such 
programs. In general, we define a class of n<sup>th</sup>-order FizzBuzz 
problems which require the production of a program which solves the 
(n-1)<sup>th</sup>-order FizzBuzz problem.

We use a variation on the stacksort algorithm due to [Munroe 
(2013)](https://xkcd.com/1185/) and first implemented by [Koberger 
(2013)](https://gkoberger.github.io/stacksort/), which mimics a technique 
commonly employed in the wild. Here, the availability of solutions on 
StackOverflow is exploited to solve the second-order FizzBuzz problem in 
quadratic time<sup>[*citation needed*]</sup>.

With reasonable probability, StackFizzBuzz finds, downloads, and executes a 
FizzBuzz solution from StackOverflow. Also, with small but nonzero 
probability, FizzBuzz may root your computer. It is recommended that 
StackFizzBuzz not ever be run.