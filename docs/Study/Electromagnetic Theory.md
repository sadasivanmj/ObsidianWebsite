# Theory
==Insert Second Sem Concepts==

## Maxwells equation in Matter
>[!REVIEW]
>1. $\nabla \cdot E = \frac{\rho}{\epsilon_0}$
>2. $\nabla \cdot B = 0$
>3. $\nabla \times E = -\frac{dB}{dt}$
>4. $\nabla \times B = \mu_0 J + \mu_0 \epsilon_0 \frac{dE}{dt}$

Inside a polarized material there will be accumulation of bound charge and current.
In static case
	$\rho_b = -\nabla \cdot P$
	$J_b = \nabla \times M$
In non static case there will also be a polarization current due to any change in electric polarization
	$J_p = \frac{\partial P}{\partial t}$
	also it is consistent with continuity equation $\nabla \cdot J = \frac{\partial (\nabla \cdot P)}{\partial t} = -\frac{\partial \rho_b}{\partial t}$
Now we have 
	$\rho = \rho_f + \rho_b = \rho_f - \nabla \cdot P$
and
	$J=J_f + J_b + J_p = J_f + \nabla \times M + \frac{\partial P}{\partial t}$
Substituting  this in to maxwells equation 1 we get
	$\nabla \cdot E = \frac{\rho_f + \rho_b}{\epsilon_0} = \frac{1}{\epsilon_0}(\rho_f - \nabla \cdot P)$
	i.e $\nabla \cdot \epsilon_0 E + \nabla \cdot P = \rho_f$
	$\implies \nabla \cdot (\epsilon_0 E + P) = \rho_f$
	Where as $D = \epsilon_0 E + P$
	$\nabla \cdot D = \rho_f$

And Similarly
	Substituting Eq of J in Eq 4 of review we get
	 $\nabla \times H = J_f + \frac{dD}{dt}$
	 where $H = \frac{B}{\mu_0} - M$

>[!IMPORTANT]
>1. $\nabla \cdot D = \rho_f$
>2. $\nabla \cdot B = 0$
>3. $\nabla \times E = -\frac{dB}{dt}$
>4. $\nabla \times H = J_f + \frac{dD}{dt}$


## Conservation Laws
==LEAVE SPACE FOR COMPLETION==

### Momentum


## Electromagnetic Waves
What is a [[Wave]] ?
> Wave is a disturbance of a continues medium that propagates with a fixed shape at a continues velocity

## Electrodynamics and Relativity
### Relativity 
[[Relativity]]

>[!Einsteins Postulates]
>1. Laws of physics apply in all inertial frames
>2. Speed of light is constant

Inference of Einsteins postulates
	- **Simultaneity** : Lack there of 
	- **Time Dilation** : $t' = \frac{t}{\gamma}$
	- Length Contraction $l'=\gamma l$
### Lorentz transformation
$x'=\gamma (x-\frac{v}{t})$
$y'=y$
$z'=z$
$t'=\gamma (t-\frac{vx}{c^2})$
#### Addition of velocity
$u'=\frac{u-v}{1-\frac{uv}{c^2}}$
### Structure of Space time
#### Four Vector
$\bar{x^0} = \gamma(x^0-\beta x^1)$
$\bar{x^1} = \gamma(x^1-\beta x^0)$
$\bar{x^2} = x^2$
$\bar{x^3}= x^3$

