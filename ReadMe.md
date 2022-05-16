# Non-Gaussian  Risk  Bounded  Trajectory  Optimization  for  Stochastic Nonlinear  Systems  in  Uncertain  Environments

39th IEEE Conference on Robotics and Automation (ICRA), 2022, https://arxiv.org/abs/2203.03038

---

# 1. Risk Bounded Trajectory Planning

We address the risk bounded trajectory optimization problem of stochastic nonlinear robotic systems. More precisely, we consider the motion planning problem in which the robot has stochastic nonlinear dynamics and uncertain initial locations, and the environment contains multiple dynamic
uncertain obstacles. The uncertain obstacle can be of arbitrary shape, can deform over time, can move, and has arbitrary uncertainty. The goal is to plan a sequence of control inputs for the robot to navigate to the target while bounding the probability of colliding with obstacles. In this paper, we deal with stochastic nonlinear models, nonlinear safety constraints, and arbitrary probabilistic uncertainties (without the need for linearization or Gaussian approximation), the most general setting ever considered.


# 2. Existing Methods

Existing approaches to address risk bounded trajectory optimization problems are limited to particular classes of models and uncertainties such as Gaussian
linear problems.



# 3. Our Approach

To address the risk bounded trajectory optimization problem, we first formulate the problem as an optimization problem with stochastic dynamics equations and chance constraints. We then convert probabilistic constraints and stochastic dynamics constraints on random variables into a set of deterministic
constraints on the moments of state probability distributions. Finally, we solve the resulting deterministic optimization problem using nonlinear optimization solvers and get a sequence of control inputs.

**3.1. Uncertinty Propagation**

**3.2. Probabilistic Constraints**

---

# Background Information

[Moments-Based Deterministic/Probabilistic Optimization and Planning](https://ocw.mit.edu/courses/16-s498-risk-aware-and-robust-nonlinear-planning-fall-2019/)


# Contact


Ashkan Jasour: jasour@mit.edu

Weiqiao Han: weiqiaoh@mit.edu


