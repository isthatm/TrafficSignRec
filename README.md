# Traffic Sign Classifer
- This repo contains source code to train, test and validate a Deep Neural Network against Vietnamese traffic sign dataset.
- To train a model, please refer to `src/TrafficSignTest.ipynb`.
- This work is inspired by [vamsiramakrishnan/TrafficSignRecognition](https://github.com/vamsiramakrishnan/TrafficSignRecognition) and [chengyangfu/pytorch-vgg-cifar10](https://github.com/chengyangfu/pytorch-vgg-cifar10)
- The obtained model can be coupled with a YOLO object-detection model to classify traffic signs in real-time, the detailed implementation can be found in `src/yolo_cam.py` 

# Architecture
- Before feeding images into the model, serveral image processing technqiues are implemented
   (gray scale conversion, thresholding, Gaussian blur, etc.) to separate traffic signs from background
- The model was observed to converge the accuray 90% benchmark faster when Multiscale Convolutional Network features were incorparated
  to enhance feature extraction.

  <p align="center">
    <img src="https://github.com/user-attachments/assets/7dd8c13d-7fe4-472a-9e5d-0ab1a3ef8e91" width="800">
  </p>

# Results
To be updated
