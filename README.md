### Resume

### Project Title: Training and Evaluation of VGG16 Model on MNIST Dataset

#### Objective:

To train a VGG16 convolutional neural network (CNN) model on the MNIST dataset for handwritten digit classification.
To evaluate the model's performance using accuracy, F1 score, and training time metrics.
Steps Taken:

#### Data Preparation:

The MNIST dataset containing grayscale images of handwritten digits was utilized.
Images were resized to fit the input size of the VGG16 model (224x224 pixels).
Grayscale images were converted to tensors and normalized.
Model Initialization:

The pre-trained VGG16 model from torchvision.models was loaded.
Modifications were made to the first convolutional layer to accept one input channel instead of three, suitable for grayscale images.
The final fully connected layer was replaced with a new one to classify 10 classes corresponding to digits 0 to 9.
Training and Evaluation:

The model was trained using the modified MNIST dataset.
Training was conducted over multiple epochs using stochastic gradient descent (SGD) optimizer with a learning rate of 0.001 and momentum of 0.9.
Evaluation of the trained model was performed using accuracy and F1 score metrics, with testing conducted on a separate test set.
Training time was measured to analyze the efficiency of the training process.
#### Results:

The adapted VGG16 model demonstrated effective performance in classifying handwritten digits on the MNIST dataset, achieving high accuracy and F1 score metrics.
The modifications made to the model's architecture allowed for compatibility with grayscale images, showcasing the versatility of transfer learning techniques.
Further optimizations and experimentation could be explored to enhance the model's performance and efficiency for digit recognition tasks.