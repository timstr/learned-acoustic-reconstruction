# Learned Acoustic Reconstruction using Synthetic Aperture Focusing

## Tim Straubinger, Robert Xiao, and Helge Rhodin

Department of Computer Science, University of British Columba

Presented at ICASSP 2022

[doi.org/10.1109/ICASSP43922.2022.9746645](https://doi.org/10.1109/ICASSP43922.2022.9746645)

![system diagram](https://timstr.github.io/static/img/ml/thesis_system_diagram.png)

Many algorithmic approaches to 3D acoustic imaging have been devised which rely on a large abundance of receiving elements to produce images with delay-and-sum techniques, but these have found little use in air due to hardware complexity and low accuracy. Recent learning-based approaches to one-shot in-air acoustic reconstruction attempt to overcome these limitations using simple hardware and large datasets of geometry and echo pairs to train neural networks. How-ever, existing learned models use spatially-dense representations and attempt to predict entire scenes at once, requiring an abundance of data to truly generalize.We train an implicit neural network with no spatial awareness to predict the distance to the nearest obstacle at a single location from only time-delayed echoes. Using acoustic wave simulation, we show that our method yields better generalization and behaves more intuitively than competing methods while requiring only a fraction of the training data.

***

## Code

Please refer to our GitHub repository at [github.com/timstr/echo-thesis-project](https://github.com/timstr/echo-thesis-project).

## Data

Our primary datasets are available for download [here](https://drive.google.com/drive/folders/191fBomm7V3WLIyCj2exFJC1ad5GBFas-?usp=sharing).
