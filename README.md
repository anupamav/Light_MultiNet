# Fruit and Vegetable Classification and Grading

## Description
Classify and grade fruit and vegetables using deep learning models.

## Dataset
*   **Name:** Any fruit and vegetable grading dataset
*   **Split Ratio:** The dataset should be split into training, validation, and test sets.

## Model Architectures
The following model architectures can be tested:
*   resnet18, resnet34, resnet50, mobilenet_v2, mobilenet_v3_small, mobilenet_v3_large, vgg16, vgg19, vit_b_16, efficientformer_l1, efficientformerv2_s1, resnet18_TF, ga_ghostnet

## Training
*   **Epochs:** 200
*   **Device:** CUDA or CPU
*   **Loss Function:** CrossEntropyLoss
*   **Optimizer:** Adam
*   **Learning Rate Scheduler:** ReduceLROnPlateau
*   **Early Stopping:** Patience on validation loss
*   **Model Saving:** Best model based on validation loss is saved.
