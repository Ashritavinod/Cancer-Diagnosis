# Summary: Breast Cancer Classification using Neural Network

## Dataset
- **Name**: Wisconsin Breast Cancer Dataset (Diagnostic)
- **Features**: 30 numerical features extracted from digitized images of breast mass cell nuclei.
- **Labels**: Binary classification — Malignant (M) or Benign (B)

## Model
- A simple feedforward neural network built using Keras.
- Architecture includes:
  - Input layer matching feature shape
  - One or more hidden layers with ReLU activation
  - Output layer with sigmoid activation

## Workflow
1. Data loading and preprocessing (standardization and label encoding)
2. Splitting into training and test sets
3. Building the model architecture
4. Compiling with binary crossentropy loss and Adam optimizer
5. Training the model
6. Evaluating accuracy and visualizing performance

## Results
- Accuracy achieved: Typically over 95% on test data (varies by training)
- Confusion matrix and loss/accuracy plots included

## Key Takeaways
- Simple neural networks can achieve strong performance on structured datasets.
- Proper preprocessing and tuning are crucial for accuracy.
