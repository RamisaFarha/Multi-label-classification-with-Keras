# Multi-label-classification-with-Keras

This project focuses on multi-label image classification using a pre-trained Keras model. The aim is to classify fashion items into multiple categories, where each image can belong to more than one category.

##Dataset Overview
The dataset includes various fashion items, and each image is labeled with one or more of the following categories:

black_jeans
blue_dress
blue_jeans
red_dress
red_shirt
##Key Findings
Threshold Tuning: Multiple thresholds (0.3, 0.4, and 0.5) were tested to determine the best classification accuracy. A threshold of 0.4 gave the best balance between precision and recall for multi-label classification.
Prediction Outcome: The model successfully predicted the correct labels for images with high confidence, demonstrating that threshold tuning is critical for multi-label tasks. For instance, at a threshold of 0.4, it accurately predicted classes like blue_jeans for a given image.
##Conclusion
This project highlights the importance of threshold tuning in multi-label classification. By selecting an appropriate threshold, the Keras model was able to improve prediction accuracy across multiple categories.
