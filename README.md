# Multi-label-classification-with-Keras

# Multi-label Classification with Keras

This project focuses on multi-label image classification using a pre-trained Keras model. The goal is to classify fashion items into multiple categories, where each image can belong to more than one category.

## Dataset Overview

The dataset contains various fashion items, and each image is labeled with one or more of the following categories:

- `black_jeans`
- `blue_dress`
- `blue_jeans`
- `red_dress`
- `red_shirt`

## Key Findings

- **Threshold Tuning**: Multiple thresholds (0.3, 0.4, and 0.5) were tested to optimize classification accuracy. A threshold of **0.4** provided the best balance between precision and recall in this multi-label classification task.
  
- **Prediction Outcome**: The model successfully predicted correct labels for images with high confidence. For example, at a threshold of 0.4, the model accurately predicted classes like `blue_jeans` for a given image.

## Conclusion

This project highlights the importance of threshold tuning in multi-label classification. By selecting the appropriate threshold, the Keras model was able to improve prediction accuracy across multiple categories.


