# Integration of Computer Vision and ML for Sports Celebrity Face Recognitionng

This project aims to develop a celebrity face recognition system using image preprocessing techniques and machine learning algorithms. The process involves detecting faces and eyes in images, cropping the facial regions, and extracting features using wavelet transforms. These preprocessed images are then used to train machine learning models for classification.

## Project Structure

The project is structured as follows:

- **Data Collection:** Images of celebrities are collected and organized into folders by celebrity name.
- **Preprocessing:** Images undergo preprocessing steps including face and eye detection, cropping, and wavelet transformation to extract features.
- **Model Training:** Machine learning models are trained on the preprocessed images to recognize celebrity faces.
- **Model Evaluation:** The trained models are evaluated using various metrics such as accuracy, precision, recall, and F1-score.
- **Model Selection:** Different machine learning algorithms such as Support Vector Machines (SVM), Random Forest, and Logistic Regression are evaluated, and the best-performing model is selected.
- **Model Deployment:** The selected model is saved for future use and deployment in face recognition applications.

## Dependencies:

- Python 3
- OpenCV
- NumPy
- Matplotlib
- scikit-learn
- PyWavelets
- Pandas
- Seaborn
- Joblib

## Conclusion:
this project demonstrates the process of building a celebrity face recognition system using image preprocessing techniques and machine learning algorithms. By detecting faces and eyes, cropping facial regions, and extracting features using wavelet transforms, we preprocess the images to enhance the performance of the machine learning models. Through the evaluation of various classifiers including Support Vector Machines, Random Forest, and Logistic Regression, logistic regression model achieves high accuracy, nearly 94%, and provides a robust solution for recognizing celebrity faces in images.
