---
layout: default
title: "ISCA '22 Tutorial: Scalable Quantum Benchmarking"
---

{:refdef: style="text-align: center;"}
![Logo](/static/SupermarQ_Logo.png){:width="50%"; refdef}

The goal of this tutorial is to:
1. Provide an overview of the current quantum benchmarking landscape.
2. Introduce [SupermarQ](https://arxiv.org/abs/2202.11045), a new quantum benchmarking suite recently published in [HPCA 2022](https://hpca-conf.org/2022/program/#session4c).
3. Walk attendees through a hands-on demo of generating benchmarks, evaluating them on hardware, and processing the results.
4. Show users how they can develop and design their own quantum benchmarks.

# SupermarQ
SupermarQ is a scalable, application-oriented, quantum benchmark suite. It is based on collaborative research between Princeton University, The University of Chicago, Super.tech, and Northwestern University. This work was recently published in [HPCA 2022](https://hpca-conf.org/2022/program/#session4c) and an open source version is available on [arXiv](https://arxiv.org/abs/2202.11045). More information on SupermarQ can be found on the [Super.tech website](https://www.super.tech/supermarq/), and our [GitHub repository](https://github.com/SupertechLabs/SupermarQ).

# Benchmarking Demo

Before getting started (and ideally before attending the ISCA tutorial) please set up a fresh python environment
we can use to run the SupermarQ benchmarks.

Please note that Python version `3.7` or higher **is required**. Once you have the correct version of Python installed,
a new virtual environment can be created via the command:

```python
python3 -m venv name_of_your_environment
```

Activate that new environment by

```python
source name_of_your_environment/bin/activate
```

Once this is completed you can type the command `which python` to see that you are now referencing the python installed at the location
of your new environment. With your newly created and activated python environment it is time to install all of the necessary packages.

```python
pip install cirq-superstaq supermarq
```

This will install `cirq-superstaq` and its dependencies -- which we will use to access different quantum computers available over the cloud, and the `supermarq` package which contains all of the code for generating and evaluating the quantum benchmarks.

[More content coming soon!]

# Designing your own benchmarks

[More content coming soon!]
