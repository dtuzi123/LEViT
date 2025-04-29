>📋 The implementation of Online Task-Free Continual Learning via Expansible Vision Transformer

# Title : Online Task-Free Continual Learning via Expansible Vision Transformer

This repository is the implementation of Continual Unsupervised Generative Modeling.


# Paper link : 

# Abstract

Vision Transformers (ViTs) have lately shown remarkable data representation capabilities leading to state-of-the-art results in several vision and language learning tasks. Given its powerful representation ability, some recent studies have explored the ViT in continual learning by employing the dynamic expansion mechanism. However, these methods rely on the task information and therefore can not deal with a more realistic scenario, namely the Task-Agnostic Continual Learning (TACL). Unlike these ViT-based continual learning methods, this paper addresses TACL by proposing the Lifelong Expansible Vision Transformer (LEViT) model, which dynamically increases the model's capacity to deal with changes in the underlying probability distribution of the data representations learnt during continual learning. LEViT is implemented by an ensemble of transformers, each enabled with a multi-head attention mechanism and a linear classifier. We propose a new dynamic expansion mechanism which incrementally increases the capacity of LEViT without requiring task labels, by evaluating the statistical similarity between the joint distribution modeled by all previously learned components and the probabilistic representation of incoming data samples. The proposed expansion mechanism ensures the diversity of learnt knowledge by the components of LEViT. In addition, we introduce the Dynamic Knowledge Fusion (DKF) approach, aiming to explore the ViT feature representation ability for knowledge transfer. Specifically, we view all previously learnt components as an evolved knowledge base which provides prior knowledge for future learning. The proposed LEViT, when compared to the existing ViT-based methods, does not require any task information and can reuse previously learned representations to promote future task learning.


# Environment

1. pytorch
2. Python 3.7

## Training

To train the model(s) in the paper, run this command:

```train
python FiveRun_XXX.py
```






