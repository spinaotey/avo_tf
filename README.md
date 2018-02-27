#Adversarial Variational Optimization in Tensorflow

In this repository we will implement and reproduce the first two examples of the [Adversarial Variational Optimization of Non-Differentiable Simulators](https://arxiv.org/abs/1707.07113) paper from Gilles Louppe and Kyle Cranmer by using tensorflow.

The implementation was heavly inspired by [Stefan Webb's repository](https://github.com/stefanwebb/adversarial-variational-optimization) aiming for the same goal. Some modifications include fixing code bugs, separating the simulator from the tensorflow environment, etc.

Current work is done in replacing the resampling in the simulator by reweighting some nominal initial samples.
