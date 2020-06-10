# Replicating Sutton's 1998 TD(λ) Random Walk Experiments

This project implemented the random walk experiments introduced in Sutton's 1998 paper [Learning to Predict by the Methods of
Temporal Differences](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf) and replicates the original work's figures
3, 4, and 5 using the introduced TD(λ) update rule.

The dataset generation process and empirical is described in detail and seek to resemble the original work as closely
as possible. A few number of assumptions are taken as a result of the paper not explicitly stating some of the learning
hyperparameters and convergence criteria. However, the paper provides enough insight and flexibility as to reproduce the
experiments, and the results obtained support the original work's claims with regards to the
computational, peak performance, and prediction accuracy advantages of Temporal Difference (TD) learning methods over the
conventional supervised-learning ones available at the time, in the context of solving the multi-step prediction problem 
in dynamic environments such as the random walk.

## Resources

[1] [Learning to Predict by the Methods of Temporal Differences](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf)
