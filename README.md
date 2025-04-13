# Image-Classification-of-Animals-using-Transfer-Learning
To build a robust image classification system that identifies animals in images using deep learning. The goal is to implement a solution using transfer learning for high accuracy and efficiency.
 
 Project Summary
This project utilizes a dataset containing 15 animal classes with images of size 224x224x3. Each class is stored in separate folders. We apply Transfer Learning with VGG16, a proven Convolutional Neural Network, using Keras and TensorFlow in Google Colab. The final model achieves high accuracy and is capable of classifying new, unseen animal images effectively.

Code-https://colab.research.google.com/drive/13dJFiP555pWHeKJa2jRbwtI2ghtdYvD5

Dataset
Each folder represents one of the following animal classes:

Bear, Bird, Cat, Cow, Deer, Dog, Dolphin, Elephant, Giraffe,
Horse, Kangaroo, Lion, Panda, Tiger, Zebra

Images are resized to 224x224x3.

Technologies Used
Python
TensorFlow & Keras
Google Colab
MobileNetV2 
Matplotlib & Seaborn

Results
Final training accuracy: 89+
Model generalizes well on unseen data (validation set).

Successfully distinguishes among 15 animal classes.

Learnings
Hands-on experience with Transfer Learning using MobileNetV2
Implemented ImageDataGenerator for augmentation.
Learned model evaluation using matplotlib visualizations.
Trained and saved a model for real-world prediction use cases.
