# ImageProcessing-ComputerVision-Assignments
The repository contains assignments for the exam Image Processing and Computer Vision in the first year of Artificial Intelligence Master in Unibo. In particular, assignments are present in the form of the following Jupyter notebooks:
1. [assignment_module_one.ipynb](assignment_module_one.ipynb): explore standard image processing techniques, and in particular object detection techniques, to accomplish the following task:

    Develop a computer vision system that, given a reference image for each book, is able to identify such book from one picture of a shelf.
    For each type of product displayed on the shelf, the system should compute a bounding box aligned with the book spine or cover and report:
    - Number of instances;
    - Dimension of each instance (area in pixel of the bounding box that encloses each one of them);
    - Position in the image reference system of each instance (four corners of the bounding box that enclose them);
    - Overlay of the bounding boxes on the scene images.
  
   To solve the task, sava the notebook and the dataset in the following path /content/drive/MyDrive/AssignmentsIPCV/ if using Colab.

   Starting from the standard use of algorithms such as Sift and Ransac, two different techniques have been tested to achieve the task: the use of inliers and masks.

2. [assignment_module_two.ipynb](assignment_module_two.ipynb): here, the goal of this assignment is to implement a neural network that classifies images of 37 breeds of cats and dogs from the Oxford-IIIT-Pet dataset. The assignment is divided into two parts:
    - in the first, a neural network for image classification is implemented from scratch;
    - in the second, fine-tuning a pretrained network provided by PyTorch, and in particular ResNet-18 with the same training hyperparameters used for best model in part 1. Tweak the training hyperparameters in order to increase the accuracy on the test split
