---
layout: project
title: ENGRD 2020 - OLHW5b
description: Static Mechanical Analysis 
technologies: [Autodesk Fusion]
image: /assets/images/radio-machine-cad.jpg
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

Now, instead of relying on grip strength to apply the input force, modify your design to use a linear actuator.

### (i) Actuator Selection

Pick a linear actuator from the following website, taking into account:

- Force output  
- Size  
- Stroke length  

Website:  
https://www.progressiveautomations.com/collections/linear-actuators


# Constraints & Input Parameters
- Average diameter of a macademia nut = 1 in (Source: Aloha Farms Hawaii)
- Maximum grip strength of adult human female = 329 N (Source: The National Institute of Health NIH)
- Average hardness of cracking a full size macademia nut = 222.18 kg (Source: Schrauf et. al. 2008) which is equivalent to 2178 N of force

---

# Approach
## Plan 
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

The mechanical advantage is given by $MA = \frac{F_{out}}{F_{in}}$.

$$
MA = \frac{L_{effort}}{L_{load}}
$$

$$
\begin{aligned}
MA &= \frac{F_{out}}{F_{in}} \\
F_{out} &= MA \cdot F_{in}
\end{aligned}
$$

Nulla et magna urna. Morbi a ipsum sollicitudin, rhoncus risus volutpat, ultricies nunc. Quisque mollis finibus ante id imperdiet. Quisque vehicula elit sit amet felis facilisis fermentum.

![Shaded rendering of earlier version]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Nulla et magna urna. Morbi a ipsum sollicitudin, rhoncus risus volutpat, ultricies nunc. Quisque mollis finibus ante id imperdiet. Quisque vehicula elit sit amet felis facilisis fermentum.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

I was inspired by this old radio when I made this rendering:

![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.

Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.
