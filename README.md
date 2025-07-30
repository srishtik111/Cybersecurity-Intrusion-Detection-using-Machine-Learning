# Cybersecurity-Intrusion-Detection-using-Machine-Learning

This project demonstrates the application of both supervised and unsupervised machine learning algorithms to detect cyber intrusions in network traffic data.
It compares the performance of:
1.)Random Forest Classifier (Supervised Learning)
2.)Isolation Forest (Unsupervised Anomaly Detection)

Dataset Source: Kaggle - [Cybersecurity Intrusion Detection Dataset](https://www.kaggle.com/datasets/dnkumars/cybersecurity-intrusion-detection-dataset)

*Workflow
1.)Data Preprocessing
    Encoding categorical features
    Standardization

2.)Dimensionality Reduction
    Applied PCA for 2D visualization

3.)Model Training
    Random Forest: trained with labeled data
    Isolation Forest: trained without using labels

4.)Evaluation
    Accuracy, classification report, confusion matrix

5.)Visualization
    PCA scatter plots of real vs predicted anomalies
    Feature importance from Random Forest


*Tools & Libraries
Python, Pandas, NumPy
Scikit-learn
Matplotlib

*Random Forest (Supervised Learning): Achieved an accuracy of 89.68% in detecting cybersecurity intrusions using labeled data.
*Isolation Forest (Unsupervised Learning): Achieved an accuracy of 62.91% in identifying anomalous sessions without requiring labels.
