# HW3 MachineLearning

This project uses pretrained convolutional neural networks (convnets) to practice data visualization techniques.

The convnet used is VGG19, which is a network which classifies images into either the category "cat" or "dog", i.e. the network detects if the photo is of a cat or a dog.

## This project incorporates these steps:
### Step 1:
  Feature extraction with data augmentation.

### Step 2:
  Fine-tune with data augmentation.

### Step 3:
  Visualize heatmaps of class activation for the the model obtained in Step 2.

### Step 4:
  Build an activation model that takes as input an image and produces as output the activation of the last conv layer of the model obtained   in Step 2. Using this activation model obtain the corresponding activations for the validation images. Apply t-SNE visualization to    these activations to see how well the convnet separates cats from dogs.
