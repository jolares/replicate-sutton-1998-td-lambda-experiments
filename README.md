# Replicating Sutton's 1988 TD(λ) Random Walk Experiments


This project replicates the _Random Walk_ experiments found in Sutton's 1998 paper [Learning to Predict by the Methods of
Temporal Differences](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf), with the goal of generating the original work's figures 3, 4, and 5, by implementing the _TD(λ) update rule_ introduced in the paper.

The dataset generation process and empirical steps seek to resemble, as close as possible, the one of the paper. A number of assumptions are taken as a result of the paper not explicitly stating some empirical details such as the values for certain learning
hyperparameters, and convergence criteria; however, enough insight is derived from the paper as for this project to achieve empirical replication.

The obtained results support the original work's claims with regards to the
computational, peak performance, and prediction accuracy advantages of Temporal Difference (TD) learning methods over the ones of
conventional supervised-learning available at the time, in the context of solving the multi-step prediction problem 
within dynamic environments such as that of the _bounded random walk_.

Please inquire for more details about this project. Despite the abundant amount of information out there with regards to the task of replicating Sutton1988, the implementation details of this project are not shared in the public domain as the activities involved in the replication of this paper are often part of the learning experience of many graduate Computer Science programs; self learning and academic integrity is encouraged.


## Resources


[1] [Learning to Predict by the Methods of Temporal Differences](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf)

[2] [Georgia Tech's Graduate Reinforcement Learning course offered through Udacity.com](https://www.udacity.com/course/reinforcement-learning--ud600)
