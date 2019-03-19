# Airbus Ship Detection Challenge

Kaggle challenge: Airbus is excited to challenge Kagglers to build a model that detects all ships in satellite images as quickly as possible. Can you find them even in imagery with clouds or haze? 

# U-Net architecture
I used a well known segmentation network in order to detect ship in the sea. The network architecture is described below:
![unet](https://raw.githubusercontent.com/puechtom/airbus_satellite/master/u-net-architecture.png)

# Results
From left to right, original images, ground truth mask and predicted mask by the network:
![results](https://raw.githubusercontent.com/puechtom/airbus_satellite/master/results.png)
