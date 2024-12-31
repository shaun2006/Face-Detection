# Face Detection using Python

This project implements a simple face detection algorithm using OpenCV in Python. It detects faces from an image using a pre-trained classifier. 

## Requirements

Make sure you have Python installed on your system. You will need to install OpenCV for Python, which can be done easily using `pip`.

### Installation

1. First, install the necessary Python packages:
    ```bash
    pip install opencv-python
    ```

2. Replace `test1.jpg` with your own image for face detection. Ensure the image is in the same directory as the script, or update the file path in the script accordingly.

## How to Run

1. Place your image (for example, `test1.jpg`) in the same directory as the script.
2. Run the `main.py` script to detect faces in your image:
    ```bash
    python main.py
    ```

## How it Works

1. The script loads the image (`test1.jpg` by default) and applies the face detection using OpenCV’s Haar Cascade Classifier.
2. Detected faces are highlighted with rectangles, and the output image is displayed.

## License

This project is licensed under the GPL 3 License.
