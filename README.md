# Breast_Cancer_Detection_System

This project focuses on detecting breast cancer using ultrasound images from the Dataset BUSI with GT. Key highlights include:

🖼️ Image Preprocessing: Masking and overlaying of images to enhance features, followed by resizing and augmentation.

🔄 Data Augmentation: Applied transformations like horizontal flipping, rotation, and color jitter to balance the dataset.

🧠 Model Development: Fine-tuned a pre-trained MobileNetV3 model, replacing the final layer to classify benign, malignant, and normal cases.

🎯 Training: Used early stopping to prevent overfitting, achieving an impressive 97% training accuracy.

📊 Evaluation: The model achieved a 97% test accuracy, with detailed classification reports and confusion matrices showing strong performance across all categories.

The final model effectively classifies benign, malignant, and normal breast ultrasound images, demonstrating high precision and recall across all categories.
