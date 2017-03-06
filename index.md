---
layout: frontpage
---

This is the main software repository of the
Artificial Intelligence and Machine Learning Research Group
at [Universitat Pompeu Fabra](https://www.upf.edu), Barcelona, Spain.
You can browse the full list of publicly available projects on the [group's Github page](https://github.com/aig-upf/),
or click directly to a particular project on the list below:

## [Automated Programming Framework](https://github.com/aig-upf/automated-programming-framework)

The Automated Programming Framework includes the code necessary to configure and execute different compilations related
to the formalisms of *Planning Programs* and *Hierarchical Finite State Controllers*.
These compilations are produced from the original planning problems using the Universal PDDL Parser,
and solved using classical planners which are included in the repository.


## [The FS Planner](https://github.com/aig-upf/fs)

FS is a classical planner based on the *Functional STRIPS* planning language,
with additional support for existential quantification, state constraints and a fairly large
library of global constraints which are useful both from the expressive and computational points of view.


## [The Lightweight Automated Planning Toolkit (LAPKT)](https://github.com/aig-upf/LAPKT-public)
LAPKT is an open-source framework written in `C++` / `Python` to ease the creation of high-performance automated planners.
The toolkit has been succesfully used as the basis for a number of planners from
the last [International Planning Competition (2014)](https://helios.hud.ac.uk/scommv/IPC-14/), as well as
in several research projects on compilation-based and replanning approaches.
The full documentation of the toolkit can be found on the [project's main website](http://lapkt.org).


## [PROBE](https://github.com/aig-upf/probe)

PROBE is a classical planner developed by Nir Lipovetzky and Hector Geffner
that participated in the [seventh International Planning Competition (2011)](http://www.plg.inf.uc3m.es/ipc2011-deterministic/)
with remarkable performance. See *"Searching for plans with carefully designed probes"*, N. Lipovetzky and H. Geffner. In Proceedings ICAPS 2011.


## [Universal PDDL parser](https://github.com/aig-upf/universal-pddl-parser)

A `PDDL` parser written in `C++` and, used in several of the other software projects within the group.
Provides support for programmatically parsing and generating `PDDL` instances.


## [Multiagent Parser](https://github.com/aig-upf/universal-pddl-parser-multiagent)

Extends the Universal PDDL Parser to provide support for parsing multiagent planning instances expressed in `PDDL`.
Currently also includes a solver for concurrent multiagent planning in which agents can take actions in parallel;
the solver is based on a compilation from multiagent planning to classical planning `(Crosby et al., ECAI 2014)`.


