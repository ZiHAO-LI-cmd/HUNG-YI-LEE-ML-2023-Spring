# Homework 3: Image Classification

## Objectives:

- Solve image classification with convolutional neural networks(CNN).



## Baseline

- [x] boss baseline: 0.874
- [x] strong baseline: 0.814
- [x] medium baseline: 0.700
- [x] simple base line: 0.637



## Hints

- simple : Run Sample Code

- medium : Do some Data Augmentation & Train longer

- strong : Use predefined CNN from torchvision or TensorFlow 

- boss : Cross Validation + Ensemble or any other methods you know 



## What I did
- Do Data Augmentation:
```python
transforms.AutoAugment(policy=transforms.AutoAugmentPolicy.CIFAR10)
```
- Epoch:
**50**

- Pretrained Model:
[**ResNet50 + ResNet50_Weights.IMAGENET1K_V2**](https://pytorch.org/vision/stable/models.html)

I exceeded the strong baseline with **0.88333**, which of course is the way to cheat😄.








