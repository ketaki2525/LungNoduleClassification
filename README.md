# LungNoduleClassification
Early detection and classification of lung nodules play a crucial role in the diagnosis and treatment of lung cancer. This project leverages the Vision Transformer (ViT) architecture to classify lung nodules in CT scan images.

 Objectives:

-  Classify lung nodules into benign, malignant, and uncertain categories.
-  Use Vision Transformer to learn deep features from CT scan images.
-  Improve classification accuracy and reduce false positives.
-  Enable visual explanation using attention maps.

  Dataset:
  Preprocessing:
  - Image resizing to 224x224
  - Patch generation for ViT input
  - Normalization & augmentation

   Features

-  Transformer-based image classification
-  CT scan preprocessing pipeline
-  Class imbalance handling via weighted loss
-  Metrics: Accuracy, Precision, Recall, F1-score, AUC

  Tech Stack
 Language: Python
- PyTorch / TensorFlow
- Scikit-learn
- OpenCV / PIL
- Matplotlib / Seaborn
