# Image-Classification

## Overview
This project is a Python-based graphical user interface (GUI) for image classification, utilizing TensorFlow for deep learning and the Taipy library for GUI development. The application allows users to select an image from their file system, and a pre-trained model predicts the content of the image among ten different classes.

## Prerequisites
- Python: Ensure you have Python 3.x installed.
- Libraries: Install the required libraries using the following command:
```
pip install taipy tensorflow pillow numpy
```

## Getting Started
1. Clone the Repository:
```
git clone https://github.com/akhilathuluri/Image-Classification.git
cd Image-Classification
```
2. Download Pre-trained Model:
  - Download the pre-trained model file named "baseline.keras" and place it in the project directory.
3. Virtual Environment (Optional):
  - It's recommended to create a virtual environment to isolate dependencies.
```
python -m venv venv
source venv/bin/activate  # On Windows, use "venv\Scripts\activate"
```
4. Run the Application:
```
python classifier.py
```
## Application Features
### File Selector
- Use the file selector to choose an image file with a ".png" extension from your file system.
## Image Prediction
- The selected image is preprocessed and fed into a pre-trained TensorFlow model.
- The predicted class and confidence level are displayed in the GUI.
## Display
- The GUI displays the selected image along with the predicted class and confidence level.

## Code Structure
'classifier.py
- Main script containing the code for the GUI application.
- Imports: Taipy, TensorFlow, Pillow, and NumPy libraries.
- Model Loading: Loads the pre-trained TensorFlow model from "baseline.keras".
- Prediction Function: Defines a function to predict the content of the selected image.
- GUI Layout: Sets up the GUI layout using Taipy syntax.
- Callback Function: Defines a callback function for image selection and prediction updates.
- Application Execution: Initializes and runs the GUI using the Gui class from Taipy.

## Additional Notes
- This code can be extended to support batch processing, multiple model selection, and additional preprocessing options.
- Ensure that the provided model file ("baseline.keras") is compatible with the TensorFlow version used in the project.

## video -
https://www.youtube.com/watch?v=h0dglh9elCw

