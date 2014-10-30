# IS606 Homework 4
James Quacinella  
10/30/2014  

### Problem 6.18

For a continuous random variable $X$, the number $m$ such that $P (X ≤ m) = 1/2$ is called the median of X.

(a) Find the median of an Exp(λ) distribution.

(b) Give a simplified expression for the difference between the mean and the median. Is the difference positive or negative?
 
#### Answer

a) $$ F(X) = 1 - e^{-\lambda x} $$
$$ P(X <= x) = 1 - e^{-\lambda x} $$
$$ P(X <= x_{median}) = 1 - e^{-\lambda x_{median}} = \frac{1}{2} $$
$$ \frac{1}{2} = 1 - e^{-\lambda x_{median}} $$
$$ \frac{1}{2} = e^{-\lambda x_{median}} $$
$$ ln(\frac{1}{2}) = ln(e^{-\lambda x_{median}}) $$
$$ ln(\frac{1}{2}) = -\lambda x_{median} $$
$$ -ln(2) = -\lambda x_{median} $$
$$ x_{median} = \frac{ln(2)}{\lambda} $$

b) The difference between the expectation value and the median is:

$$ E[X] - x_{median} $$
$$ = \frac{1}{\lambda} - \frac{ln(2)}{\lambda} $$
$$ = \frac{1 - ln(2)}{\lambda} $$
