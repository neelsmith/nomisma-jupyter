[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/neelsmith/nomisma-jupyter/master)

# `nomisma-jupyter`

This repository hosts Jupyter notebooks illustrating usage of the [`nomisma` library](https://github.com/neelsmith/nomisma).  It accompanies a series of blog posts on [digital numismatics](http://neelsmith.info/tag-coins/).


## Running these notebooks

These notebooks use the [Almond kernel](https://almond.sh/).  You can run a notebook server with the Almond kernel using a docker container like this:


    docker run -it --rm -p 8888:8888 almondsh/almond:0.9.0

or use it locally in a notebook server or in apps like nteract or Atom with the Hydrogen plugin if you install the almond kernel locally.

You can also work interactively with these notebooks on [mybinder.org](https://mybinder.org/v2/gh/neelsmith/nomisma-jupyter/master).
