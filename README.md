# Relaxation Runge-Kutta Methods for inner-product norms

[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)

Relaxation Runge-Kutta methods are modifications of Runge-Kutta methods that
enforce conservation, dissipation, or other solution properties with respect
to any convex functional by the addition of a *relaxation parameter* that
multiplies the Runge-Kutta update at each time step.
Moreover, other desirable stability (such as strong stability preservation)
and efficiency (such as low storage requirements) properties are preserved.
The technique can be applied to both explicit and implicit Runge-Kutta
methods and requires only a small modification to existing implementations.
The computational cost at each step is a computation of few inner products.

They are developed and studied in the articles
```
@misc{ketcheson2019relaxation,
  title={Relaxation {R}unge--{K}utta Methods: {C}onservation and Stability for
         Inner-Product Norms},
  author={Ketcheson, David I},
  year={2019},
  month={05}
  note={in preparation}
}

@online{ranocha2019relaxation,
  title={Relaxation {R}unge--{K}utta Methods: Fully-Discrete Explicit
         Entropy-Stable Schemes for the {E}uler and {N}avier--{S}tokes Equations},
  author={Ranocha, Hendrik and Sayyari, Mohammed and Dalcin, Lisandro and
          Parsani, Matteo and Ketcheson, David I.},
  year={2019},
  month={05},
  eprint={1905.09129},
  eprinttype={arxiv},
  eprintclass={math.NA}
}
```
Implementations of relaxation Ruge-Kutta methods and numerical experiments
reported in the first article can be found in this repository, along with some
other interesting computations that did not fit in the paper.
schemes useful, please cite the first article mentioned above. If you use the
implementations provided here, please cite this repository as
```
@misc{ketcheson2019_RRK_rr,
  title={{R}elaxation {R}unge--{K}utta Methods for inner-product norms},
  author={Ranocha, Hendrik and Ketcheson, David I.},
  year={2019},
  month={05},
  howpublished={\url{https://github.com/ketch/RRK_rr}},
}
```


## Disclaimer

Everything is provided as-is and without warranty. Use at your own risk!
