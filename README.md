# Cybele
Open sourced security specification mining framework. For Anne Benna Sims's first principal role.

# Direction

This project builds on Astarte, a tool for specifying subsets of design states at and across partitions of the design space.

Paper: https://cd-public.github.io/papers/2020/HOST2020.pdf
Repo: https://github.com/cd-public/Astarte

This project builds on HyperMiner, a tool for identifying interference cases within traces of designs.

Paper: https://www.cse.iitk.ac.in/users/smuduli/assets/pdf/hyperminer.pdf
Repo: https://github.com/c0demag/HyperMiner_SourceCode

This project studies the following design:

https://github.com/pulp-platform/pulpissimo

Using Hyperminer to find interference cases and Astarte to define design state when interference occurs, Cybele will compose conditional interference hyperproperties from design traces while fully open source.

# Workflow

* Generate Pulpissimo traces [Kellen]
* Detect Pulpissimo interference times [Paul]
* Mine states when interference occurs [Next]
* Post-process output into conditional interference hyperproperties [a la Isadora]
