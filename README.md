# AIXHW5

# Explainable AI: Investigating Saliency Map Changes Under Adversarial Perturbations

This notebook investigates how adversarial perturbations affect a neural network's attention patterns by analyzing differences in saliency maps between clean and adversarially perturbed images.

## Project Overview
- Uses ResNet-34 pre-trained model for image classification
- Implements FGSM (Fast Gradient Sign Method) for generating adversarial examples
- Generates and compares saliency maps between original and perturbed images
- Quantifies differences in model attention using similarity metrics

## Requirements
- PyTorch
- torchvision
- torchattacks
- matplotlib
- numpy
- PIL

## Dataset
Navigate to **AIXHW5** and follow this path to access the dataset:
1. /Explainable AI
2. /train
3. /n12267677

Download the entire 'train' folder and place it in your working directory. While the original analysis used 500 images, GitHub file limitations restricted the upload to approximately 100 images. This reduced dataset is sufficient to replicate the analysis and demonstrate the effects of adversarial perturbations on saliency maps.

## Results
The analysis demonstrates significant differences between saliency maps of clean and adversarially perturbed images, with an average similarity score of 0.079, supporting the hypothesis that adversarial perturbations meaningfully alter the model's attention patterns.
