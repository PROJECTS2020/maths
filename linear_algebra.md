<!-- ## https://www.markdownguide.org/ -->
<!-- ## https://www.markdownguide.org/extended-syntax/ -->
<!-- ## https://github.github.com/gfm/ -->

## [Mathematics for Machine Learning: Linear Algebra](https://www.coursera.org/learn/linear-algebra-machine-learning) (Coursera.org)

**OBJECTIVES:**
1. Understand the fundamentals of Linear Algebra.
2. Translate into the basics of Machine Learning.
3. Develop interactive exercises.
4. Document using Jupyter Notebooks.
5. Plan weekly study times, ask question and network!

**REFERENCES:**
- [Equations](https://www.coursera.org/learn/linear-algebra-machine-learning/resources/WPKgo)
- *Mathematical Methods in the Physical Sciences* by Mary L Boas, John Wiley and Sons, 3rd Ed, 2006. 
- *[Introduction to Linear Algebra](http://math.mit.edu/~gs/linearalgebra/)* by Gilbert Strang, Wellesley-Cambridge Press, 5th Ed, 2016.
- [Khan Academy: Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
- [Grant Sanderson](http://www.3blue1brown.com)
- Reference articles contributed to Wikipedia on [linear algebra](https://en.wikipedia.org/wiki/Linear_algebra)

>**Exercise #1 - Price Discovery**

Instructor: *Say I go shopping on two occasions, and I buy apples and bananas, and the first time I buy two apples and three bananas and they cost eight Euros. And the second time I buy say, ten apples and one banana, and the cost is 13 Euros. And the As and the Bs here, are the price of a single apple and a single banana. In these "simultaneous equations", how would you discover the price of individual apples and bananas?*

```
2a + 2b = 8USD
(English: Two apples plus two bananas equal eight U.S. dollars.)

10a + 1b = 13USD
(English: Ten apples plus one banana equals thirteen U.S. dollars.)
```

*This is an example of a Linear Algebra problem. I have some "constant linear coefficients" here, these numbers 2, 10, 3, 1, that relate the "input variables" A and B, to the "output" 8 and 13; that is, if I think about a "vector" [a,b], that **describes the prices** of apples and bananas.*

```
constant linear coefficients = 2, 10, 3, and 1
vectors or input variables = a, b
output or price of both a and b = 8, 13
```

*Then this gets **translated into a cost, to find out how many I might want to buy**. And I can write this down as a "matrix problem" where the 2, 3 is my first trip, and the 10, 1 is my second trip, and then these are then matrices, that's a matrix then, and these are vectors.* 

```
matrix problem: (matrix)[vector] = [vector]

( 2  3 ) [ a ] = [ 8 ]
  10 1     b       13 
```

>**Exercise #2 - Fitting an Equation to Some Data**

Instructor: *With **neural networks** and **machine learning**, we want the computer in effect not only to fit the equation, but to figure out what equation to use. let's say, we have some data like an histogram that looks like a population with an average and some variation or some width.*

>**Exercise #3 - How to Find the Optimal Value of the Parameters in an Equation Describing a Line**


