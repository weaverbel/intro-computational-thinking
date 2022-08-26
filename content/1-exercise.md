---
title: Exercise 1
nav: Exercise
---

In this exercise, we will see how computational thinking can help us add up all the numbers between 1 and 200 within a minute.

Using the first step - *Decomposition* - we break the problem up into smaller pieces.

### Decomposition

We can begin at each end of the sequence by adding up the first (1) and last (200) numbers.

What is 200 + 1?

The answer is **201**.

Then we add up the second and the second last numbers, i.e. 199 + 2.

The answer is **201**.

Then we add up the third and the third last numbers, i.e. 198 + 3.

The answer is **201**.

-------

### Pattern Matching

Using our second step - *Pattern Matching* - we can now spot a pattern, i.e. that each pair of numbers will add up to **201**.

If we are adding up all the numbers between 1 and 200, we will end up with 100 pairs, all of which add up to **201**.

-------

### Algorithm

Using an *Algorithm* - another name for a series of steps - how do we calculate the final total?

We multiply 100 (the number of pairs) by the total to which each pair adds up (**201**).

100 * 201 gives us the answer of **20,100**.

But what about about our fourth step, *Abstraction*? 

-------

### Abstraction 

*Abstraction* will enable us to repeat the process we used to add 1-200 to add up a different set of numbers, e.g., 1-500.

The *Algorithm* will be 

(`number to be added` divided by 2) multiplied by (`number to be added` +1). We can express that as an algebraic formula:

`(x/2) * (x + 1)`

where *x* is the `number to be added.`

-------------

That's it! Using those four key steps, you have covered the basics of computational thinking.

---------

#### Practice

Use the algorithm above to add up all the numbers betwen 1 and 400, 1 and 2000, and 1 and 20,000.
