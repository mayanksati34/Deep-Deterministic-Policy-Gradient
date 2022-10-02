# Deep Deterministic Policy Gradients
<b> References : </b>
<br> Deterministic Policy Gradient Algorithms : http://proceedings.mlr.press/v32/silver14.pdf
<br> Continuous control with deep reinforcement learning : https://arxiv.org/abs/1509.02971



<ul>
  <li> In Policy Gradient algorithms, policy is represented by a parametric probability distribution that stochastically selects action a in state s according to parameter vector θ.
  <li> In our project we instead consider deterministic policies.
  <li> In the deterministic case it only integrates over the state space, so computing the stochastic policy gradient may require more samples.
  <li> In order to explore the full state and action space, a stochastic policy is often necessary. To ensure that the deterministic policy gradient algorithms continue to explore satisfactorily, an off-policy actor-critic algorithm was used.
</ul>

## Results On OpenAI Gym Environments:
### Pendulum V1 (256 * 256 Network)
![plot](./results/ddpg1.png)
### Pendulum V1 (512 * 512 Network)
![plot](./results/ddpg2.png)
### Pendulum V1 (Mountain Car Continuous)
![plot](./results/ddpg3.png)
