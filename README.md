# Handwritten Character Recognition (A–Z)

A CNN-based system to recognize handwritten English 
characters A to Z using TensorFlow and OpenCV.

## Accuracy: 99.38%

## Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas, Matplotlib

## Dataset
- A-Z Handwritten Alphabets (Kaggle)
- 372,450 images

## Model Architecture
Input 28x28 → Conv2D(32) → MaxPool → Conv2D(64) 
→ MaxPool → Flatten → Dense(128) → Dense(26)

## How to Run
1. Open .ipynb in Google Colab
2. Upload kaggle.json
3. Run all cells top to bottom

## Results
- Test Accuracy: 99.38%
- Epochs: 10
- Train/Test Split: 80/20
