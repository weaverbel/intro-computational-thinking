---
title: Exercise
nav: One
---

In this exercise, we will see how computational thinking can help us add up all the numbers between 1 and 200 in our heads within a minute. 

Seems impossible?

It's not.

Using the first step - *Decomposition* - we break the problem up into smaller pieces. Rather than trying to add up numbers randomly, let's start by simply adding two of them.

### Decomposition

Let's begin at each end of the sequence by adding up the first (1) and last (200) numbers.

What is 200 + 1? The answer is **201**.

Let's add up the second and the second last numbers, i.e. 199 + 2. The answer is **201**.

Let's add up the third and the third last numbers, i.e. 198 + 3. The answer is **201**.

-------

### Pattern Matching

Using our second step - *Pattern Matching* - we can now spot a pattern, i.e. that each pair of numbers will add up to **201**.

{% include figure.html img="pattern-spot.png" alt="Spotting the pattern" caption="Spotting the pattern" width="25%" %}

If we follow this same process with **all** the numbers between 1 and 200, we will end up with **100 pairs**, each of which will add up to **201**.

-------

### Algorithm

Using an *Algorithm* - another name for a series of steps - how do we calculate the final total?

We multiply the **number of pairs** (100) by **201** (the total to which each pair adds up).

`100 * 201` gives us the answer of **20,100**.

So far, so good.

Now, what about about our fourth step, *Abstraction*? 

-------

### Abstraction 

*Abstraction* will enable us to repeat the process we used to add up all the numbers between 1 and 200 to add up a *different* set of numbers, e.g., 1-500.

The *Algorithm* will be 

(`number to be added` divided by 2) multiplied by (`number to be added` +1). We can express that as an algebraic formula:

`(x/2) * (x + 1)`

where *x* is the `number to be added`.

-------------

That's it! Using those four key steps, we have learned the basics of computational thinking.

---------

#### Practice

Use the algorithm above to add up all the numbers betwen 1 and 400, 1 and 2000, and 1 and 20,000.
