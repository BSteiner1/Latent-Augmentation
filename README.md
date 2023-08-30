# Latent-Augmentation

### A data augmentation method to improve the speed of re-training.
* We introduce noise to the latent features of the network in order to enhance data upsampling.

### The hypothesis was tested on the [MovieLens](https://grouplens.org/datasets/movielens/) dataset. 
* This dataset is a widely used dataset for building and evaluating recommender systems. It contains user ratings and movie information, making it a valuable resource for developing personalized recommendation algorithms.

### An example of the training process
* We see that the network trained on the original dataset (blue) learns much slower in the early stages of training.

![LearningPlot ](https://github.com/BSteiner1/Latent-Augmentation/assets/96544001/59189610-45ee-4bc5-8522-eb64a070c83a)

