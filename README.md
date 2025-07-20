# Brain-Tumor-Detection using VGG16

This project implements a deep learning-based brain tumor detection system using the VGG16 architecture. It analyzes MRI scans and identifies the presence and type of brain tumor among four classes:

1.Glioma

2.Meningioma

3.Pituitary

4.No Tumor

Unlike simple classification, this model focuses on detecting whether a tumor is present, and if so, determining its specific type. The model was trained on a curated dataset of brain MRI images from kaggle using transfer learning.

About VGG16

VGG16 is a popular deep convolutional neural network developed by the Visual Geometry Group at Oxford. It consists of 16 layers (13 convolutional + 3 fully connected) and uses small 3x3 filters throughout. Known for its simplicity and strong performance, VGG16 is widely used in image classification and detection tasks. In this project, we fine-tuned VGG16 on MRI scans to detect and differentiate tumor types.

