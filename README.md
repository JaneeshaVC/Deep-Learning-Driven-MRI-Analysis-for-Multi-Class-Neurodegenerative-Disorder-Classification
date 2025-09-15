# Deep-Learning-Driven-MRI-Analysis-for-Multi-Class-Neurodegenerative-Disorder-Classification
Deep learning models for classifying Alzheimer’s and Parkinson’s disease from MRI. MobileNetV2 achieved state-of-the-art accuracy (~99.8%) with strong generalization, highlighting its potential for real-time, resource-efficient clinical diagnostics.

Neurodegenerative diseases, including Alzheimer’s disease (AD) and Parkinson’s disease (PD), pose 
significant global health challenges, necessitating early and accurate diagnosis. Traditional diagnostic 
approaches rely on clinical assessment and imaging interpretation, which are often time-consuming, 
subjective, and prone to variability. The present study investigates the application of deep learning 
frameworks for the automated classification of AD and PD using structural MRI data. Three 
architectures; a baseline 2D Convolutional Neural Network (CNN), ResNet50, and MobileNetV2, were 
developed, tuned, and critically evaluated for multi-class disease detection. The baseline 2D CNN 
achieved a validation accuracy of 86% after hyperparameter optimization, demonstrating stable 
convergence and effective generalization. ResNet50, while providing strong baseline feature extraction, 
exhibited instability and overfitting during fine-tuning, highlighting challenges associated with transfer 
learning on limited neuroimaging datasets. In contrast, the fine-tuned MobileNetV2 emerged as the 
most robust model, attaining a validation accuracy of approximately 0.998, strong discriminative 
performance across classes, and minimal overfitting. Minor limitations in minority class recall were 
noted, reflecting persistent challenges with imbalanced datasets. Comparative analysis with existing 
literature confirms that MobileNetV2’s performance is state-of-the-art, demonstrating its suitability for 
real-time and resource-constrained clinical applications. These findings underscore the potential of 
optimized deep learning models to facilitate early and accurate detection of neurodegenerative 
disorders, paving the way for clinically actionable AI-driven diagnostic tools. 
