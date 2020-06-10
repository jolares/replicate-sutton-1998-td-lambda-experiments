# Replicating Sutton's 1988 TD(λ) Random Walk Experiments

This project implemented the random walk experiments found in Sutton's 1998 [Learning to Predict by the Methods of
Temporal Differences](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf), and replicates the original work's figures 3, 4, and 5 using the TD(λ) update rule introduced in the paper.

The dataset generation process and empirical steps seek to resemble the original work as closely as possible. A few number of assumptions are taken as a result of the paper not explicitly stating some of the learning
hyperparameters and convergence criteria. However, enough insight was derived from the paper as to allow for empirical reproduction. The obtained results support the original work's claims with regards to the
computational, peak performance, and prediction accuracy advantages of Temporal Difference (TD) learning methods over the
conventional supervised-learning ones available at the time, in the context of solving the multi-step prediction problem 
in dynamic environments such as the random walk.

Altho there is enough information out there with regards to this experiment, implementation details are not shared as this project is often part of many graduate computer science degree programs, and self learning and academic integrity is always encouraged.

## Resources

[1] [Learning to Predict by the Methods of Temporal Differences](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf)
