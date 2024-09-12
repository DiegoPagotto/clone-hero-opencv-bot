# Clone Hero OpenCV Bot

This project is an OpenCV-based application that captures screenshots, recognizes Clone Hero icons and sends in game commands to play the song

## Features

-   Capture screenshots using `pyautogui`
-   Process images using OpenCV
-   Recognize images and send in game commands

## Requirements

-   Python 3.x
-   `opencv-python`
-   `pyautogui`
-   `numpy`

## Setup

1. **Create a virtual environment**:

    ```sh
    python3 -m venv venv
    ```

2. **Activate the virtual environment**:

    ```sh
    source venv/bin/activate
    ```

3. **Install the required packages**:

    ```sh
    pip install opencv-python pyautogui numpy
    ```

4. **Update `requirements.txt`**:
    ```sh
    pip freeze > requirements.txt
    ```

## Usage

1. Run the main script:

    ```sh
    python main.py
    ```

2. The application will capture the screen and display the image. The image recognition functionality needs to be implemented in the `recognize_images` function.

## Contributing

Feel free to submit issues or pull requests if you have any improvements or bug fixes.
