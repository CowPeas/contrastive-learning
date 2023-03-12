# contrastive-learning

The main idea behind contrastive learning is to learn a similarity function that maps similar inputs closer together and dissimilar inputs further apart in the learned embedding space.


Contrastive learning is a technique used in unsupervised learning, where the goal is to learn representations of data without explicit labels.

The contrastive learning approach involves training a model to differentiate between similar and dissimilar examples by comparing them against each other. 

Specifically, the model learns to map an input example to a representation in a high-dimensional embedding space, where similar examples are mapped to nearby points and dissimilar examples are mapped to distant points.

During training, contrastive learning typically involves creating pairs or sets of examples, where some examples are similar (positive pairs) and others are dissimilar (negative pairs). 

The model is then trained to differentiate between the positive and negative pairs by maximizing the similarity between the positive pairs and minimizing the similarity between the negative pairs.

One common way to accomplish this is to use a contrastive loss function, such as the InfoNCE loss, that encourages the model to learn representations that make similar examples more similar and dissimilar examples more dissimilar. 

The InfoNCE loss involves maximizing the similarity between the positive pairs and minimizing the similarity between the negative pairs by using a softmax function over the dot product between the representations of the examples.
