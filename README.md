# Motion-of-Sedimenting-Particle

## Introduction

This project is being used for the purpose of enhancing abilities toward the use of numerical methods applied in the context of physical problems that are described by differential equations.

## Dynamic of Sedimenting Particle

### Linear Analysis 

The dynamics of a sedimenting particle will be studied by applying a free-body diagram to the particle, in order to understand the forces that are acting on the particle’s motion, as illustrated in the image below:

<p align="center">
  <img src="https://github.com/arthurhsalgado/Motion-of-Sedimenting-Particle/blob/main/Imagem_ProblemaFisico.PNG?raw=true" width="400" height = "400">
</p>

The forces acting in the particle are:

$$
fe = \frac{4}{3}\pi \rho_f a^3
$$
$$
fp = \frac{4}{3}\pi \rho_s a^3
$$
$$
fa  =  6\pi \eta a v_z
$$

In this context, the equation of motion for the particle is:

$$
m_p \frac{d v_z}{dx} =  - 6\pi\eta av_z + \frac{4}{3} \pi a^3\Delta \rho g
$$

Considering the Stoke-Velocity as:

$$
v_s = \frac{2}{9}\frac{a^2}{\eta}\Delta \rho g
$$

By introducing a time constant for the Stoke’s velocity and performing a change of variables

$$
t^\ast = t\frac{v_s}{a}; v^\ast_z = \frac{v_z}{a}
$$

It is then necessary to express the derivative in terms of the new variables, as follows:

$$
\frac{d v_z}{dt} = \frac{v_s^2}{a}\frac{d v^\ast _z}{dt^\ast}
$$

Applying theses substituions in the equation of motion results in:

$$
m_p \frac{v_s^2}{a}\frac{d v^\ast _z}{dt^\ast} =  - 6\pi\eta a v^\ast_zv_s + \frac{4}{3} \pi a^3\Delta \rho g
$$

The equation can then be nondimensionalized, yielding:

$$
St\frac{d v^\ast _z}{dt^\ast} =  -v^\ast_z + 1; St =  \frac{m_p v_s}{6 \pi \eta a^2}
$$

The linear differential equation has the following analytic solution:

$$
v^\ast _z(t) = 1 - e^{-t/St} 
$$

### Non Linear Analysis


## Numerical Methods

## Results
