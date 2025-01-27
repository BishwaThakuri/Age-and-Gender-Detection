# Age and Gender Detection

This project detects the gender and age group of a person from an image or live camera feed using pre-trained deep learning models.

## Features

- Detects gender (`Male` or `Female`).
- Predicts age group (e.g., `(0-2)`, `(25-32)`, `(60-100)`).
- Works with static images and live webcam input.

## Prerequisites

- Python 3.8+
- OpenCV (`cv2`)
- Pre-trained models:
  - `opencv_face_detector.pbtxt` and `opencv_face_detector_uint8.pb`
  - `age_deploy.prototxt` and `age_net.caffemodel`
  - `gender_deploy.prototxt` and `gender_net.caffemodel`

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/BishwaThakuri/Age-and-Gender-Detection.git
   cd Age-and-Gender-Detection
   ```

2. Install dependencies:

    ```bash
    pip install opencv-python numpy
    ````

3. Place the model files in the project directory.

4. Run the script. 

5. Press `q` to exit the camera.