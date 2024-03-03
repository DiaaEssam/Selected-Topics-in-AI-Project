# Enhancing Models' Scores Through Feature Extraction & Gray Wolf Optimization

This repository contains the code and research paper for the project "Modern Approach for Weed Recognition Using SVM GWO." The project focuses on utilizing Support Vector Machine (SVM) classifiers integrated with Convolutional Neural Network (CNN) architectures and Gray Wolf Optimizer for enhancing models' performance and accurate weed detection in agricultural images.

## Table of Contents

- [Research Paper](#research-paper)
- [Contents](#contents)
- [Methodology](#methodology)
- [Dataset](#dataset)
- [Code](#code)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Research Paper

The research paper titled "Modern Approach for Weed Recognition Using SVM GWO" by Mohammed Kamal, Diaa Essam, and Aly Waleed was published in December 2023. It explores the fusion of modified CNN architectures with SVMs at the classification layer to enhance classification performance. The paper discusses the application of this approach to the Plant Seedlings dataset and evaluates the efficacy of the proposed models against their original counterparts. The results provide insights into the potential enhancements achievable through the integration of SVM classifiers in CNN architectures.

## Contents

- `Modern_Approach_for_Weed_Recognition_Using_SVM_GWO.pdf`: The full research paper detailing the methodology, models, and outcomes of the project.

## Methodology

The project employs several widely used pre-trained CNN models, including ResNet50, EfficientNet, MobileNetV2, InceptionV3, and SqueezeNet, each modified to incorporate SVM classifiers. The primary objective is to leverage the feature extraction capabilities of pre-trained models with the discriminative power of SVMs for improved weed classification accuracy. The project also explores the use of Binary Grey Wolf Optimization (GWO) for feature selection to enhance interpretability and efficiency in weed detection models.

## Dataset

The project utilizes the Plant Seedlings Classification dataset hosted on Kaggle. This dataset involves the classification of plant seedlings into various species based on images of seedlings at an early stage. It comprises 12 classes with a total of 12,000 training examples in RGB format. Preprocessing steps, including dimensionality reduction and channel adjustment, were applied to ensure compatibility with the pre-trained models.

## Code

The code for implementing the weed recognition system using SVM GWO can be found in the `code` directory of this repository. The code is written in Python and utilizes popular machine learning libraries such as TensorFlow and scikit-learn. It includes scripts for data preprocessing, model training, and evaluation.

## Usage

To use the code in this repository, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/weed-recognition-svm-gwo.git`
2. Make a new notebook in Kaggle to access the pre-trained models and use any GPU of the accelerators available in Kaggle.
3. Import the cloned notebook in the notebook you created in Kaggle.
4. Run all or modify the code as you wish.

## Results

The research paper provides comprehensive comparative analysis results, showcasing the performance of the modified CNN architectures against their original counterparts. The results offer insights into the potential enhancements achieved through the integration of SVM classifiers in CNN architectures for weed recognition.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We would like to acknowledge the support and guidance provided by our supervisor during the course of this project.
