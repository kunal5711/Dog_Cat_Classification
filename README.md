# Dog vs Cat Classifier

This project is a Convolutional Neural Network (CNN) built using Keras to classify images of dogs and cats. 

## Installation

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory:**
    ```bash
    cd <project-directory>
    ```

3. **Create and activate a virtual environment:**
    ```bash
    python -m venv .venv
    .\.venv\Scripts\activate  # On Windows
    source .venv/bin/activate  # On macOS/Linux
    ```

4. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Train the model:**
    ```python
    python train_model.py
    ```

2. **Predict using the trained model:**
    ```python
    python predict_image.py --image_path <path-to-image>
    ```

## Files

- `model.h5`: Saved model file.
