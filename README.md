# Skin Cancer Detection

The project uses deep learning techniques, specifically Convolutional Neural Networks (CNN), to classify skin tumor images into three categories: malignant melanoma and two types of benign lesions, nevi and seborrheic keratoses.

The project utilized the concept of transfer learning, which involves using a pre-trained neural network as a starting point for training a new model. In this case, VGG-16 is used as the backbone for the image classification model, which is implemented using the Tensorflow library.
VGG-16 Architecture is as follows:

<img width="353" alt="Screenshot 2023-05-09 182201" src="https://github.com/AravindanVasudevan/Skin-Cancer-Detection/assets/57245944/241e04d6-61fb-4337-9d5b-0a7e50b0c4ad">

To train the model, a dataset that contained images of malignant skin tumors and two types of benign lesions is used. They then utilized a time-based learning rate decay strategy to optimize the model's training process. This technique gradually reduced the learning rate for each epoch, leading to improved model convergence over time.
Overall, the project aimed to create an accurate and efficient skin cancer detection model using deep learning techniques.

The graphs below shows the model's accuracy for the training and validation set for 25 epochs:

<img width="286" alt="Screenshot 2023-05-09 182225" src="https://github.com/AravindanVasudevan/Skin-Cancer-Detection/assets/57245944/1ba3a933-bc09-4bdc-87be-964514208089">

The graphs below shows the model's loss for the training and validation set for 25 epochs:

<img width="300" alt="Screenshot 2023-05-09 182305" src="https://github.com/AravindanVasudevan/Skin-Cancer-Detection/assets/57245944/7c9927a5-ae32-4ee8-8c6c-42eab9e3017f">
