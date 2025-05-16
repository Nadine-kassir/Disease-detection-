This project aimed to develop an accurate and robust deep learning model for pneumonia detection using chest X-ray images.The approach was based on Convolutional Neural Networks (CNNs) and Transfer Learning,
allowing the model to learn rich visual features from a pre-trained network and adapt them to the medical imaging domain.
Conclusion:
While transfer learning proved to be more effective than the custom CNN in terms of accuracy and feature extraction, the model initially suffered from overfitting.By adding a validation_split=0.1 
to the training data generator and setting shuffle=True for training and shuffle=False for validation and test sets, the final model achieved improved performance with reduced overfitting. 



