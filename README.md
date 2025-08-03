# H-E-image-classification
Histopathological Image Classification Using CNNs and Logistic Regression - Logistic Regression was used as a baseline model and trained on the flattened grayscale images. The model used the ‘saga’ solver with multinomial loss for multiclass classification. 
CNN Architecture consisted of two convolutional layers followed by a dropout layer (rate 0.5) and a fully connected output layer mapping to five tissue classes. The model used cross-entropy loss and was trained using either the Adam or SGD optimizer with different learning rates.
Conv2D (3→16) → MaxPool → Conv2D (16→32) → MaxPool → Dropout → FC (32×7×7→5)
