# Cascading fails in IT Portfolios

This python code tries to run a cascading failure spread in IT projects within a broad IT portfolio (ITP). Similar to a virus spread, where individuals in society get infected with a virus and spread it through aquaintances, this IT virus spreads via dependencies. Such a systemic risks are already received great attention in the reseach fields of epidemiology, finance theory, and energy grids. Nevertheless, research about systemic risks in IS research is scarce. Due to increasing amount of IT projects in companies and existing dependencies between these projects, malfunctions (e.g. delays) in specific projects can trigger a domino effect eventually effecting the whole ITP. This code tries to simulate such a fail spread, based on several assumptions and potential cases (e.g. immunity of projects) which can occur throughout the simulation. 

The initial simulation builds on the basic SIS cascade model and was further developed within the scope of my master thesis. The cascading model therefore further developed from SIS -> SI(R)S -> SIRS cascade model, following Kermack and McKendrick (1927) as well as Hethcote (1976).

It is my first GitHub repository and will be updated with all content over the past few weeks to open up the opportunity to further develop my work and to drive future research regarding this topic!

## Content

- the inital code [final_code_model_artefact](https://github.com/ducity34/IT-Project-fail-spread/blob/master/20200721_v6.0_updated%20code%20structure.txt) is the final code model algorithm I developed throughout the process of my master thesis.

- the IT portfolio contains 20 projects and 38 dependencies connecting these projects. An [exemplary IT portfolio](https://github.com/ducity34/IT-Project-fail-spread/blob/master/03_Graph%20Example_Section%204.2.png) I used in the algorithm looks like this.


Best, 

Dominik 

## References

Hethcote, H. W. 1976. “Qualitative Analyses of Communicable Disease Models,” Mathemati-cal Biosciences (28:3–4), pp. 335–356. 
(https://doi.org/10.1016/0025-5564(76)90132-2).

Kermack, W. O., and McKendrick, A. G. 1927. “A Contribution to the Mathematical Theory of Epidemics,” Proceedings of the Royal Society of London. Series A, Containing Papers of a Mathematical and Physical Character (115:772), pp. 700–721. 
(https://doi.org/10.1098/rspa.1927.0118).
