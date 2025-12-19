---
layout: project
title: ENGRD 2020 Actuator
description: class project

image: /assets/actuator.pdf
---


#### Constraints/Objectives
I was tasked with designing a mechanism that utilizes an actuator, a rigid beam, and pins to lift the heaviest weight to the highest height. This is to be done in a 150 cm by 50 cm, 2-D space.

#### Design Degrees of Freedom
Because of the pins put in place, there are no translational degrees of freedom. There is 1 rotational degree of freedom in the k̂ direction.

#### Static Analysis
The actuator is placed as far from the center pin as possible in order to produce the most amount of torque. The mass is placed at half the distance because it balances increasing both the maximum weight of the mass, as well as the maximum height it can rise to. I chose the RSX actuator because it was capable of producing 294 kN, the most amount of force from the provided catalog of actuators. As a result, by doing a moment balance about the center pin and creating the expression (294 kN)(70 cm) = max w(35 cm), the maximum weight of the mass is calculated to be 588 kN. In order to calculate the maximum height, I used the Pythagorean Theorem with the hypotenuse and horizontal component at the mass' point. By taking the square root of (106.065 squared + 105 squared), I get 15 cm.