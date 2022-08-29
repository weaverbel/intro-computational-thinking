---
title: Computational thinking in programming
nav: Examples
 
---

Decomposition is really important in programming. The computer must be told precisely what to do, and in what order, so a problem you are using automation to solve must be broken down and each section coded appropriately.

Suppose we want to find the most commonly used ten words in a text. How would we go about that?

#### Linear code

There are many ways to do it. This is one way, where all the commands are run in a linear sequence. We could first

{% include figure.html img="word-counting.png" alt="counting words in a text" caption="Counting words in a text" width="60%" %}

Job done.

Each part of the sequence would need to be individually coded. The good thing is that programmers can adapt code that others have already used to do similar tasks. This is where *pattern matching* comes in - finding similar code that can be adapted. 

--------

#### Branching code

However, most programming rarely works in a linear fashion. Code generally includes branching so that different pathways can be taken, depending on conditions being met or not met, e.g., different responses to a Yes/No decision, as in the example here.

{% include figure.html img="workflow.png" alt="Branching code" caption="Branching code" width="90%" %}
