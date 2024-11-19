# Distracted-Driver-Detection-model-comparison

This project evaluates and compares the performance of several Convolutional Neural Network (CNN) architectures for detecting distracted drivers using the State Farm dataset, which categorizes driver behaviors into 10 distinct classes. The study explores both standard and custom CNN models to determine the most effective architecture for this task.


## Objectives:

-> Train and evaluate multiple CNN architectures on the State Farm dataset.

-> Compare model performance using metrics such as loss, accuracy, and confusion matrices.

-> Identify the most effective CNN architecture for distracted driver detection.


## Models Compared:

-> Pre-trained architectures: ResNet50, VGG16, VGG19, EfficientNet B3.

-> Custom CNN model designed specifically for this dataset.


## Methodology:

-> Data augmentation techniques were applied to improve model generalization.

-> Each model was trained using the same dataset split to ensure a fair comparison.

-> Performance metrics (accuracy, loss) were tracked over epochs, and confusion matrices were generated to analyze classification errors.


## Key Findings:

-> EfficientNet B3 achieved the highest testing accuracy of 96%, making it the top-performing model.

-> VGG16 had the lowest testing accuracy at 89%, highlighting limitations in its ability to handle the dataset's complexity.

-> Loss and accuracy plots demonstrated consistent training for most models, with minimal overfitting.

-> Confusion matrices revealed common misclassifications, providing insights for future model improvements.
