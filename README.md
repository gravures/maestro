# Maestro

A zellij IDE layout and more...

## installation

cloning the repo and boostraping micromamba:

```bash
git clone https://github.com/gravures/mestro.git && cd maestro
source bootstrap && bootstrap
micromamba create -f environment.yml
```

activating the conda environment:

```bash
source bootstrap && bootstrap
micromamba activate maestro
```

updating the conda environment:

```bash
source bootstrap && bootstrap
micromamba deactivate
micromamba update --file environment.yml --prune
micromamba activate maestro
```

> note: It should be preferable to re-create entirely the environment
> instead trying an update when mixing conda packages with pip packages.
