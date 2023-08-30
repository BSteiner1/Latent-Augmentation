# Latent-Augmentation

### A data augmentation method to improve the speed of re-training.
* We introduce noise to the latent features of the network in order to enhance data upsampling.

### The hypothesis was tested on the [MovieLens](https://grouplens.org/datasets/movielens/) dataset. 
* This dataset is a widely used dataset for building and evaluating recommender systems. It contains user ratings and movie information, making it a valuable resource for developing personalized recommendation algorithms.

### An example of the training process
* We see that the network trained on the original dataset (blue) learns much slower in the early stages of training.

![AELearningPlot](https://github.com/BSteiner1/Latent-Augmentation/assets/96544001/bb6c878f-29d5-4c14-94c9-cae45100d0cb)
