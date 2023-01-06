# Nicholas P. Herrington
I am currently a PhD student at the University of Exeter in the U.K.

## Research interests
My current work focuses on modeling regions of a spiral arm galaxy using smooth particle hydrodynamics simulations, which includes feedback and magentohydrodynamics. As well as this I am interested in the origin of the first quasars, particularly simulating the evolution of supermassive primordial stars as the progenitors of the first supermassive black holes (SMBH) in the universe. We make use of the MESA stellar evolution code to model the evolution of these stars to determine their properties.  
### Simulations of extracted regions of a galaxy
We setup a suite of simulations, extracting the initial conditions from a galaxy evolution model. Our box regions contain a section of spiral arm and cluster sink particles which represent sites of star formation within the region.
![Image](f1.pdf)
We evolve these with a smooth particle hydrodynamics code (sphNG), making use of feedback perscriptions, such as supernovae and photo-ionising feedback. As well as this we pre-populate our simulation with massive stars of different masses and ages according to the star formation history of the progenitor galaxy evolution model.
#### Hydrodynamic simulations with an initial population of stars 
Simulations of star formation on molecular cloud scales typically start with a turbu-
lent region of gas, or for example the collision of two clouds. In reality, a typical region
within a galaxy may already include, or reside near some population of stars contain-
ing massive stars undergoing feedback. As such, generations of stars may influence the
formation of subsequent generations, particularly through feedback. We present sim-
ulations of sub galactic regions, in which we pre-populate our models with an evolved
system of stars, based on a prior galaxy scale simulation. We investigate including initial
ionising stars, initial HII regions and stars which will imminently undergo supernovae.
Surprisingly, So far we find that having an initial stellar population does not strongly
effect the evolution when comparing to simulations without pre-existing stars. We also
investigate the reliability of extracting regions in simulations, and show that with a good
choice of region, results are comparable with using a larger region for the duration of
our simulations.
![Image](f4.pdf)
#### Magnetohydrodynamic simulations with an initial population of stars 
![Video](cd_all_models_nofb.mp4)
![Video](modB_all_models_nofb.mp4)
Simulations of star formation on molecular cloud scales typically start with a turbulent region of gas, or for example the collision of two clouds. Realistically, a typical region within a galaxy may already include, or reside near some population of stars containing massive stars undergoing feedback. In this work we investigate the interactions of Giant Molecular Clouds (GMCs) on kpc scales, focussing on how feedback from massive stars impact star formation throughout the region. Our sub galactic region includes ideal magnetohydrodynamics (MHD), photo-ionising and supernova feedback. So far we find that ionising and supernova feedback trigger star formation, through the expansion of hot ionised bubbles, whilst MHD suppresses star formation, smoothing out small over densities within inter-arm regions and prolonging GMC collapse across the spiral arm. Cosmic rays are expected to play an important role in the star formation process and will be sourced when supernovae occur. We aim to include a feedback prescription for modelling the impact and propagation of cosmic rays throughout the sub galactic region.
### The origins of the first quasars
Observations of the first quasars place these objects at redshifts z > 6, posing a problem for astrophysicists. Since quasars contain supermassive black holes (SMBH) the problem emerges when trying to explain the origin of > 10^8 solar mass black holes after only several hundred million years after the big bang. Black holes come from the death of stars, meaning the first population of stars (Pop. III stars) must have produced black holes that go on to become SMBHs, but even the most massive of Pop. III stars cannot produce a massive enough black hole that can evolve up to billions of solar masses by redshift 6.
To understand the origin of the first quasars we need to know how the first supermassive black holes formed. 
#### How the first quasars formed from turbulent origins 

#### The evolution of rapidly accreting supermassive primordial stars with MESA

#### Supermassive stars formed from the collapse of intermediate LW background primordial haloes

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/npherrington/npherrington.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
