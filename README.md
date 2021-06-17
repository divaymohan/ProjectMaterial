# Link prediction on dynamic disease network.
## What is Link Prediction?

##  What problem we are solving with the help of this project?
 
## what are the similarity score ?

## Methods used 
1. NLP (**Negative Link Prediction**)
2. MLP (**Mixed Link Prediction**) 
3. Batch approach with **MLP**(Mixed Link Prediction) 
4. MLP with **normalized score**.
5. **Supervised Learning**
6. **Supervised learning with MLP**

### Edge selection algorithm

```
Input: Adjacency Matrix, ScoreFunctionMatrix
Output: edge(i,j)
SelectNode:
    MaxIndex=70
    TopRank=-1
    for i=1 to MaxIndex-1 do
        for j=i+1 to MaxIndex do
            if Matrix(i,j)==0 then
                TempRank= ScoreFunctionMatrix(i,j)
                if TempRank>TopRank then
                    x=i
                    y=j
                    TopRank=TempRank
                end if
            end if
        end for
    end for
```

### NLP First (Negative Link Prediction First)
* Introduction :- In NLP first approach we predict all the edges which can be removed in the future.
* Algorithm :-
    1. Calculate Score(i,j) for every i and j.
    2. Select one edge using Edge Selection algorithm such that the edge does not exist in the graph and have highest score.
    

* Results 

### PLP First (Negative Link Prediction First)
* Introduction
* Algorithm
* Results 

### MLP(Mixed Link Prediction)
* Introduction
* Algorithm
* Results

### Batch approach with MLP
* Introduction
* Algorithm
* Results

### MLP on Normalized score
* Introduction
* Algorithm
* Results

### Supervised Learning
* Introduction
* Algorithm
* Results

### Supervised learning with MLP
* Introduction
* Algorithm
* Results

### Resources Used