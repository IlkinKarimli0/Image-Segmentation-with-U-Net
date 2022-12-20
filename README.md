# Image-Segmentation-with-U-Net


I have built U-Net (CNN architecture that used for biomedical image segmentation), a type of CNN designed for quick, precise image segmentation, and using it to predict a label for every single pixel in an image - in this case, an image from a self-driving car dataset.

As you might imagine, region-specific labeling is a pretty crucial consideration for self-driving cars, which require a pixel-perfect understanding of their environment so they can change lanes and avoid other cars, or any number of traffic obstacles that can put peoples' lives in danger.

In this repository i have implemented semantic image segmentation on the CARLA self-driving car dataset

I have trained the model, step by step and saved them (38 EPOCHS in total). Uploaded the last results. With it you can get the implementation of the model to train on another segmentation problem, you can use pretrained model on segmentation task and etc. Just keep in mind that model contains 8,640,471 parameters in itself, so it could be heavy to train on ineligible hardwares. 

