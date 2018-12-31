Recursion to Iteration Exercises
================================

This repository contains the exercises that accompany a
[series of blog posts I wrote on converting recursive algorithms into iterative algorithms](http://blog.moertel.com/tags/recursion-to-iteration%20series.html).


Tom Moertel / 2013-05-11

Solved the exercise. Read the blog, it is pretty great.

Some things I wanted to add:

- For converting recursive calls to tail calls, think about "what does my
recursive call want to know so that it can just give me the answer directly?"
Then, just pass that in!

- On [stackoverflow](https://stackoverflow.com/questions/159590/way-to-go-from-recursion-to-iteration) 
I read that another good way to think about converting
recursive calls to iterative calls is to keep your own stack to track the
parameters to each recursive call (obviously if you successfully convert
all recursive calls to tail calls, no need to have a stack). 


Rahman Qureshi / 2018-12-30


