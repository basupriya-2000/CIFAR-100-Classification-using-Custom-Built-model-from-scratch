# CIFAR-100-Classification-using-Custom-Built-model-from-scratch
This code defines a modified version of the ResNet architecture with Squeeze-and-Excitation (SE) blocks and introduces dropout. The model is trained on the CIFAR-100 dataset.
Prerequisites
Make sure you have the following libraries installed:

pip install torch torchvision numpy matplotlib
Model Architecture
The model consists of a modified ResNet101 architecture with Squeeze-and-Excitation blocks and dropout. The ResNet blocks have been replaced with ModifiedBottleneck blocks.

Data Augmentation
The training data is augmented using random crops, random horizontal flips, and normalization. The test data is normalized without augmentation.

Training
The model is trained using the cross-entropy loss function and stochastic gradient descent (SGD) optimizer. A learning rate scheduler is used to adjust the learning rate during training.

Results
The test accuracy of the model is 75.29% after training for 50 epochs on the 50 layer model, Accuracy can be further increased by implementing 101 or 152 layer model.

Feel free to modify hyperparameters or experiment with different architectures based on your specific requirements.

About
CNN architecture inspired from ResNet with Squeeze-and-Excitation (SE) blocks and introduces dropout. The model is trained on the CIFAR-100 dataset.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
100.0%
Footer
