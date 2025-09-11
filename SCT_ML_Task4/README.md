# **🖐️ Task 4: Hand Gesture Recognition**

**🎯 Project Objective**

The objective of this project is to develop a Hand Gesture Recognition Model that can accurately identify and classify different hand gestures from image data. Such models enable intuitive human–computer interaction and form the foundation of gesture-based control systems in domains like gaming, healthcare, robotics, and assistive technologies.

**📂 Dataset**

Source: Kaggle Hand Gesture Dataset (~2 GB)

Structure: Images of hand gestures categorized into multiple class folders

Format: PNG image files

Preprocessing Applied:

Resized images to 64×64 pixels

Normalized pixel values to the range [0,1]

Used ImageDataGenerator for training and validation split

**🧠 Model Architecture**

A Convolutional Neural Network (CNN) was implemented using TensorFlow/Keras.

Layers used:

Conv2D & MaxPooling: Feature extraction

Flatten: Converts 2D features into a vector

Dense Layers: Fully connected layers for classification

Dropout: Prevents overfitting

Softmax Output Layer: Predicts gesture class probabilities

Training Details:

Optimizer: Adam

Loss Function: Categorical Crossentropy

Epochs: 10 (can be tuned further)

Batch Size: 32

**📊 Results**

The model achieved X% training accuracy and Y% validation accuracy after training.

Successfully tested on random images from the dataset.

Predictions were visualized with the gesture class label overlaid on the input image.

**🚀 Key Features**

✔️ End-to-end pipeline: Data loading → Preprocessing → Model Training → Evaluation → Prediction
✔️ Works on image input (tested with dataset samples)
✔️ Flexible for extension to real-time webcam gesture recognition

**🔮 Future Scope**

Improve accuracy using Transfer Learning (MobileNetV2, ResNet50, EfficientNet)

Deploy model for real-time video gesture recognition

Extend dataset with more complex hand gestures and backgrounds

Integrate with IoT or robotics for gesture-based control

**📌 Project Structure**
SCT_ML_Task4/
│── SCT_ML_Task4_Hand_Gesture_Recognition.ipynb   # Colab notebook
│── README.md                                     # Project documentation
│── results/                                      # (Optional) Prediction samples

**🙌 Acknowledgement**

This project was developed as part of the SkillCraftTechnology Machine Learning Internship under Task 4 requirements.
