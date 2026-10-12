# Selene's Binary Tree Partioning Map Generator

This is a simple program that generates a partitioned binary tree and renders each 'leaf'.

It works as follows:
  1. Take a rectangle
  2. Cut rectangle along the x or y axis into two parts
  3. Repeat recursively with those two parts
  4. Stop at a certain depth, or from random chance.

My take on the algorithm, specifically, uses a recursive and object-oriented approach. each rectangle, or 'room', is a seperate instance
of a larger 'room' class. Then, we have a function that recursively calls itself to make the tree.

Simple and quick. If i have time, I may come back to this as a seperate project and do a rewrite, as there are parts i could improve.
Right now, however, i have class tommorow.
So,

Made with hate by sillyselene.
