The inverted cart pendulum system serves as a classic benchmark problem for studying the control of dynamical systems, featuring a cart connected to a pole along a track. This system presents a challenging control problem due to its non-linear, unstable and under-actuated dynamics.

The objective in this repository, is to determine the optimal action selection policy using a Q-learning algorithm to maintain upright balance of the pole by forcing the cart to the left or right. The environment developed discretizes the continuous state space, drawing inspiration from Gym’s cart-pole environment. Acheiving the optimal action selection policy is obtain through careful tuning of the Q-learning parameters.

<p align="center">
  <video src="" width=400/>
<p/>

The short clip above displays the resulting dynamics of the inverted cart pendulum when controlled by the action selection policy obtained from the Q-learning model.


