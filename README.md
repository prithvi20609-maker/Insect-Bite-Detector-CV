# Insect Bite Detection using Computer Vision

A Computer Vision project that uses a Keras-based model to detect and classify possible insect bites from images.

---

## Features

* Image-based detection of insect bite patterns
* Keras model trained on visual skin features
* Simple prediction pipeline using Python

---

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy

---

## Project Structure

* `keras_model.h5` → Trained model file
* `detector.py` → Script for running predictions
* `test_images/` → Folder for input images

---

## Setup & Installation

1. Install required libraries:

```id="setup_keras"
pip install tensorflow opencv-python numpy
```

2. Place the trained model file (`keras_model.h5`) in the project directory

   * If not included, provide a download link

---

## How to Run

1. Add test images to the `test_images/` folder

2. Run the detection script:

```id="run_keras"
python detector.py
```

3. The model will analyze the image and output whether an insect bite is detected

---

## Model Details

* Built using Keras (TensorFlow backend)
* Trained on images representing different skin conditions
* Uses visual patterns such as redness, swelling, and texture variations

---

## Example Output

* Normal Skin → No Bite Detected
* Affected Area → Possible Insect Bite

---

## Notes

* For educational purposes only – not a medical diagnostic tool
* Image quality and lighting may affect predictions

---

## Future Improvements

* Expand dataset with more diverse samples
* Improve classification accuracy
* Add multi-class detection for different bite types

---

## Author

Prithvi Biswas
