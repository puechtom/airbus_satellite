# Airbus Ship Detection Challenge
Github Pages: https://puechtom.github.io/airbus_satellite/

Kaggle competition: Airbus is excited to challenge Kagglers to build a model that detects all ships in satellite images.

The dataset is composed of 208 162 images with a resolution of 768 by 768 pixels. The dataset is splitted into 192 556 training images and 15 606 testing images. Example of satellite images:
![images](https://raw.githubusercontent.com/puechtom/airbus_satellite/master/images.png)

For training purpose, each training image has a corresponding segmentation mask. This mask will be used as ground truth for the network. The masks corresponding to the example images above:
![masks](https://raw.githubusercontent.com/puechtom/airbus_satellite/master/masks.png)

# U-Net architecture
I used a well known segmentation network, implemented with Keras in Python, in order to detect ships. The network architecture is described as below:
![unet](https://raw.githubusercontent.com/puechtom/airbus_satellite/master/u-net-architecture.png)

# Results
Since I do not have access to a powerful GPU, I can not properly train the network. Nevertheless, it acheives a true positive detection rate of almost 74%.

From left to right, original images, ground truth mask and predicted mask by the network:
![results](https://raw.githubusercontent.com/puechtom/airbus_satellite/master/results.png)
