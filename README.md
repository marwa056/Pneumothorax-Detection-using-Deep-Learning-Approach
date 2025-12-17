Pneumothorax Binary Classification on Chest X-Rays

- This project focuses on binary classification of pneumothorax from chest X-ray images using deep learning. The dataset is highly imbalanced, with far fewer pneumothorax cases than normal images. To tackle this, we applied data preprocessing, augmentation, and class weighting to improve model performance on the minority class.

Key steps include:

- Image preprocessing (resizing, normalization, CLAHE)

- ratified splitting into training, validation, and test sets

- Data augmentation to enhance training diversity

- Handling class imbalance with weighted loss

- Model training and evaluation using metrics sensitive to class imbalance (F1-score, recall)

- Experiments with two CNN architectures: DenseNet121 and ResNet50 for comparative performance

- The goal is to develop a robust model for accurate pneumothorax detection, with potential applications in clinical decision support systems.
