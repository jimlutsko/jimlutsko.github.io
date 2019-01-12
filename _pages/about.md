---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


 My background is in nonequilibrium statistical mechanics and nowadays most of my time is spent on the study of crystallization and crystal growth. Previously, I have worked on non-classical diffusion, granular materials, symbolic learning, kinetic theory and the mechanical properties of solid interfaces. My work involves a combination of analytic theory, numerical analysis and computer simulation and is currently funded by the European Space Agency, via the Belgian Science Policy Office, and the EU Horizon 2020 program, via the [AMECRYS project](http://www.amecrys-project.eu). 





# Current Projects  <img src='/images/smaller.gif'> 

## In brief: Crystallization and crystal growth
Crystallization is a particularly complex example of the more general phenomenon of nucleation: the fluctuation-driven transition from one metastable state to another, usually more stable, state via the formation of clusters. Small clusters form all the time due to thermal fluctuations and, once formed, they fluctuate in size but are generally unstable and tend to dissipate. If, by chance, one does happen to grow larger than a critical size,  then everything changes and the cluster will continue to grow forever and fluctuations no long play the dominant role. Thus, the formation of crystals involves two complementary steps: fluctuation-driven crystal nucleation followed by determinisitic crystal growth. I study both processes.

## Mesoscopic Nucleation Theory (MeNT)
This is an approach to the understanding of nucleation that I have developed over the last several years. Cluster energetics are described using classical Density Functional Theory and fluctuation dynamics are modeled using fluctuating hydrodynamics. Of particular interest in my work is the _nucleation pathway_ which describes the different stages a cluster passes through before it reaches its final form: for example, crystal nucleation from a dilute solution might begin with the nucleation of a liquid droplet within which the actual crystal forms or it may form directly, in one go. One of the key ideas of my work is that the pathway can be identified as the _Most Likely Path_ determined from the fluctuation dynamics in a mathematically precise way. Finally, I have spent a lot of time showing that simplified models can be derived from this framework with the simplest ones corresponding to the standard description of nucleation called Classical Nucleation Theory. A summary of the relevant papers are:
* Density Functional Theory background: [general](/publication/00076) and improvements [needed for crystallization](/publication/107).
* MeNT framework : [short summary](/publication/00083) and a [longer version](/publication/00084).
* Application to liquid droplet nucleation: [importance of the pathway](/publication/00087), [nucleation in a finite volume](/publication/00086)
* Simplified models: [connection to CNT](/publication/00091), [nucleation in a finite volume](/publication/00098), a [two parameter generalization of CNT](/publication/00099) and [a general framework for extending CNT](/publication/106].

## Crystal Growth
This work mostly involves kinetic Monte Carlo simulations of crystal growth with the main physical problem being the effect of impurities on crystal growth. One of our main insights is that crystal growth in the presence of impurities involves three regimes. When the impurities are very sparse, growth continues unimpeded but is slowed. As the density of impurities increases, the rate of crystal growth decreases until a limit - called the Cabrera-Vermilyea (CV) threshold  - is reached. Beyond this, with increasing impurity density, growth depends on fluctuations and we call this the "stochastic regime". Eventually, when there are too many impurities, growth stops altogether - the so-called "dead zone". This critical density of impurities can be determined based on simple thermodynamic arguments. Our understanding is that these different regimes are completely analogous to the liquid-vapor phase diagram of a simple liquid. The dead-zone is like the stable region of a phase diagram and the thermodynamic threshold beyond which growth occurs is like the binodal; the stochastic growth regime is like the metastable region of the phase diagram and the CV threshold is analogous to the spinodal; the regime of unimpeded growth is like spinodal decomposition. Some relevant work is:
* [The intiial work on the CV threshold](/publication/00094)
* [Long thin impurities](/publication/00097)
* Macrosteps can grow even in the dead zone: see [this](/publication/102) and [this](/publication/110).


## My Open source Project
My work makes extensive use of classical Density Functional Theory. The codes I have developed for doing cDFT calculations, including crystallization, are available for download from [this link](https://jimlutsko.github.io/classicalDFT). 



Contact
------------
I can be reached via email at jlutsko AT ub.ac.be as well as jim AT lutsko.com
