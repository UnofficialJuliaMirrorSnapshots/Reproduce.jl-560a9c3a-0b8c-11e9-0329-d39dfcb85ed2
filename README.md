# Reproduce.jl
[![Build Status](https://travis-ci.com/mkschleg/Reproduce.jl.svg?branch=develop)](https://travis-ci.com/mkschleg/Reproduce.jl)
[![codecov](https://codecov.io/gh/mkschleg/Reproduce.jl/branch/develop/graph/badge.svg)](https://codecov.io/gh/mkschleg/Reproduce.jl)

How did I get these results?

A framework for managing hyper-parameter settings, and running experiments. Lightly based on litetracer from Borealis.

## What is this?

This repository is for giving you the tools you need to make experiments reproducible. This repository is mostly built around machine learning and reinforcement learning projects, but there is no reason it is restricted to these types of projects. I've developed this around my own tastes (specifically using )

## How To use

The best way to see how to use this repository is in the examples folder. [parallel.jl](examples/parallel.jl) shows all the parallel and experiment utilities in action, while running an experiment in [experiment.jl](examples/experiment.jl) which shows off the data management, and arg parsing.


## What's next.

The goal is to make a convenient framework for data analysis for experiments in ML/RL. The goal is to create something like [mlflow](mlflow.org) for Julia. It might be worthwhile to actually take advantage of the mlflow framework, or even a similar framework for the future.

## TODOs

- [ ] Allow for YAML specification
- [x] Data searching (Mostly done. Could probably use more testing...)
- [ ] Plotting utilities (Up Next!)
- [ ] Frontend for visualizing data.
- [x] Testing with slurm backend. (Make sure your experiments run *BEFORE* a job is scheduled.)
- [ ] More examples. (maybeeee.....)
- [ ] Docs

HELP WANTED! Contact me via issues panel, or setup a PR.
