# Sign-Language-Image-Classification-

Project Overview
This project dives into the world of deep learning to unlock the potential of translating American Sign Language (ASL) through a lightweight application. The challenge? To build and optimize models capable of accurately classifying hand poses corresponding to ASL letters. With the ultimate goal of bridging communication gaps for non-signers and those using different sign languages or styles, I tackled this project under strict constraints: no more than 50 training runs and a maximum of 500,000 parameters per model—all while aiming for top-notch accuracy.

What I Did
To bring this vision to life, I implemented and fine-tuned three distinct deep-learning models:

Densely Connected Neural Network (DNN): Kicked off with a fully connected neural network to lay down the baseline performance metrics. This model served as a foundation to understand the complexities of the data.
Convolutional Neural Network (CNN): Took it up a notch with a CNN, specifically designed to capture the intricate spatial features of ASL hand gestures. By incorporating convolutional layers, max-pooling, and dropout regularization, I significantly boosted performance while keeping overfitting at bay.
Optimized Convolutional Neural Network (Optimized CNN): Pushed the boundaries by systematically tweaking hyperparameters like learning rates and dropout rates. The result? A more refined and accurate model that stands closer to our goal.
The journey involved meticulous data preprocessing—loading, scaling, and structuring the datasets for training, validation, and testing—all while ensuring data integrity. I trained and evaluated each model, carefully monitoring learning curves to identify and counteract any signs of underfitting or overfitting. The final step was to optimize these models, fine-tuning every detail to squeeze out the best possible performance within the given constraints.

Results
Convolutional Neural Network (CNN):
Test Accuracy: 87.34%
This model made a significant leap in accuracy by effectively capturing the spatial nuances of ASL gestures, though it still called for further optimization to hit the target.
Optimized Convolutional Neural Network (Optimized CNN):
The optimized CNN showed tremendous promise, edging ever closer to the desired accuracy goal. Through careful tuning and architectural adjustments, this model emerged as a top contender for the ASL translation task.
Conclusion
This project not only showcased the power of CNNs in image classification but also highlighted the importance of systematic optimization. With a few more refinements, the model is on track to exceed the accuracy targets, making it a strong candidate for a real-world ASL translation application. The journey from baseline DNN to an optimized CNN reflects a clear path of innovation and relentless pursuit of excellence.





