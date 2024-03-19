### Scene Recognition with MiniPlaces Dataset

This Python file contains two neural network architectures for recognizing scenes using the MiniPlaces dataset. The MiniPlaces dataset consists of 100 different scene categories.

#### Neural Network Architectures:

1. **SimpleFCNet**:  
   - A simple neural network with fully connected layers.
   - Consists of two fully connected layers with ReLU activation functions.
   - Input shape: (28, 28) for MiniPlaces dataset.
   - Output: Class predictions for 100 scene categories.

2. **SimpleConvNet**:  
   - A simple convolutional neural network (CNN).
   - Utilizes convolutional layers followed by max-pooling and fully connected layers.
   - Input shape: (32, 32) for MiniPlaces dataset images.
   - Output: Class predictions for 100 scene categories.

#### Training and Evaluation Functions:
- **`train_model(model, train_loader, optimizer, criterion, epoch)`**: Trains the model using the specified optimizer and loss criterion.
- **`test_model(model, test_loader, epoch)`**: Evaluates the trained model on the test dataset and computes accuracy.

These functions facilitate training and evaluating the performance of the neural network models on scene recognition tasks using the MiniPlaces dataset.

#### Dependencies:
- Python
- PyTorch

For usage instructions, refer to the respective function documentation within the file.

### License

This project is licensed under the MIT License.

### Acknowledgments

Acknowledgments to the creators of the MiniPlaces dataset and the PyTorch community for providing valuable resources and tools for deep learning research.
