# A Convolutional Neural Network for Flood Detection on SAR Images

## Project Overview
This project leverages a Convolutional Neural Network (CNN) to detect flooded areas using SAR (Synthetic Aperture Radar) satellite images. By accurately classifying flooded vs. non-flooded regions, this model supports real-time environmental monitoring and disaster response efforts.

## Key Features
- **High Accuracy**: Achieved an 85% validation accuracy, with performance comparable to advanced architectures like ResNet and VGG.
- **Dataset Management**: Processed and labeled a dataset of 3,300+ SAR images, creating distinct classes for flooded and non-flooded regions.
- **Image Preprocessing**: Applied data augmentation techniques to improve the model's ability to generalize across varied flood conditions.
- **Pixel Analysis**: Validated data integrity through pixel distribution analysis, enhancing the model’s reliability.

## Dataset
- **Source**: The dataset comprises SAR images organized into flooded and non-flooded categories.
- **Preprocessing Steps**: Images were resized, organized, and augmented to ensure diverse training conditions.
- **Pixel Validation**: Black and white pixel distributions were analyzed across images to confirm data consistency.

## Model Architecture
- **CNN Architecture**: The model uses multiple convolutional and pooling layers to extract flood-relevant features from SAR images.
- **Comparison with ResNet and VGG**: Model performance was benchmarked against ResNet and VGG, achieving close accuracy while maintaining computational efficiency.
- **Training**: The model was trained for 20 epochs with a batch size of 28, optimizing with categorical cross-entropy loss and the Adam optimizer.

## Results
- **Validation Accuracy**: Achieved 85% accuracy on validation data, demonstrating high reliability in flood detection.
- **Test Accuracy**: Final model achieved an 82% accuracy on test data, proving effective in diverse flood scenarios.
