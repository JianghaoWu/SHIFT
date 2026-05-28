# SHIFT

This is the official repository for the ICML 2026 paper:

**Single-Rollout Hidden-State Dynamics for Training-Free RLVR Data Selection**

**Authors:** Jianghao Wu, Jianfei Cai, Weiqiang Wang, Jin Ye, Daniel F. Schmidt, Yasmeen George

**Affiliation:** Faculty of Information Technology, Monash University, Melbourne, Australia

## Overview

SHIFT is a training-free and label-free data selection method for reinforcement learning with verifiable rewards (RLVR). It selects useful training instances before RL training by analyzing hidden-state dynamics from a single deterministic reasoning rollout.

For each candidate instance, SHIFT computes a reasoning-induced representation shift (RIRS), then combines this signal with a quality-weighted CoreSet selection procedure to build compact and diverse training subsets. The method is designed for large unlabeled pools where training-time signals, reward evaluation, or ground-truth answers are expensive or unavailable.

## Code Release

The code is currently being organized and cleaned up for release. We will update this repository with installation instructions, data preparation steps, data selection scripts, and evaluation commands as soon as the code is ready.

## Citation

Citation information will be added after release.
