
🍃 Leaf Disease Detection using Deep Learning
📌 Overview
This deep learning project focuses on identifying and classifying 33 different types of plant leaf diseases using image recognition techniques. It leverages transfer learning on top of powerful pre-trained convolutional neural network (CNN) architectures to enhance accuracy while reducing training time.

Designed for agricultural experts, plant pathologists, and hobbyists, this system helps in quickly diagnosing plant diseases by analyzing leaf images, enabling timely interventions and improving crop health outcomes.

🖼️ Dataset
The model was trained on a large, labeled dataset of plant leaf images, covering:

Healthy leaves

33 distinct leaf disease classes

Each image is preprocessed (resizing, normalization, augmentation) to improve the model's generalization ability.

Features of the dataset:

High-resolution images

Varied lighting conditions and backgrounds

Diverse plant species and disease manifestations

🧠 Model Architecture & Approach
The project employs deep learning and transfer learning techniques for efficient training and superior accuracy.

Key components:

Pre-trained Base Models:
Examples: ResNet50, EfficientNetB0, MobileNetV2 (can be swapped in experiments)

Transfer Learning:
Freezes initial layers of the base model to retain learned visual features and fine-tunes the top layers on the custom leaf disease dataset.

Training Enhancements:

Data augmentation (rotation, zoom, shift, flip)

Early stopping & model checkpointing

Learning rate scheduling

Output:
Multi-class softmax classifier predicting one of 33 leaf disease categories.

📊 Performance Metrics
Accuracy

Precision / Recall / F1-Score per class

Confusion Matrix

Top-5 Accuracy (optional for comparison)

Graphs and logs for training/validation accuracy and loss curves are available to track performance improvements during training.

🎛️ Usage Instructions
To run the leaf disease detection system:

📦 Install Dependencies:
Ensure your Python environment has the required libraries. Install them via:

bash
Copy
Edit
pip install -r requirements.txt
🚀 Run the Application:
Launch the Streamlit-powered web app:

bash
Copy
Edit
streamlit run main.py
Features of the web app:

Upload a leaf image

Real-time prediction of disease class

Display of prediction probability scores

Optionally view model performance stats


## Usage

To use the model for leaf disease detection, follow these steps:

1. Make sure you have a Python environment set up with the necessary libraries installed. You can use the provided requirements.txt file to set up the required dependencies.

```
pip install -r requirements.txt
```

2. Run main.py

```
streamlit run main.py 
```

## Model Details
The leaf disease detection model is built using deep learning techniques, and it uses transfer learning to leverage the pre-trained knowledge of a base model. The model is trained on a dataset containing images of 33 different types of leaf diseases. For more information about the architecture, dataset, and training process, please refer to the code and documentation provided.


## Acknowledgments
We would like to acknowledge the contributions of the open-source community and the creators of the base model that this project builds upon. Your work and support are greatly appreciated.
