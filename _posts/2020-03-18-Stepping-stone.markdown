---
layout: post
title:  "Stepping Stone"
date:   2020-03-19 10:33:12 +0530
categories: markov-chain 
permalink: /stepping-stone/
---



The Stepping Stone Model is used in the study of genetics.



>Example from **Introduction to Probability**: Grinstead, Snell;

 
In this model we have an n-by-n array of squares, and each square is initially any
one of k different colors. For each step, a square is chosen at random. This square
then chooses one of its eight neighbors at random and assumes the color of that
neighbor.

To avoid boundary problems, we assume that if a square S is on the
left-hand boundary, say, but not at a corner, it is adjacent to the square T on the
right-hand boundary in the same row as S, and S is also adjacent to the squares just
above and below T . A similar assumption is made about squares on the upper and
lower boundaries. 

(These adjacencies are much easier to understand if one imagines
making the array into a cylinder by gluing the top and bottom edge together, and
then making the cylinder into a doughnut by gluing the two circular boundaries
together.) With these adjacencies, each square in the array is adjacent to exactly
eight other squares.

A state in this Markov chain is a description of the color of each square. For this
Markov chain the number of states is k^(n)^2 , which for even a small array of squares
is enormous. 
This is an example of a Markov chain that is easy to simulate but
difficult to analyze in terms of its transition matrix. 

![Initial](/images/initial.png)
*The initial state with 8 colors (k=8) and n=20 (400 squares)*

<ul>
<li markdown="1">
</li>
</ul>


