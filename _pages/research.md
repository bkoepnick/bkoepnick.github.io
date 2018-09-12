---
permalink: /research/
title: "Research"
---

## _De novo_ protein design in Foldit

![Foldit design](/images/foldit-design-screenshot-small.png){: .align-right}

I develop protein design tools for the crowdsourcing game [Foldit](https://fold.it), and set up protein design challenges for Foldit players. Then I analyze Foldit players' solutions, and test their protein designs in the lab. The results of these tests and analyses are used to inform the next iteration of challenges and the development of new design tools. 

Foldit players help us address two problems in protein design:

**Protein design requires expertise.** There have been many reports of successful _de novo_ protein design in recent years, and researchers in the field continue to improve protein design methods. However, even the most "automated" design methods typically still require some intervention from expert protein engineers. It is unclear how much of this success is codified in protein energy functions and design protocols, and how much relies on the expertise and implicit skill of the protein designer. **Non-expert Foldit players can rigorously test protein design rules, to make protein design more robust and accessible.**

**Protein design is open-ended.** Because protein structures have many degrees of freedom, the number of possible structures is astronomically large, and exhaustive sampling of all protein folds is infeasible. Several billion years of natural evolution have explored only a tiny fraction of possible protein folds. Thus, there is considerable room for creativity in designing new protein folds. **We can use crowdsourcing to draw on the creativity of the general public.**

The work of Foldit players has revealed implicit assumptions in expert design methods, and has discovered flaws in our protein design energy function. After we addressed these flaws and assumptions, Foldit players have successfully designed a wide diversity of protein structures -- including new folds that are unobserved in natural proteins. We are currently writing a manuscript reporting these findings.


## Model building in Foldit with electron density

![](/images/pubthumb-2016-09-16.png){: .align-right}

Structural biology depends heavily on accurate structures of proteins and other macromolecules, typically determined from x-ray crystallography and cryo-electron microscopy (cryo-EM) experiments. Model building is a critical part of structure determination, but is labor-intensive and prone to error when carried out by a single individual. 

We added support for electron density maps in the protein folding game [Foldit](https://fold.it), allowing us to crowdsource model building to Foldit players. Foldit players are adept at interpreting electron density data, and -- collectively -- can produce high-quality, accurate models on par with those of structural biologists. Although Foldit players lack formal training in protein structure, the Rosetta energy function underlying Foldit can guide the development of physically realistic models that conform to the experimental data.

This work was published in:

:   [Horowitz S, Koepnick B, Martin R, Tymieniecki A, Winburn AA, Cooper S, Flatten J, Rogawski DS, Koropatkin NM, Hailu TT, Jain N, Koldewey P, Ahlstrom LS, Chapman MR, Sikkema AP, Skiba MA, Maloney FP, Beinlich FR, Foldit Players, University of Michigan students, Popović Z, Baker D, Khatib F, Bardwell JC. Determining crystal structures through crowdsourcing and coursework. _Nature Communications_ **7** (2016)](https://www.ncbi.nlm.nih.gov/pubmed/27633552)

