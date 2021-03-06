## Avoid Overfitting - Strategies
#### 1. Get more training data
#### 2. Reduce the capacity (degrees of liberty or complexity) of the network.
Alternatively one can use architectures that generalize quite well, such as the inverted convolutional pyramid comonly found in image classification.
#### 3. Add weight regularization.
#### 4. Add dropout.
#### 5. Data augmentation.

#### 6. Batch Normalization.
- Batch normalization reduces the dependence of your network to your weight initialization.
- Improves the gradient flow through the network.
- Adds regularization into your network.
- Effectively circumvents the dead ReLU problem by shifting and scaling the standard normal distribution accordingly.
