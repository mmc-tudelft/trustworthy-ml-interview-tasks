Data analysis assignment
=====


This repository contains a notebook with the data analysis assignment for the Trustworthy ML PhD position.

The notebook involves data, which is synthesized based on the [bank telemarketing dataset](https://www.researchgate.net/publication/260805594_A_Data-Driven_Approach_to_Predict_the_Success_of_Bank_Telemarketing). A detailed description of the included variables (columns) can be found in the [UCI repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).


_Being synthesized, the data may not 100% share characteristics with the 'official' bank telemarketing dataset. The candidate is asked to assume they only have the synthesized dataset at hand._

We are interested in classifying the variable _y_: whether a client subscribed to a term deposit, and want to use several basic classifiers in the `sklearn` package for this, based on a cross-validation procedure.

We put some starter code for this in a notebook, which deliberately has some problematic aspects to it. Candidates are asked to transform the notebook into a more trustworthy and more appropriate implementation.

More specifically, we ask for the candidates to:
- investigate and justify pre-processing steps to be performed on the data;
- correct the implementation into a proper cross-validation procedure;
- choose and justify evaluation strategies for the given problem.

We will discuss the candidate's solution during the interview.
