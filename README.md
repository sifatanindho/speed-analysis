# speed-analysis
tl;dr - We experimentally test how the speed of certain algorithms vary across input size.


Algorithmic theory provides a useful framework for understanding how the time complexity of an algorithm increases with input size.  In many cases, these techniques generate solid expectations for which of two algorithms will be better to solve a problem.  In practice, however, growth rate alone is not enough; we can never be sure of an algorithm’s speed on a particular problem size until we try it out.
(Emily Dolson, personal communication) 

For the given problems below, we experimentally tested how the speed of algorithms vary across input sizes with the goal of helping programmers make a more informed decision when choosing a certain algorithm for a task. If reproduced, the exact results of our experiments will vary depending on the specific implementation of the algorithms, the hardware, and the programming language used.

<ol>
  <li>Merge sort vs Insertion sort</li>
  <li>Hybrid sorting</li>
  <li>Comparing dictionary structures</li>
</ol>
