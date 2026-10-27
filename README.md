# AI-Powered Tongue Print Analysis for Gender Classification

## 📌 Overview
An AI-based research project that uses deep learning and transfer learning to classify gender categories from tongue images. Developed in collaboration with a dental college, the project explores tongue-image patterns for biometric analysis.

## 🎯 Objectives
- Develop a deep learning model for tongue-image classification.
- Compare pretrained CNN architectures to identify a suitable model.
- Explore the potential of tongue images for research in biometric analysis.

## 🛠️ Tech Stack
- **Language:** Python
- **Framework:** TensorFlow
- **Approach:** Deep Learning, Transfer Learning
- **Models:** VGG16, VGG19, ResNet18

## 📂 Dataset
- Real-world dataset containing **1,500+ tongue images**.
- Used for training and evaluating gender classification models.
- Dataset access is restricted to the research project; images are not included in this repository.

## 🧠 Models Evaluated
The project compares three pretrained CNN architectures:

| Model | Accuracy |
|---|---:|
| VGG16 | 84.62% |
| VGG19 | 89.62% |
| ResNet18 | 88.68% |

**Current model selection:** ResNet18 was explored based on its lowest test loss (0.316) and balanced precision and recall.

## ⚙️ Methodology
1. Collect and prepare tongue images.
2. Preprocess images for model input.
3. Apply transfer learning using pretrained CNN architectures.
4. Train and evaluate the models.
5. Compare performance using accuracy, test loss, precision, recall, and F1-score.

## 📊 Results
- **ResNet18 Accuracy:** 88.68%
- **ResNet18 F1-Score:** 0.887
- **ResNet18 Test Loss:** 0.316
- **VGG19 Accuracy:** 89.62%

Model selection considers multiple evaluation metrics rather than accuracy alone.

## 🚀 Future Enhancement
- Extend the project to explore **age estimation** from tongue images.
- Evaluate model performance on larger and more diverse datasets.
- Investigate robustness and generalization across different imaging conditions.

## ⚠️ Disclaimer
This project is intended for academic research and experimentation. Its predictions are not a definitive determination of a person's gender, and the system is not intended for medical diagnosis or forensic identification without further validation.

## 👩‍💻 Project Status
Research and model evaluation are ongoing.
