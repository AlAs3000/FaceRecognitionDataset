# FaceRecognitionDataset
Dataset containing face images of five persons for face recognition tasks using CNN.
Face Recognition Dataset Using CNN
Overview
This dataset is designed for face recognition tasks using Convolutional Neural Networks (CNNs). It consists of images of five individuals, divided into training and testing sets. The dataset is structured to facilitate deep learning-based facial recognition research and model performance evaluation.

📂 Dataset Structure
The dataset is divided into two main folders:

Training Set (Train/): Contains five folders, each corresponding to a different person, with 300 images per person.
Testing Set (Test/): Contains five folders, each corresponding to a different person, with 25 images per person.
Directory Structure:
Copy
Edit
FaceRecognitionDataset/
├── Train/
│   ├── Person_1/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_300.jpg
│   ├── Person_2/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_300.jpg
│   ├── Person_3/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_300.jpg
│   ├── Person_4/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_300.jpg
│   ├── Person_5/
│       ├── img_1.jpg
│       ├── img_2.jpg
│       ├── ...
│       └── img_300.jpg
│
├── Test/
│   ├── Person_1/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_25.jpg
│   ├── Person_2/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_25.jpg
│   ├── Person_3/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_25.jpg
│   ├── Person_4/
│   │   ├── img_1.jpg
│   │   ├── img_2.jpg
│   │   ├── ...
│   │   └── img_25.jpg
│   ├── Person_5/
│       ├── img_1.jpg
│       ├── img_2.jpg
│       ├── ...
│       └── img_25.jpg
📷 Image Acquisition & Augmentation
The dataset was captured using a Realme smartphone camera with the following specifications:

Resolution: HD (1080p, 30 fps)
Aspect Ratio: 4:3 (12.5 MP)
Lighting & Conditions: Various natural lighting and indoor settings.
Applied Data Augmentation:
To enhance model generalization and avoid overfitting, the following transformations were applied:

Rotation: ±30 degrees
Brightness Adjustment: (0.75–1.25)
Gaussian Noise Addition
Scaling: (80%–120%)
🛠️ CNN Architecture Used for Training
This dataset was used to train multiple CNN models with different layer configurations. The tested architectures included:

Convolutional Layers (1 to 3)
Batch Normalization
ReLU Activation
MaxPooling
Fully Connected Layers
Dropout Regularization
Softmax Classification Layer
For a detailed performance comparison, refer to the associated research paper.

🖥️ Software & Hardware Requirements
MATLAB 2023 with Deep Learning Toolbox
Hardware used for training:
Processor: Intel Core i7-13620H (13th Gen, 2.4 GHz)
RAM: 16 GB
GPU: NVIDIA (4 GB)
📚 How to Cite
If you use this dataset in your research, please cite it as follows:


[Ali H. H. Al-Amili], "Face Recognition Dataset Using CNN", GitHub repository, 2025. [Online]. Available: [https://github.com/AlAs3000/FaceRecognitionDataset.git]
✉️ Contact
For inquiries, suggestions, or collaboration opportunities, feel free to reach out:

📧alihh@uomustansiriyah.edu.iq
© 2025 [Ali H. H. Al-Amili]. All Rights Reserved.
