# Non-Gaussian  Risk  Bounded  Trajectory  Optimization  for  Stochastic Nonlinear  Systems  in  Uncertain  Environments

39th IEEE Conference on Robotics and Automation (ICRA), 2022, https://arxiv.org/abs/2203.03038

---

# 1. Risk Bounded Trajectory Planning

We address the risk bounded trajectory optimization problem of stochastic nonlinear robotic systems. More precisely, we consider the motion planning problem in which the robot has stochastic nonlinear dynamics and uncertain initial locations, and the environment contains multiple dynamic
uncertain obstacles. The uncertain obstacle can be of arbitrary shape, can deform over time, can move, and has arbitrary uncertainty. The goal is to plan a sequence of control inputs for the robot to navigate to the target while bounding the probability of colliding with obstacles. In this paper, we deal with stochastic nonlinear models, nonlinear safety constraints, and arbitrary probabilistic uncertainties (without the need for linearization or Gaussian approximation), the most general setting ever considered.


# 2. Existing Methods

Existing approaches to address risk bounded trajectory optimization problems either are limited to particular classes of models and uncertainties such as Gaussian linear problems or rely on sampling-based methods.


![myImage](https://github.com/jasour/Non-Gaussian_Risk-Bounded_TrajOpt/blob/main/Animations/Uncertainty_Propagation.gif)
[<ins>Left</ins>: *Sampling-based representation of uncertainties*] Sampling-based methods use a large number of uncertainty samples in the planning process; Hence, they are computationally expensive and cannot guarantee the safety of the original uncertain system.
[<ins>Middle</ins>: *Gaussian approximation of uncertainties*] Gaussian linear methods use linearized models and Gaussian approximation of the uncertainties and therefore they cannot guarantee the safety of the original uncertain system.
[<ins>Right</ins>: *Non-Gaussian uncertainties*] We use nonlinear stochastic models where uncertainties are not necessarily Gaussian and generate plans with guaranteed bounded risk.

# 3. Our Approach

To address the risk bounded trajectory optimization problem, we first formulate the problem as an optimization problem with stochastic dynamics equations and chance constraints. We then convert probabilistic constraints and stochastic dynamics constraints on random variables into a set of deterministic
constraints on the moments of state probability distributions. Finally, we solve the resulting deterministic optimization problem using nonlinear optimization solvers and get a sequence of control inputs.

**3.1. Uncertainty Propagation**

**3.2. Probabilistic Constraints**

<p align="center">
  <img src="https://github.com/jasour/Non-Gaussian_Risk-Bounded_TrajOpt/blob/main/Animations/Approach.png" width="600" height="700">
</p>


---

# Background Information

[Moments-Based Deterministic/Probabilistic Optimization and Planning](https://ocw.mit.edu/courses/16-s498-risk-aware-and-robust-nonlinear-planning-fall-2019/)


# Contact


Ashkan Jasour: jasour@mit.edu

Weiqiao Han: weiqiaoh@mit.edu


