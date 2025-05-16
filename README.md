Conclusion:
In this project, I implemented both a custom CNN and a transfer learning model with fine-tuning for pneumonia detection from chest X-ray images. While transfer learning proved to be more effective than the custom CNN in terms of accuracy and feature extraction, the model initially suffered from overfitting. By adding a validation_split=0.1 to the training data generator and setting shuffle=True for training and shuffle=False for validation and test sets, the final model achieved improved performance with reduced overfitting, resulting in the best outcome of the project.

