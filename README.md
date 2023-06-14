# AutoRA Inequality Sampler

`autora-experimentalist-sampler-inequality` is a Python module for sampling data built on AutoRA.

Website: [https://autoresearch.github.io/autora/](https://autoresearch.github.io/autora/)

## User Guide

You will need:

- `python` 3.8 or greater: [https://www.python.org/downloads/](https://www.python.org/downloads/)
- `graphviz` (optional, required for computation graph visualizations): 
  [https://graphviz.org/download/](https://graphviz.org/download/)

Install the inequality sampler as part of the `autora` package:

```shell
pip install -U "autora[experimentalist-sampler-inequality]"
```

> It is recommended to use a `python` environment manager like `virtualenv`.

Check your installation by running:

```shell
python -c "from autora.experimentalist.sampler.inequality import summed_inequality_sample"
```
