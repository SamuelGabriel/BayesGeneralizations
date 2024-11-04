## Bayes' Power for Explaining In-Context Learning Generalizations

> This repository is frozen at the state of the submission all funcionality is copied to the actively maintained repository [github.com/automl/PFNs](https://github.com/automl/PFNs)

This repository contains the code for the paper "Bayes' Power for Explaining In-Context Learning Generalizations".

Install in editable mode:
```bash
pip install -e .
```

We have a set of notebooks in this repository to reproduce the results of our paper.

- To reproduce the main ICL experiments, use the notebook `discrete_bayes.ipynb`.
- To run the Tiny-MLP generalization experiments, where we evaluate extrapolation, use the notebook `Tiny_MLP_Generalization.ipynb`.
- To run the Coin-Flipping experiments, where we show that the true posterior converges to the wrong probability, use the notebook `Cointhrowing_converging_to_wrong_posterior.ipynb`.
- To see the GP converging to the wrong solution for a step function, use the notebook `GP_fitting_a_step.ipynb`.
