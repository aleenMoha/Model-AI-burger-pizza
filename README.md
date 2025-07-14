# Image Classification with Keras Model

This Python script loads a pre-trained Keras model to classify images. It processes an input image, normalizes it, and uses the model to predict the class label with a confidence score.

---

## Requirements

- Python 3.x
- TensorFlow and Keras
- Pillow (`pip install pillow`)
- NumPy (`pip install numpy`)

---

## Files

- `keras_model.h5` — The trained Keras model file.
- `labels.txt` — Text file containing class labels (one label per line).
- `download.jpg` — Sample image to classify (replace with your own image).

---

## Usage

1. Place the following files in your workspace or update the paths in the script:
   - `keras_model.h5`
   - `labels.txt`
   - The input image (default: `download.jpg`)

2. Run the script:

   ```bash
   python ai1.py
