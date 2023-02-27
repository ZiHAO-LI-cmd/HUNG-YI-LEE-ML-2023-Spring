# Homework 1: COVID-19 Cases Prediction (Regression)

## Objectives:

- Solve a regression problem with deep neural networks (DNN).
- Understand basic DNN training tips e.g. hyper-parameter tuning, feature selection, regularization, …
- Get familiar with PyTorch.



## Baseline

- [ ] boss baseline: 0.81456
- [x] strong baseline: 0.92619
- [x] medium baseline: 1.15678
- [x] simple base line: 1.96993



## Hints

- simple : sample code 

- medium : Feature selection 

- strong : Different optimizers and L2 regularization

- boss : Btter feature selection, different model architectures and try more hyper-parameters



## What I did

First, I dropped 1st col, which is useless `id`, then I used `SelectKBest` to select 24 best features from raw data.

After that, I tried to replace the `SGD` optimizer with `Adam` and use L2 regularization. I exceeded the strong baseline with **0.82367**.







