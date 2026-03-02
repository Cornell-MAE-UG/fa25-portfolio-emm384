---
layout: project
title: ENGRD 2020 - OLHW5b
description: Static Mechanical Analysis - Macademia Nut Cracker 
technologies: 
image: /assets/images/OLHW5.png
---

# Design Problem

Imagine you have a macadamia nut that you want to crack open by hand using a simple lever nutcracker.



## (a) Mechanical Design and Analysis

Draw a figure of the nut cracker with the nut when it’s about to crack. Calculate the necessary dimensions of the nutcracker and come up with a design to make this task feasible. You can assume a very simple geometry for the nutcracker to make your calculations easier.

### (i) Required Inputs

You will need to find typical values for the inputs, such as:

- Average size of macadamia nuts  
- Maximum human grip strength  

### (ii) Required Cracking Load

The average load required to crack a macadamia nut can be found in the appendix section of the following paper:

> Schrauf et al.  
> *Do capuchin monkeys use weight to select hammer tools?*  
> Animal Cognition 11, 413–422 (2008)  
> https://doi.org/10.1007/s10071-007-0131-2  

## (b) Usability Discussion

Discuss the usability of the nutcracker that you designed. 

## (c) Linear Actuator Modification
*This section was part of the original problem but will not be included in this published analysis*

Now, instead of relying on grip strength to apply the input force, modify your design to use a linear actuator.

### (i) Actuator Selection

Pick a linear actuator from the following website, taking into account:

- Force output  
- Size  
- Stroke length  

Website:  
https://www.progressiveautomations.com/collections/linear-actuators



---
## Constraints & Input Parameters
- Average diameter of a macademia nut = 1 in (Source: Aloha Farms Hawaii)
- Maximum grip strength of adult human female = 329 N (Source: The National Institute of Health NIH)
- Average hardness of cracking a full size macademia nut = 222.18 kg (Source: Schrauf et. al. 2008) which is equivalent to 2178 N of force

---

## Approach
- Construct free body diagram of generic handheld nutcracker
![Whole mechanism FBD]({{ "/assets/images/OLHW5.png" | relative_url }}){:style="width: 400px"}

- Contruct exploded free body diagrams for an individual part of the overall mechanism

![Exploded mechanism FBD]({{ "/assets/images/OLHW5-2.png" | relative_url }}){:style="width: 400px"}

- Derive a relationbship for relevant dimensions $(L_1 & L_2)$ using input parameters and equillibrum equations derived from free body diagrams from previous two steps 

$$
\sum M_A = 0 = F_N L_1 - F_g L_2 \\
F_N L_1 = F_g L_2 \\ 
\frac{F_N}{F_g} = \frac{L_2}{L_1} = \frac{2178 N}{329 N} = 6.62 \\
L_2 = 6.62 L_1 \\
$$

 - Design Choice: Let $L_1 = $ 2.25 the average diameter of a macademia nut 

$$
L_1 = 2.25(1 in) = 2.25 in \\ 
L_2 = 6.62(2.25 in) = 14.9 in \\
$$

---
## Discussion of Usability