$$
\begin{bmatrix}
\bar{x^0} \\
\bar{x^1} \\
\bar{x^2} \\
\bar{x^3}
\end{bmatrix}
=
\begin{bmatrix}
\gamma & -\gamma \beta & 0 & 0\\
-\gamma \beta & \gamma & 0 & 0\\
0 & 0& 1 & 0\\
0 & 0 & 0 & 1
\end{bmatrix}
\begin{bmatrix}
x^0\\
x^1\\
x^2\\
x^3
\end{bmatrix}
$$
It can be written as $\bar{x^\mu}=\sum_{\nu=0}^{3} \Lambda_{\nu}^{\mu} x^\nu$
where $\mu$ - row $\nu$ - column
Generally $\bar{a^\mu}=\sum_{\nu=0}^{3} \Lambda_{\nu}^{\mu} a^\nu$
##### Four Vector Dot Product
$a^\mu$ - Contravarient = $(a^0,a^1,a^2,a^3)$
$a_\mu$ - Covarient = $(a_0,a_1,a_2,a_3)$ = $(-a^0,a^1,a^2,a^3)$
$a^{\mu}b_{\mu} = -a^0b^0 +a^1b^1+a^2b^2+a^3b^3$
>[!Definition]
>[**Rapidity**](https://en.wikipedia.org/wiki/Rapidity) : In [relativity](https://en.wikipedia.org/wiki/Theory_of_relativity "Theory of relativity"), **rapidity** is commonly used as a measure for [relativistic velocity](https://en.wikipedia.org/wiki/Relativistic_velocity "Relativistic velocity"). Mathematically, rapidity can be defined as the [hyperbolic angle](https://en.wikipedia.org/wiki/Hyperbolic_angle "Hyperbolic angle") that differentiates two [frames of reference](https://en.wikipedia.org/wiki/Frames_of_reference "Frames of reference") in relative motion, each frame being associated with [distance](https://en.wikipedia.org/wiki/Distance "Distance") and [time](https://en.wikipedia.org/wiki/Time "Time") coordinates.

$a^{\mu}a_{\mu} > 0$ - Spacelike
$a^{\mu}a_{\mu} < 0$ - Timelike
$a^{\mu}a_{\mu} = 0$ - Light like
#### Displacement four vector
Say and event 'A' occurs at $(x^0_A,x^1_A,x^2_A,x^3_A)$ and B at $(x^0_B,x^1_B,x^2_B,^3_B)$
Interval between Events I = $(\Delta x)^\mu (\Delta x)_\mu = (\Delta x^0)^2 + (\Delta x^1)^2 + (\Delta x^2)^2 + (\Delta x^3)^2 = -c^2t^2 +d^2$ 
Where $-c^2t^2$ is the time interval and $d^2$ is the distance interval (?)


# Theory
==Insert Second Sem Concepts==

## Maxwells equation in Matter
>[!REVIEW]
>1. $\nabla \cdot E = \frac{\rho}{\epsilon_0}$
>2. $\nabla \cdot B = 0$
>3. $\nabla \times E = -\frac{dB}{dt}$
>4. $\nabla \times B = \mu_0 J + \mu_0 \epsilon_0 \frac{dE}{dt}$

Inside a polarized material there will be accumulation of bound charge and current.
In static case
	$\rho_b = -\nabla \cdot P$
	$J_b = \nabla \times M$
In non static case there will also be a polarization current due to any change in electric polarization
	$J_p = \frac{\partial P}{\partial t}$
	also it is consistent with continuity equation $\nabla \cdot J = \frac{\partial (\nabla \cdot P)}{\partial t} = -\frac{\partial \rho_b}{\partial t}$
Now we have 
	$\rho = \rho_f + \rho_b = \rho_f - \nabla \cdot P$
and
	$J=J_f + J_b + J_p = J_f + \nabla \times M + \frac{\partial P}{\partial t}$
Substituting  this in to maxwells equation 1 we get
	$\nabla \cdot E = \frac{\rho_f + \rho_b}{\epsilon_0} = \frac{1}{\epsilon_0}(\rho_f - \nabla \cdot P)$
	i.e $\nabla \cdot \epsilon_0 E + \nabla \cdot P = \rho_f$
	$\implies \nabla \cdot (\epsilon_0 E + P) = \rho_f$
	Where as $D = \epsilon_0 E + P$
	$\nabla \cdot D = \rho_f$

And Similarly
	Substituting Eq of J in Eq 4 of review we get
	 $\nabla \times H = J_f + \frac{dD}{dt}$
	 where $H = \frac{B}{\mu_0} - M$

>[!IMPORTANT]
>1. $\nabla \cdot D = \rho_f$
>2. $\nabla \cdot B = 0$
>3. $\nabla \times E = -\frac{dB}{dt}$
>4. $\nabla \times H = J_f + \frac{dD}{dt}$


## Conservation Laws
==LEAVE SPACE FOR COMPLETION==

### Momentum


## Electromagnetic Waves
What is a [[Wave]] ?
> Wave is a disturbance of a continues medium that propagates with a fixed shape at a continues velocity

## Electrodynamics and Relativity
### Relativity 
[[Relativity]]

>[!Einsteins Postulates]
>1. Laws of physics apply in all inertial frames
>2. Speed of light is constant

Inference of Einsteins postulates
	- **Simultaneity** : Lack there of 
	- **Time Dilation** : $t' = \frac{t}{\gamma}$
	- Length Contraction $l'=\gamma l$
### Lorentz transformation
$x'=\gamma (x-\frac{v}{t})$
$y'=y$
$z'=z$
$t'=\gamma (t-\frac{vx}{c^2})$
#### Addition of velocity
$u'=\frac{u-v}{1-\frac{uv}{c^2}}$
### Structure of Space time
#### Four Vector
$\bar{x^0} = \gamma(x^0-\beta x^1)$
$\bar{x^1} = \gamma(x^1-\beta x^0)$
$\bar{x^2} = x^2$
$\bar{x^3}= x^3$

$$
\begin{bmatrix}
\bar{x^0} \\
\bar{x^1} \\
\bar{x^2} \\
\bar{x^3}
\end{bmatrix}
=
\begin{bmatrix}
\gamma & -\gamma \beta & 0 & 0\\
-\gamma \beta & \gamma & 0 & 0\\
0 & 0& 1 & 0\\
0 & 0 & 0 & 1
\end{bmatrix}
\begin{bmatrix}
x^0\\
x^1\\
x^2\\
x^3
\end{bmatrix}
$$
It can be written as $\bar{x^\mu}=\sum_{\nu=0}^{3} \Lambda_{\nu}^{\mu} x^\nu$
where $\mu$ - row $\nu$ - column
Generally $\bar{a^\mu}=\sum_{\nu=0}^{3} \Lambda_{\nu}^{\mu} a^\nu$
##### Four Vector Dot Product
$a^\mu$ - Contravarient = $(a^0,a^1,a^2,a^3)$
$a_\mu$ - Covarient = $(a_0,a_1,a_2,a_3)$ = $(-a^0,a^1,a^2,a^3)$
$a^{\mu}b_{\mu} = -a^0b^0 +a^1b^1+a^2b^2+a^3b^3$
>[!Definition]
>[**Rapidity**](https://en.wikipedia.org/wiki/Rapidity) : In [relativity](https://en.wikipedia.org/wiki/Theory_of_relativity "Theory of relativity"), **rapidity** is commonly used as a measure for [relativistic velocity](https://en.wikipedia.org/wiki/Relativistic_velocity "Relativistic velocity"). Mathematically, rapidity can be defined as the [hyperbolic angle](https://en.wikipedia.org/wiki/Hyperbolic_angle "Hyperbolic angle") that differentiates two [frames of reference](https://en.wikipedia.org/wiki/Frames_of_reference "Frames of reference") in relative motion, each frame being associated with [distance](https://en.wikipedia.org/wiki/Distance "Distance") and [time](https://en.wikipedia.org/wiki/Time "Time") coordinates.

$a^{\mu}a_{\mu} > 0$ - Spacelike
$a^{\mu}a_{\mu} < 0$ - Timelike
$a^{\mu}a_{\mu} = 0$ - Light like
#### Displacement four vector
Say and event 'A' occurs at $(x^0_A,x^1_A,x^2_A,x^3_A)$ and B at $(x^0_B,x^1_B,x^2_B,^3_B)$
Interval between Events I = $(\Delta x)^\mu (\Delta x)_\mu = (\Delta x^0)^2 + (\Delta x^1)^2 + (\Delta x^2)^2 + (\Delta x^3)^2 = -c^2t^2 +d^2$ 
Where $-c^2t^2$ is the time interval and $d^2$ is the distance interval (?)


