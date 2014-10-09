## Chap2 Discrete Random Variables and Expectation

- reading status: finished on 10/09/2014


### Contents
- Definition
    - sample space
    - expectation
- Linearity of expectation
    - application: calculating the expectation of Bernoulli random variable
- Jensen's inequality
    - for any convex function f, if you connect two points on the graph of the function by a straight line, this line on or above the graph of the function
- Property of expectation
    <div style="text-align:center" markdown="1">
    <img src="./figs/lemma2-9.PNG" width="600px" />
    </div>
- Geometric random variables
    - memoryless
- Analysis of randomized quicksort
    - deterministic algorithm with probabilistic analysis, cool!
    - y_i and y_j will be compare only if they are the first elements chosen from {y_i,...,y_j}, if neither is the first pivot from this set, then they will be seperated into two distinct set and will not be compared.

### Trick
- calculating the expectation of a random variable
    - can break the random variable into a sum of some random variables, if the other ramdom variables could be *geometric random varaibles* etc, i.e., have property that can be use directly. Check page-33 for details.
- page37, when calculating the expectation of quick-sort, changing the index to enable the calculation
    
### Question
- page-24: Taylor's theorem
- page-29: why the value of z_k in independent of y_(i-1)

