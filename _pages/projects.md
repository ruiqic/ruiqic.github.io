---
permalink: /projects/
title: "Research Projects"
---

## Active Learning for Machine Learning Potentials - `al_mlp`

I am a lead developer of [`al_mlp`](https://github.com/ulissigroup/al_mlp/), an active learning package for conducting $\Delta$-machine learning to learn the correction between a simple physics-based potential and an expensive ab-initio level theory. The package is built on top of [Atomic Simulation Environment](https://github.com/rosswhitfield/ase) to interface with atomistic simulations.

Codebase: [github.com/ulissigroup/al_mlp/](https://github.com/ulissigroup/al_mlp/)


## Atomistic Machine Learning Package PyTorch, AMPtorch - `amptorch`

I am a developer of [`amptorch`](https://github.com/ulissigroup/amptorch), a machine learning potential package to model atomic interactions using a [Behler-Parinello](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.146401) neural network. The package is built on top of [PyTorch](https://pytorch.org/), [Pytorch Geometric](https://github.com/rusty1s/pytorch_geometric), and [Skorch](https://github.com/skorch-dev/skorch) to provide users an easy, flexible, and fast framework to train and iterate new models. 

This project is being developed in collaboration with Brown University's [Andrew Peterson](https://www.brown.edu/Departments/Engineering/Labs/Peterson/) as part of the Department of Energy's <i>Bridging the time scale in exascale computing of chemical systems</i> project.

Codebase: [github.com/ulissigroup/amptorch](https://github.com/ulissigroup/amptorch)


## Ulissi Walltime Prediction - `ulissi-waltime-prediction`

This is my first major project within the [Ulissi Group](https://ulissigroup.cheme.cmu.edu/), I developed a machine learning model that trains on a large dataset of past Density Functional Theory calculations to predict the duration of future calculations. The model allows the prioritization of fast and feasible calculations over long calculations that time out or produce unphysical results to increase calculation throughput.

Codebase: [github.com/ruiqic/ulissi-waltime-prediction](https://github.com/ruiqic/ulissi-waltime-prediction)
