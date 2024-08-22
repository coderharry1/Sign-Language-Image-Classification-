# Sign-Language-Image-Classification-

Project Overview:
The project focused on implementing and optimizing deep learning models to classify images of hand poses that correspond to letters in American Sign Language (ASL). The goal was to assess the feasibility of developing a lightweight application capable of translating ASL for people who do not sign or for those who sign in different languages or styles. The project required adhering to specific constraints, such as a limit of 50 training runs and a maximum of 500,000 parameters per model, while achieving high classification accuracy.

What I Did:
Implemented three different deep-learning models to classify ASL hand gestures:
Densely Connected Neural Network (DNN): A fully connected neural network model used as a baseline to establish initial performance metrics.
Convolutional Neural Network (CNN): A model designed to capture spatial features in the images, with convolutional layers, max-pooling layers, and dropout regularization to improve performance and prevent overfitting.
Optimized Convolutional Neural Network (Optimized CNN): An enhanced version of the CNN, where I systematically adjusted hyperparameters such as learning rates and dropout rates to further improve the model's accuracy.
Preprocessed the dataset by loading and scaling the image data, ensuring that the training, validation, and test sets were appropriately structured and free of data leakage.
Trained and evaluated the models, comparing their performance using accuracy metrics. I monitored learning curves to identify and mitigate underfitting or overfitting issues.
Optimized the models by fine-tuning hyperparameters and network architectures, focusing on improving the accuracy while adhering to the computational constraints.

Results:
Convolutional Neural Network (CNN):
Test Accuracy: 87.34%
The CNN significantly improved accuracy by capturing spatial features, but it required further optimization to meet the desired accuracy target.
Optimized Convolutional Neural Network (Optimized CNN):


The project demonstrated the effectiveness of CNNs in image classification tasks, especially when combined with systematic optimization techniques. The final results indicated that with further fine-tuning, the model could meet or exceed the target accuracy, making it a viable option for the ASL translation application.







