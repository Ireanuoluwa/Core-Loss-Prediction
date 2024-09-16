# Predicting Heat Loss in Inductor Cores
Overview

This project aims to predict heat loss in inductor cores using machine learning techniques. By exploring various models, we sought to improve upon traditional methods for calculating core loss, such as the Steinmetz Equation, which provides empirical estimates of core loss based on material properties and waveform characteristics.
Key Contributions

    Machine Learning Models: We investigated several models, including Linear Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Random Forest, and XGBoost. Although traditional models provided insight, neural network-based models, specifically Feedforward Neural Networks (FNN) and Long Short-Term Memory (LSTM), showed the best performance for predicting core loss.
    Deep Learning: The project delved into advanced techniques like sequence-to-scalar modeling using LSTM architectures. These models handled time-varying magnetic flux data, significantly reducing prediction errors.
    Data Augmentation: To ensure robust model training, data augmentation techniques like circular shifting and the addition of noise were applied, allowing the models to generalize better across different waveform shapes.

Conclusion

Our work demonstrates that deep learning approaches outperform conventional methods in predicting core loss in magnetic materials, particularly for the N87 material. Future efforts should focus on refining these models for a broader range of materials and further optimizing machine learning techniques to minimize errors.
