# pandapower case study

This repository includes an exemplary case study that demonstrates the capabilities of pandapower.
The case study showcases some pandapower functionality and is also used in a reference paper for pandapower, which has been accepted for publication in IEEE Transaction on Power Systems. A preprint of this paper is available on [arXiv](https://arxiv.org/abs/1709.06743). Please acknowledge the usage of pandapower by citing the Paper as follows:

- **L. Thurner, A. Scheidler, F. Schäfer et al.**, “pandapower - an Open Source Python Tool for Convenient Modeling, Analysis and Optimization of Electric Power Systems,” IEEE Transaction on Power Systems (to be published), 2018.

You can use the following BibTex entry:

```
@article{pandapower,
	author = {{Thurner}, L. and {Scheidler}, A. and {Sch{\"a}fer}, F. and {Menke}, J.-H. and {Dollichon}, J. and {Meier}, F. and {Meinecke}, S. and {Braun}, M.},
	title = "{pandapower - an Open Source Python Tool for Convenient Modeling, Analysis and Optimization of Electric Power Systems}",
	year = 2018,
	journal = {IEEE Transaction on Power Systems (to be published)},
	url = {https://arxiv.org/abs/1709.06743}
	}
```

The case study consists of three parts, which are available in interactive jupyter notebooks:
1. Definition of a 10kV ring main grid in radial operation ([grid.ipynb](grid.ipynb))
2. Analysis of all possible switching states in the grid to analyse feasible switch positions considering radiality and short-circuit constraints ([switch_evaluation.ipynb](switch_evaluation.ipynb))
3. Time series simulation for one day optimising switching states and transformer taps considering active power losses, line loading, transformer loading and voltage constraints ([time_series_simulation.ipynb](time_series_simulation.ipynb))

The case study works with pandapower 1.4.3.
