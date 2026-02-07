# blood-classification
Blood Cancer Classification Using Deep Learning
This project implements a deep learning–based framework for multiclass blood cancer classification using microscopic blood cell images. The proposed model combines Ghost Modules, Spatial Depthwise Convolution (SPD) blocks, and Multi-Dilated Convolution (MDC) blocks to achieve high accuracy while remaining computationally efficient.
The system is designed to assist automated hematology diagnostics by reducing manual effort and human error in traditional microscopic examination.

🚀 Key Features
Ghost Modules for lightweight and efficient feature extraction
SPD Blocks to capture fine-grained spatial cell morphology
MDC Blocks for multi-scale contextual feature learning
Auxiliary Classifier to improve training stability and convergence
Multiclass classification of four blood cancer types

📊 Dataset
Blood Cell Cancer (ALL – 4 Class) dataset
Microscopic peripheral blood smear images
Image size: 128 × 128
Train/Test split: 80% / 20%
Data augmentation: rotations, flips, brightness & contrast adjustments

🧠 Model Architecture
ConvBlock Stem
Ghost Module
SPD Block
MDC Block
Adaptive Average Pooling
Fully Connected Layer (4 classes)
Auxiliary Classifier (intermediate supervision)

📈 Results
Accuracy: 97%
Precision: 96%
Recall: 96%
F1-Score: 96%
The model shows strong and consistent performance across all four classes.

⚙️ Training Details
Loss Function: CrossEntropyLoss
Optimizer: Adam
Learning Rate: 0.001
Batch Size: 32
Epochs: 10
Hardware: GPU-enabled system

📌 Conclusion
This project demonstrates the effectiveness of hybrid CNN architectures in medical image classification. By combining efficiency-focused modules with multi-scale feature learning, the model achieves high accuracy and reliability, making it suitable for real-world clinical and research applications.
