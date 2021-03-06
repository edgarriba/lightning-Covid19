# Lightning-Covid19

[![Build Status](https://travis-ci.org/PyTorchLightning/lightning-Covid19.svg?branch=master)](https://travis-ci.org/PyTorchLightning/lightning-Covid19)

A detector for [covid-19 chest X-ray images](https://github.com/ieee8023/covid-chestxray-dataset) 
 using [PyTorch Lightning](https://github.com/PyTorchLightning/pytorch-lightning) (for educational purposes)

## Overview

This project came with actual global situation and reciently release X-ray dataset.

## Data

The baseline models uses only [covid-chestxray-dataset](https://github.com/ieee8023/covid-chestxray-dataset/)
 which is rather small (79 images at the time of writing).

They are also accessible with following python packages:
- https://github.com/ieee8023/covid-chestxray-dataset
- https://github.com/mlmed/torchxrayvision

## Installation

    python3.6 -m venv venv  # from repo root, use python3.6+
    source venv/bin/activate
    pip install -r requirements

## Experiments
See the [Experiments on Wiki.](https://github.com/PyTorchLightning/lightning-Covid19/wiki/Experiments)

## Contribution

Anyone is welcome to contribute and use this project...
For easier combination and coordination we are using separate [channel](https://pytorch-lightning.slack.com/archives/CV7MNM0NP) in Lightning Slack, feel free to join!

Just a few technical notes:
* when mering PR, do "Squash & merge" so in master is only one commit and does not overlap with other commits from different PRs in parallel
* for writing particular result or how to launch anything, lets ise Wiki for now as it much more flexible

## References

TBD
