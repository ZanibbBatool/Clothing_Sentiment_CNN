# Clothing_Sentiment_CNN
Optimized CNN model that classifies fashion product images into three style categories: Smart, Casual, and Formal using a fine-tuned VGG16 model and transfer learning techniques.

Dataset: fashion_data from Kaggle, 3 classes filtered: Smart, Casual, Formal

Preprocessing: Skipping missing data, label mapping, image rescaling and augmentaton

Model Architecture: VGG16 pretrained on Image Net, Dropout layers

Tech Stack: Python TensorFlow, Keras, Pandas, NumPy, ImageDataGenerator

Training Setup: 80 20 split, batch size 32, categorical cross entropy, rmsprop optimizer
Input Size: 150 x 150 pixels

Optimization: L2 regularization, Dropout, Augmentation, Transfer learning

Evaluation: accuracy, recall, f1-score, class distribution matrix
