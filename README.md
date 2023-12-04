# MachineLearning

# Deep Learning Fashion MNIST Data
## Introduction
In this project, we developed three deep-learning models using the Fashion MNIST dataset, which contains labeled images of fashion items. The dataset is split into training data with labeled images and testing data with unlabeled images. The objective is to create models for image classification, and the final accuracy is computed as the average of the three individual models.

### Model 1
Sequential model used.
Flatten layer to convert to 1-dimensional.
1 Dense layer with ReLU activation.
Output layer with 10 variables.
Model accuracy: 0.7966, Loss: 0.59.

## Model 2
Sequential model used.
Flatten layer to convert to 1-dimensional.
1 Dense layer with Sigmoid activation.
Output layer with 10 variables.
Model accuracy: 0.7059, Loss: 0.9158.
Note: ReLU demonstrated better performance compared to Sigmoid.

### Model 3
Sequential model used.
Flatten layer to convert to 1-dimensional.
1 Dense layer of 100 neurons with ReLU activation.
1 Dense layer of 300 neurons with ReLU activation.
Batch normalization layer.
Dropout layer with rate 0.25.
Output layer with 10 variables.
Model accuracy: 0.881, Loss: 0.355.

### Combined Model
The combined model averages the predictions from Model 1, Model 2, and Model 3.
Combined model accuracy: 0.794.

### Conclusion
After evaluating the three models, it is evident that Model 3 outperforms the others with an accuracy of 0.881 and a lower loss of 0.355. The use of ReLU activation in Model 3 proved more effective than Sigmoid. The combined model, an average of all three models, achieved an accuracy of 0.794, slightly lower than Model 3. In summary, ReLU activation and the architecture of Model 3 are considered optimal for the Fashion MNIST dataset.
