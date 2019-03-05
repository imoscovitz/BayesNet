# BayesNet
LISP implementation of a Bayesian DAG Classifier

Constructs a DAG whose nodes are interrelated belief probabilities. 
As new information is acquired, algorithm works by calling interrelated recursive formulas to propogate messages to update parent and child probabilities.

For a full description of the theory and algorithm, see Neopolitan, [_Probabilistic reasoning in expert systems: theory and algorithms_](https://dl.acm.org/citation.cfm?id=77340), pp 160-162, 217-231.
