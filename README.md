# Simpy_Learning_Process
### Log:

23th Oct,2017: The method 'Callback' always arises in Simpy Package,so I took some time to understand why and how to use 'callback'.

The following maybe come up with some clues and compare difference among 'plain function' 'callback' 'iterator' 'generator'.

https://code-maven.com/function-or-callback-in-python

24th Oct,2017: http://heather.cs.ucdavis.edu/~matloff/simpy.html ,The material is a better induction for simpy, which also introduce some knowledge about python and math.

My friend teaches her kid math, there is a simple problem that can be solved by many methods, I suggest her to try programming method, and I search for a way to get a traverse permutation matrix, because I use python, the follow site give a method how to create a list with tuple-formated elements.

https://stackoverflow.com/questions/104420/how-to-generate-all-permutations-of-a-list-in-python 

Next,I calculated inner product between two tuple. i used numpy and itertools packages.

The codes is as follow:
```
In [27]: import itertools

In [28]: import numpy as np

In [29]: x=list(itertools.product([1,-1], repeat=8))#生成历遍矩阵

In [30]: y=[np.dot(i,(8,7,6,5,4,3,2,1)) for i in x]

In [31]: y=[i+9 for i in y]
```
25th Oct,2017: I discussed with my friend about math problem mentioned yesterday. I find it harder than what I thought and did.
I have to redesign the program if I want to get more solutions.

Reinforcement or GENETIC algorithm may be a better start. Let me try try.

https://reinforce.io/blog/introduction-to-tensorforce/ I haven't been reading this blog.
