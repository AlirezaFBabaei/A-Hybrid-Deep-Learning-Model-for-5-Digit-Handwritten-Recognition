# A-Hybrid-Deep-Learning-Model-for-5-Digit-Handwritten-Recognition

This repository contains the code for the novel deep learning model described in the paper: [A Hybrid Deep Learning Model for 5-Digit Handwritten Recognition](https://ieeexplore.ieee.org/abstract/document/10496604), published in the proceedings of the 10th International Conference on Artificial Intelligence and Robotics (QICAR) (2024). The model utilizes Convolutional Neural Networks (CNNs) with an attention mechanism and stacked Gated Recurrent Unit (GRU) networks for handwritten 5-digit image prediction.

## Dataset Creation:

To evaluate the model's performance in recognizing 5 handwritten digits, a custom dataset was created. This dataset leverages the widely used MNIST dataset, containing grayscale images of handwritten digits from 0 to 9. Our approach involved randomly selecting and combining multiple MNIST digits to form new images containing 5 digits. Additionally, we applied data augmentation techniques to each image to further enrich the dataset and improve model generalization. This custom dataset facilitates the evaluation of the model's accuracy and effectiveness in recognizing and classifying 5-digit handwritten sequences.

## Model Functionalities:

* Convolutional neural network for feature extraction with Squeeze and Excitation blocks
* Stacked Gated Recurrent Unit (GRU) networks for sequence prediction
* Achieves high accuracy in 5-digit handwritten digit recognition
