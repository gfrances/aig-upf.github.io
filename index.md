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

#### Relevant Publications
> * Javier Segovia-Aguas, Sergio Jiménez and Anders Jonsson (2017). *Unsupervised Classification of Planning Instances*. Proceedings of the 27th International Conference on Automated Planning and Scheduling.
> * Damir Lotinac, Javier Segovia-Aguas, Sergio Jiménez and Anders Jonsson (2016). *[Automatic Generation of High-Level State Features for Generalized Planning](http://www.dtic.upf.edu/~jonsson/ijcai16a.pdf)*. Proceedings of the 25th International Joint Conference on Artificial Intelligence.
> * Javier Segovia-Aguas, Sergio Jiménez and Anders Jonsson (2016). *[Hierarchical Finite State Controllers for Generalized Planning](http://www.dtic.upf.edu/~jonsson/ijcai16b.pdf)*. Proceedings of the 25th International Joint Conference on Artificial Intelligence.
> * Javier Segovia-Aguas, Sergio Jiménez and Anders Jonsson (2016). *[Generalized Planning With Procedural Domain Control Knowledge](http://www.dtic.upf.edu/~jonsson/icaps16a.pdf)*. Proceedings of the 26th International Conference on Automated Planning and Scheduling.


## [FS Planner](https://github.com/aig-upf/fs)

FS is a classical planner based on the *Functional STRIPS* planning language,
with additional support for existential quantification, state constraints and a fairly large
library of global constraints which are useful both from the expressive and computational points of view.

#### Relevant Publications
> * Francès, G., and Geffner, H. (2015),[_Modeling and Computation in Planning: Better Heuristics from More Expressive Languages_](http://gfrances.github.io/pubs/2015-icaps-better-heuristics-more-expressive-languages/), ICAPS 2015.
> * Francès, G., and Geffner, H. (2016a), [_E-STRIPS: Existential Quantification in Planning and Constraint Satisfaction_](http://gfrances.github.io/pubs/2016-ijcai-existential-quantification-planning-csp/), IJCAI 2016.
> * Francès, G., and Geffner, H. (2016b), [_Effective Planning with More Expressive Languages_](http://gfrances.github.io/pubs/2016-ijcai-effective-planning-more-expressive-languages/), IJCAI 2016.
> * Geffner, H. (2000), [_Functional STRIPS: A more flexible language for planning and problem solving_](http://www.tecn.upf.es/~hgeffner/). In Minker, J., ed., Logic-Based Artificial Intelligence. Kluwer. 187–205.

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

#### Relevant Publications
> * N. Lipovetzky and H. Geffner (2011). *[Searching for plans with carefully designed probes](http://people.eng.unimelb.edu.au/nlipovetzky/papers/nir-icaps11.pdf)*. ICAPS 2011.



## [Universal PDDL parser](https://github.com/aig-upf/universal-pddl-parser)

A `PDDL` parser written in `C++` and, used in several of the other software projects within the group.
Provides support for programmatically parsing and generating `PDDL` instances.


## [Multiagent Parser](https://github.com/aig-upf/universal-pddl-parser-multiagent)

Extends the Universal PDDL Parser to provide support for parsing multiagent planning instances expressed in `PDDL`.
Currently also includes a solver for concurrent multiagent planning in which agents can take actions in parallel;
the solver is based on a compilation from multiagent planning to classical planning.


#### Relevant Publications
> * Matthew Crosby, Anders Jonsson and Michael Rovatsos (2014). *[A Single-Agent Approach to Multiagent Planning](http://www.dtic.upf.edu/~jonsson/ecai14.pdf)*. Proceedings of the 21st European Conference on Artificial Intelligence.




