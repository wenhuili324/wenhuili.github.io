---
title:  "Nanoparticle Encapsulation by Protein"
layout: post
mathjax: true
categories: media
---
Encapsulation of nanoparticles within encapsulins—protein-based nanocompartments found in prokaryotes—has emerged as a promising strategy for targeted delivery, bio-catalysis, and nanomaterial design. These naturally occurring protein cages offer precise size control, biocompatibility, and the potential for functional modification, making them ideal carriers for therapeutic agents, imaging probes, and catalytic nanoparticles. Despite their growing applications, the microscopic mechanisms governing the selective encapsulation process remain poorly understood. Critical questions persist regarding how cargo peptides direct nanoparticle loading, how protein-nanoparticle interactions guide encapsulation efficiency, and how structural dynamics influence cargo selectivity. These knowledge gaps limit our ability to rationally design encapsulin-based systems with predictable performance. A deeper understanding of the molecular-scale interactions and energetics involved in nanoparticle encapsulation is essential for advancing the design of programmable nanoreactors and next-generation delivery platforms.

We integrated molecular dynamics (MD) simulations with experimental data to investigate the microscopic mechanisms underlying the roles of peptides and ligands in nanoparticle encapsulation. Our findings reveal that charged ligands provide the primary driving force—electrostatic interactions—that promote the assembly of protomers into a protein cage. Meanwhile, peptides extend the effective interaction range of nanoparticles, counteracting entropic penalties and enhancing nanoparticle stability in solution. Additionally, ligands help stabilize the outward extension of peptides, further increasing the interaction range and facilitating encapsulation.

Another key insight is that, for efficient encapsulation, the interaction strength between nanoparticles and protomers must be at least comparable to that between protomers themselves. However, if the nanoparticle–protomer interaction is too strong, it can lead to kinetic trapping, where assembly errors become locked in and cannot be corrected through self-organization. This highlights the need for a delicate balance in interaction strengths to ensure both stability and proper assembly. 

![PMF Simulation system](/assets/PMF_System.png)

## MD simulation system for calculating potential of mean force (PMF) between nanoparticle and protomer

![TEM](/assets/TEM.png)

## TEM image of encapsulated nanopaticles functionalized by ligands and peptides

<!--
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Curabitur pretium tincidunt lacus. Nulla gravida orci a odio. Nullam varius, turpis et commodo pharetra, est eros bibendum elit, nec luctus magna felis sollicitudin mauris. Integer in mauris eu nibh euismod gravida. Duis ac tellus et risus vulputate vehicula. Donec lobortis risus a elit.


## Heading Two (h2)

### Heading Three (h3)

#### Heading Four (h4)

##### Heading Five (h5)

###### Heading Six (h6)


## Blockquotes

### Single line

> My mom always said life was like a box of chocolates. You never know what you're gonna get.

### Multiline

> What do you get when you cross an insomniac, an unwilling agnostic and a dyslexic?
>
> You get someone who stays up all night torturing himself mentally over the question of whether or not there's a dog.
>
> – _Hal Incandenza_

## Horizontal Rule

---

## Table

| Title 1          | Title 2          | Title 3         | Title 4         |
|------------------|------------------|-----------------|-----------------|
| First entry      | Second entry     | Third entry     | Fourth entry    |
| Fifth entry      | Sixth entry      | Seventh entry   | Eight entry     |
| Ninth entry      | Tenth entry      | Eleventh entry  | Twelfth entry   |
| Thirteenth entry | Fourteenth entry | Fifteenth entry | Sixteenth entry |

## Code

Source code can be included by fencing the code with three backticks. Syntax highlighting works automatically when specifying the language after the backticks.

````
```javascript
function foo () {
    return "bar";
}
```
````

This would be rendered as:

```javascript
function foo () {
    return "bar";
}
```

## Lists

### Unordered

* First item
* Second item
* Third item
    * First nested item
    * Second nested item

### Ordered

1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item
-->
