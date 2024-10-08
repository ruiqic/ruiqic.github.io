---
permalink: /projects/
title: "Projects"
---

Research Projects
======

## Uncertainty Quantification of Interatomic Potentials

I explored different uncertainty quantification methods for machine learning interatomic potentials such as [Gaussian Approximation Potential (GAP)](https://arxiv.org/pdf/1502.01366) and [Moment Tensor Potential (MTP)](https://arxiv.org/pdf/1512.06054) for application in active learning. The methods included Bayesian and ensemble (bootstrapping and subsampling). Furthermore, I evaluated several uncertainty recalibration methods including [isotonic regression](https://arxiv.org/abs/1807.00263) and [linear regression](https://arxiv.org/abs/2105.13303) to improve uncertainty estimation.

Partial Codebase: [github.com/ruiqic/FHI_uncertainty_scripts](https://github.com/ruiqic/FHI_uncertainty_scripts)


## Active Learning for Machine Learning Potentials - `al_mlp`

I was a lead developer of [`al_mlp`](https://github.com/ulissigroup/al_mlp/) (now rebranded as finetuna), an active learning package for conducting $\Delta$-machine learning to learn the correction between a simple physics-based potential and an expensive ab-initio level theory. The package is built on top of [Atomic Simulation Environment](https://github.com/rosswhitfield/ase) to interface with atomistic simulations.

Codebase: [github.com/ulissigroup/al_mlp/](https://github.com/ulissigroup/al_mlp/)


## Atomistic Machine Learning Package PyTorch, AMPtorch - `amptorch`

I was a developer of [`amptorch`](https://github.com/ulissigroup/amptorch), a machine learning potential package to model atomic interactions using a [Behler-Parinello](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.146401) neural network. The package is built on top of [PyTorch](https://pytorch.org/), [Pytorch Geometric](https://github.com/rusty1s/pytorch_geometric), and [Skorch](https://github.com/skorch-dev/skorch) to provide users an easy, flexible, and fast framework to train and iterate new models. 

This project is being developed in collaboration with Brown University's [Andrew Peterson](https://www.brown.edu/Departments/Engineering/Labs/Peterson/) as part of the Department of Energy's <i>Bridging the time scale in exascale computing of chemical systems</i> project.

Codebase: [github.com/ulissigroup/amptorch](https://github.com/ulissigroup/amptorch)


## Ulissi Walltime Prediction - `ulissi-waltime-prediction`

This was my first major project within the [Ulissi Group](https://ulissigroup.cheme.cmu.edu/), I developed a machine learning model that trains on a large dataset of past Density Functional Theory calculations to predict the duration of future calculations. The model allows the prioritization of fast and feasible calculations over long calculations that time out or produce unphysical results to increase calculation throughput.

Codebase: [github.com/ruiqic/ulissi-waltime-prediction](https://github.com/ruiqic/ulissi-waltime-prediction)




Personal Projects
======

## Futarchy Python SDK

I developed a Python SDK for Futarchy, facilitating trading [MetaDAO](https://docs.metadao.fi/)'s futarchy markets. 

Public SDK codebase: [github.com/ruiqic/futarchy](https://github.com/ruiqic/futarchy)

## Moonshot Python SDK

I developed a Python SDK for Moonshot, facilitating interaction with the protocol on the [Solana](https://solana.com/) blockchain, allowing developers to trade meme tokens or vanity coins. The [official TypeScript SDK](https://github.com/wen-moon-ser/moonshot-sdk) was used as reference. A simple, data-driven sniping bot was also developed to make use of the SDK to execute profitable trades.

Public SDK codebase: [github.com/ruiqic/moonshot-py](https://github.com/ruiqic/moonshot-py)

## On-chain Trading Bot

I programmed a bot that operated on the [Solana](https://solana.com/) blockchain, using Python and JavaScript to interact with Rust smart contracts (programs). The strategy profited from price volatility in digital assets. The bot had been profitable without investing in high-end infrastructure, relying instead on free-tier services. The bot was hosted on [Google Cloud Platform](https://cloud.google.com/) to maintain uptime. I also made a [simple chart](../crypto-bot-performance) with d3.js to track the bot's performance.




Class Projects
======

## Laboratory: Storage Methods on Vitamin C Degradation

In a team of four, we explored the effect of different storage methods on the vitamin C concentration of orange and lemon juice. The analysis included organic extraction, iodimetric titration, dichlorophenolindophenol (DCPIP) titration, and high-performance liquid chromatography (HPLC). We concluded that vitamin C degrades significantly through refrigeration, while freezing and storing the whole fruit preserves the vitamin well. 


## Programming: Sokoban

I programmed the classic puzzile game [Sokoban](https://en.wikipedia.org/wiki/Sokoban) in Python. Instead of hardcoded levels, I used backtracking to randomly generate the puzzles at varying difficulty levels. The game also used sockets and threading to allow for a multiplayer gamemode, where players compete to solve puzzles in the shortest duration.

Codebase: [github.com/ruiqic/term-project/](https://github.com/ruiqic/term-project/)
