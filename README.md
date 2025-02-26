# Fashion-Item-Classfication-for-deep-learning
Overview
This project focuses on classifying fashion items into 20 different categories using deep learning techniques. The model is trained on a curated dataset and optimized for accuracy and efficiency. It leverages advanced architectures to enhance feature extraction and classification performance.

My primary contribution was in model development and training, where I implemented and fine-tuned multiple deep learning architectures to determine the most effective approach. I handled the data preprocessing and augmentation process, ensuring that the input images were normalized, resized to 224x224, and enhanced using techniques such as random horizontal flipping and normalization. These steps were essential for improving model generalization and reducing overfitting.

To achieve high accuracy, I focused on hyperparameter tuning, adjusting learning rates, weight decay, optimizers, and batch sizes to find the optimal training configuration. Additionally, I experimented with different loss functions, including CrossEntropyLoss and Focal Loss, to address class imbalance issues within the dataset.

Throughout the project, I tested several deep learning models, including MobileNetV2, ResNet50, SqueezeNet, DenseNet, and Vision Transformer (ViT). Among them, MobileNetV2 achieved the highest accuracy of 93.26%, with a macro F1-score of 0.88, outperforming other architectures. I utilized Adam and SGD optimizers along with a Cosine Annealing Scheduler to improve training efficiency. The models were trained using PyTorch and TensorFlow on high-performance GPUs (RTX 3090 & Google Colab A100).

The final model demonstrated state-of-the-art performance in fashion classification, making it ideal for real-time applications in e-commerce. Moving forward, I explored the possibility of integrating real-time classification into mobile applications and proposed multimodal data fusion by combining text and image inputs to enhance personalized recommendations.

This project highlights my expertise in deep learning, model optimization, and AI-driven fashion applications, demonstrating my ability to develop and refine machine learning solutions for industry use.
