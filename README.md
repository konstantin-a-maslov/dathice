# DATHICE: Data-Assisted THickness correction for ICE

<!-- [Konstantin A. Maslov](https://people.utwente.nl/k.a.maslov) -->

[[`Installation`](#installation)] [[`Getting started`](#getting-started)] [[`BibTeX`](#citing)] 

<br/>

This short exercise ...

## Installation

\[*NOT RECOMMENDED*\] The repository provides the `env.yml` file, which can be used to reproduce the environment with, e.g., `conda` by running
```
conda env create -f env.yml
```

However, this is likely to fail as the installation process of JAX might be complicated in some configurations.
I highly recommend to install JAX as explained [here](https://jax.readthedocs.io/en/latest/installation.html) and install manually other dependencies: `optax`, `rioxarray`, `geopandas`, `pandas`, `matplotlib`, `jupyterlab` and (optionally) `tqdm`. 
It might take some time to figure out which versions of the packages work best for you. 

As this exercise is really simple and do not require a lot of computational resources, it is also a good idea to install a CPU version of JAX, which is usually much easier to deal with.

## Getting started

[link to the raster data](https://bit.ly/4gce19k)

## Acknowledgements

I acknowledge the contributions of my peers and instructors, particularly [Prof. Andrew Hodson](https://www.unis.no/staff/andy-hodson/) and [Erik Schytt Mannerfelt](https://www.mn.uio.no/geo/english/people/aca/geohyd/erikmann/), from the [AG-325/825 course at the University Centre in Svalbard (UNIS)](https://www.unis.no/courses/ag-825-glaciology/) in the collection and interpretation of the low-frequency GPR data for ice thickness mapping in February 2024. 
Their assistance was essential for this project. 

## License

This software is licensed under the [GNU General Public License v2](LICENSE).

## Citing

```
@misc{dathice_2024,
    title  = {{DATHICE: Data-Assisted THickness correction for ICE}},
    author = {Maslov, Konstantin A.},
    url    = {https://github.com/konstantin-a-maslov/dathice},
    year   = {2024},
}
``` 
