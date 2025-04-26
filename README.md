# Trading-Recommendation-system
Developed a deep learning model to recognize stock chart patterns and generate trading recommendations (Buy, Sell, Hold), utilizing image-based inputs instead of traditional numerical stock data.

Deep Learning & Image Processing: Built a custom Convolutional Neural Network (CNN) architecture inspired by LeNet to process candlestick chart images. Implemented data loading, preprocessing, and normalization pipelines using OpenCV and TensorFlow.

Model Development:
Designed and trained a CNN model to classify stock chart patterns with categorical cross-entropy loss and Adam optimizer. Applied one-hot encoding for label preparation and split datasets strategically to validate model generalization.

Visualization & Evaluation:
Created dynamic plots to visualize model performance (training/validation loss and accuracy) over epochs. Conducted manual testing on unseen chart images to assess prediction accuracy and model robustness.

Outcome:
Achieved an automated trading recommendation system capable of interpreting stock charts visually, streamlining pattern recognition for traders and reducing reliance on manual analysis.
