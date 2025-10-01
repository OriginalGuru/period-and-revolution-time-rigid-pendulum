# period-and-revolution-time-rigid-pendulum

In this assignment, you will extract the period and revolution time for the nonlinear pendulum in two ways:
1. using `event` in `solve_ivp`, and;
2. using `quad` on the integral form.

**Useful definitions:**
1. The revolution time $T_{rev}$ is the time for the pendulum angle $\theta$ to change by $2\pi$.
2. The period $T$ is the peak-to-peak time in $\theta$.
3. The total energy of the rigid pendulum is $U(\dot{\theta},\theta) = \frac{1}{2} I \dot{\theta}^2 + I\omega_0^2 (1 - cos(\theta))$. $I$ is the moment of inertial; $\omega_0$ is the natural frequency.

**Assignment:**
In Colab, using text and code cells, create a structured Python notebook with the following elements.
1. Write pseudocode explaining your approach.
2. Extract $T$ and $T_{rev}$ versus the initial angular velocity (`ang_vel_0`).
3. Define and solve (numerically) the integral form for $T$ and $T_{rev}$.
4. Plot these two results together in a labeled figure.

**Submit your Colab notebook through the assignment GitHub repository**
