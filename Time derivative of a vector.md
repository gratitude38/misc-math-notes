Let the vector $\mathbf{A}$ be defined as:


$$
\mathbf{A} = A \mathbf{e}_r
$$


where $A$ is the magnitude of the vector, and $\mathbf{e}_r$ is the unit vector in the radial direction. The unit vector $\mathbf{e}_r$ originates from the origin of the global coordinate system, i.e., $(0, 0, 0)$. Any changes in the magnitude of $\mathbf{A}$ occur along the direction of $\mathbf{e}_r$, which defines the radial direction.

The time derivative of the vector $\mathbf{A}$ is given by:


$$
\frac{d}{dt}\mathbf{A} = \frac{dA}{dt}\mathbf{e}_r + A \frac{d}{dt}\mathbf{e}_r
$$


This expression indicates that over time, the vector $\mathbf{A}$ may change in both its magnitude $A$ and/or its direction, represented by the unit vector $\mathbf{e}_r$. A change in direction is characterised by a variation in the orientation of $\mathbf{e}_r$. Since $\mathbf{e}_r$ is anchored at the origin and only its endpoint moves, this change in direction can be described by the angular variation $\theta$, which measures the difference between the previous and current orientations of $\mathbf{e}_r$.

We can express the unit vector $\mathbf{e}_r$ in terms of the angle $\theta$ as follows:


$$
\mathbf{e}_r = \cos \theta \ \mathbf{e}_x + \sin \theta \ \mathbf{e}_y
$$


where $\mathbf{e}_x$ and $\mathbf{e}_y$ are the unit vectors along the horizontal and vertical axes, respectively, in the Cartesian coordinate system.

It is important to note that changing the orientation angle $\theta$ does not affect the magnitude of the vector. This implies that the direction of angular change, represented by a new unit vector $\mathbf{e}_\theta$, must be perpendicular to $\mathbf{e}_r$. Mathematically, this orthogonality condition is expressed as $\mathbf{e}_r \cdot \mathbf{e}_\theta = 0$. This condition can be satisfied if:


$$
\mathbf{e}_\theta = \begin{bmatrix} 0 & -1 \\ 1 & 0 \end{bmatrix} \mathbf{e}_r = -\sin \theta \ \mathbf{e}_x + \cos \theta \ \mathbf{e}_y
$$


Here, $\mathbf{e}_\theta$ represents the direction of angular motion and is perpendicular to $\mathbf{e}_r$, as required.

Now, we observe that the time derivative of $\mathbf{e}_r$ can be calculated as:


$$
\frac{d}{dt} \mathbf{e}_r = \frac{d \cos \theta}{d \theta} \frac{d \theta}{dt} \ \mathbf{e}_x + \frac{d \sin \theta}{d \theta} \frac{d \theta}{dt} \ \mathbf{e}_y
$$


Simplifying this expression, we get:


$$
\frac{d}{dt} \mathbf{e}_r = \frac{d \theta}{dt} \left( -\sin \theta \ \mathbf{e}_x + \cos \theta \ \mathbf{e}_y \right)
$$

This simplifies further to:


$$
\frac{d}{dt} \mathbf{e}_r = \frac{d \theta}{dt} \mathbf{e}_\theta
$$



Thus, the time derivative of the vector $\mathbf{A}$ can be rewritten as:


$$
\frac{d}{dt} \mathbf{A} = \frac{dA}{dt} \mathbf{e}_r + A \frac{d \theta}{dt} \mathbf{e}_\theta
$$



This final expression clearly shows that the rate of change of $\mathbf{A}$ has two components: the rate of change of the magnitude $A$ in the radial direction $\mathbf{e}_r$, and the rate of change of the angular position $\theta$ in the direction perpendicular to $\mathbf{e}_r$, represented by $\mathbf{e}_\theta$.











---

