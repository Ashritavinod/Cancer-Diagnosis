##Cancer Classification Using Deep Learning##

This repository contains two Google Colab notebooks demonstrating deep learning-based approaches for cancer classification:

1. **Breast Cancer Classification using Neural Network**
2. **Skin Cancer Classification using AlexNet**

These projects aim to leverage neural networks and pre-trained architectures to improve the accuracy and reliability of medical image classification.

Project Notebooks

1. Breast Cancer Classification using Neural Network
- A simple feedforward neural network is built using TensorFlow/Keras.
- The model is trained to classify breast cancer as benign or malignant.
- Dataset used: [Wisconsin Breast Cancer Dataset](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))

2. Skin Cancer Classification using AlexNet
- Implements the AlexNet architecture for multi-class skin lesion classification.
- Uses transfer learning for better performance on limited data.
- Dataset: Skin cancer image dataset (e.g., HAM10000 or a custom dataset)

Technologies Used
- Python
- TensorFlow / Keras
- Google Colab
- NumPy, Pandas, Matplotlib
- Pre-trained CNNs (for transfer learning)

Files
- `breast_cancer_classification.ipynb`
- `skin_cancer_alexnet.ipynb`
- `summary_breast_cancer.md`
- `summary_skin_cancer.md`

How to Run
1. Open the notebooks in Google Colab.
2. Ensure required packages are installed.
3. Upload datasets as instructed or use provided links.
4. Run all cells to train and evaluate the models.

License
This project is open-source under the [MIT License](LICENSE).
