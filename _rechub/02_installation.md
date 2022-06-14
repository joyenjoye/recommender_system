---
layout: default
title: Installation
nav_order: 2
---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Mac OS 

*Step1: Create Virtual Environment*

```bash
conda create --name my_env python=3.8
```

*Step2: Activate Virual Environment*

```bash
conda activate my_env
```

*Step3: Install `torch-rehub`*

```bash
pip install torch-rechub
```

Dependency of `torch-rehub` including `annoy` will be installed accordingly.


<br>

## Windows

*Step1: Create Virtual Environment*

```bash
conda create --name my_env python=3.8
```

*Step2: Activate Virual Environment*

```bash
conda activate my_env
```

In windows, annoy can be direcly installed with pip because of the compilation issue. One option is to find the compiled wheel corresponding to the python version and windows system from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/).  Alternatively, it can be installed through conda.

*Step3: Install `annoy`*

```bash
conda install -c conda-forge python-annoy
```

*Step4: Install `torch-rehub`

```bash
pip install torch-rechub
```

