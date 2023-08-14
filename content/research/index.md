---
title: "Research"
draft: false
---


Everyone has a gut microbiome, full of trillions of microbes, that influences
their health. One person's microbiome might give them a stomach ache, while
another person's might help them metabolize food more efficiently. I want to
figure out how "medicine for the microbiome" works-- how can a sick person's
microbiome be made "healthy"? Specifically, I am interested in how external
interventions (e.g. fecal microbiota transplantation, probiotics, or a modified
diet) influence microbiome composition.

To address this goal, in my research I develop ecological models of the
microbiome that are characterized and guided by well-controlled fruit fly and
mouse microbiome experiments. I approach the complexity of the microbiome in
two ways: experimentally, I use a simple model organism with a core microbiome
of only five species; and theoretically I develop mathematical methods for
dimensionality reduction.

Community assembly in the fruit fly microbiome
--------------------

In my experimental collaboration with Will Ludington (Department of Embryology,
Carnegie Institution for Science), we have worked to construct simple models
from first principles that describe the behavior of the fruit fly microbiome.
The microbiome of the fruit fly _Drosophila melanogaster_ naturally
hosts only a few species of commensal bacteria. In our research we cultivate a
core group of five commensal bacteria, and associate each possible combination
of the five bacteria with a set of germ-free flies. Since the flies were
otherwise identically reared, the flies associated with each of these 32
bacterial combinations carry a distinct microbiome-affiliated phenotype (e.g.
lifespan or fecundity) that is a function of the complex interactions in the
microbiome.  However, we found that the complexity of these fly phenotypes was
often reducible: we could approximate the phenotype of flies associated with
more than one bacterial species by averaging the phenotypes of the flies with
the corresponding single-species associations.  Thus, we found that simple
models can at least partially describe complex behaviors in the fly microbiome.
**In 2018 lead author Alison Gould published these findings in PNAS
[[link]](https://www.pnas.org/content/115/51/E11951.short), this article was
covered in the press by Sonia Fernandez in the _UCSB Current_
[[link]](https://www.sciencedaily.com/releases/2018/12/181205152208.htm), and
this article was also adapted for the non-profit journal _Science Journal for
Kids_
[[link]](https://sciencejournalforkids.org/articles/how-do-microbes-shape-fruit-fly-fitness/),
.**

Dimensionality reduction of the generalized Lotka-Volterra equations
--------------------------------------------------------------------

In my theoretical and computational research
I use ecological
models of the microbiome to probe how microbial communities will respond to
bacteriotherapies like fecal microbiota transplantation (FMT), an as-yet
unconventional therapy that might pioneer a new paradigm for treating
microbiome diseases **(Jones and Carlson, PLOS Comp Bio 2018
[[link]](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006001))**.

To inform these control protocols, I designed analytic techniques for the
simplification of high-dimensional generalized Lotka-Volterra (gLV) models
exhibiting multistability **(Jones and Carlson, Phys Rev E 2019
[[link]](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.99.032403))**.
The key idea behind this method, called Steady-State Reduction (SSR), is to
first identify a pair of stable steady states that exhibit bistability in the
high-dimensional system, and then to approximate these high-dimensional
dynamics on the two-dimensional subspace spanned by the two steady states and
the origin. This method provides the best possible two-dimensional gLV
approximation in this subspace, and the reduced dynamics are analytically
tractable.  This method, which compresses complex dynamics into a
two-dimensional subsystem, makes ecological landscapes intuitive and
mathematically accessible.

I have written two publications
with excellent undergraduates to further extend SSR.
First, with Parker Shankin-Clarke I demonstrated how a system with
multistability can be decomposed into many bistable subsystems to create an
"attractor network" that compresses a high-dimensional dynamical landscape
into a graph structure **(Jones et al., AIMS Special
Issue 2020
[[arXiv
link]](https://arxiv.org/abs/2003.12954) [[book link]](https://www.aimsciences.org/book/AM/volume/Volume%2011))**. Second, with Zipeng Wang I
developed a method to control gLV models by modifying the interactions between
microbes, rather than altering the state of the system itself . This "indirect"
control protocol reflects bacteriotherapies that are based on altering the
environment of the microbiome, for example by modulating a person's diet **(Wang et al., Phys Rev E 2020
[[link]](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.101.052402))**.
This last project was covered in the press by Sonia Fernandez at the _UCSB
Current_ [[link]](https://www.news.ucsb.edu/2020/019897/gut-ecology).


_Research theme: decomposition of multistable systems into networks of bistable subsystems_



Aging-induced fragility in a mathematical model of the immune system
--------------------------------------------------------------------

Finally, in a collaboration with Shenshen Wang (Department of Physics, UCLA) I
have developed a mathematical model of the coupled innate-adaptive immune
response to investigate the mechanisms that lead to immunosenescence in a host
**(Jones et al., _Journal of Theoretical Biology_ 2021
[[link]](https://www.sciencedirect.com/science/article/abs/pii/S0022519320303283))**.
We observe that the adaptive response plays an important role in "turning off"
inflammation following pathogen clearance, which highlights the importance of
collaboration between the two immune compartments.



