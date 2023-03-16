# Homework 2: Phoneme Classification

## Objectives:

- Solve a classification problem with deep neural networks (DNNs). 
- Understand recursive neural networks (RNNs).



## Baseline

- [ ] boss baseline: 0.83017
- [x] strong baseline: 0.74944
- [x] medium baseline: 0.66440
- [x] simple base line: 0.49798



## Hints

- simple : sample code 

- medium : concat n frames, add layers 

- strong : batchnorm, dropout

- boss : sequence-labeling (using  RNN) 



## What I did
- Concat 17 frames
- Add hiddden layers to 4
- Set hidden dimension to 1024
- Add batchnorm and dropout(0.35)

After training 100 epochs, I exceeded the strong baseline with **0.75038**. 

- Tried to use GRU, but only got 0.7189








