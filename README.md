# microANARCI

Minified version of [ANARCI](https://github.com/oxpig/ANARCI). Pip-installable.

- mimics currently latest version of bioconda::anarci (noarch/anarci-2021.02.04-pyhdfd78af_0.tar.bz2)
- installation just pulls hmmer weights that were copied from bioconda instead of rebuilding those
- dropped deprecated packaging methods


## Installation:

1. install hmmer (`apt install hmmer` or `brew install hmmer`)
2. `pip install git+https://github.com/arogozhnikov/microANARCI`
