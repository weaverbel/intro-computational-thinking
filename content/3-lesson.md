---
title: Computational thinking in programming
nav: Content
 
---

Decomposition is really important in programming. The computer must be told precisely what to do, and in what order, so a problem you are using automation to solve must be broken down and each section coded appropriately.

Suppose we want to find the most commonly used ten words in a text. How would we go about that?

#### Linear code

There are many ways to do it. This is one way, where all the commands are run in a linear sequence. We could first

{% include figure.html img="word-count.png" alt="counting words in a text" caption="Counting words in a text" width="75%" %}

- save the text as a text file (this will elimiate all "smart" formatting created by programs like Word)
- remove all the punctuation
- change the case of all the words to lower case 
- remove all the `new line` characters
- sort the file by word so that all instaces of a word appear sequentially
- count the instances of each word
- sort by count, with largest first
- output the first ten words

Job done.

--------

#### Branching code

However, programming rarely works in a linear fashion. Usually, code includes branching so that differwent pathways can be taken depending on the conditions being met or not met, e.g. a Yes/No decision.

{% include figure.html img="workflow.png" alt="counting words in a text" caption="Counting words in a text" width="75%" %}
