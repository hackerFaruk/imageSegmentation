https://www.tensorflow.org/tutorials/images/segmentation

This tutorial uses the Oxford-IIIT Pet Dataset (Parkhi et al, 2012). The dataset consists of images of 37 pet breeds, with 200 images per breed (~100 each in the training and test splits). Each image includes the corresponding labels, and pixel-wise masks. The masks are class-labels for each pixel. Each pixel is given one of three categories:

Class 1: Pixel belonging to the pet.
Class 2: Pixel bordering the pet.
Class 3: None of the above/a surrounding pixel.

gets tesmro flow pip install git+https://github.com/tensorflow/examples.git
