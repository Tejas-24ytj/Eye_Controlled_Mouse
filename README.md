# Eye Controlled Mouse with Mediapipe, OpenCV-contrib-python, and PyAutoGUI

This project demonstrates how to build an eye-controlled mouse using Mediapipe for eye tracking, OpenCV with the `opencv-contrib-python` package for computer vision, and PyAutoGUI for mouse control.

## Requirements

- Python 3.x
- `mediapipe` library (`pip install mediapipe`)
- `opencv-contrib-python` library (`pip install opencv-contrib-python`)
- `pyautogui` library (`pip install pyautogui`)

## Usage

1. Clone or download the repository to your local machine.

2. Install the required dependencies:

    ```bash
    pip install mediapipe opencv-contrib-python pyautogui
    ```

3. Run the `eye_controlled_mouse.py` script:

    ```bash
    python eye_controlled_mouse.py
    ```

4. Calibrate the system by asking the user to look at specific points on the screen. This step helps establish a mapping between the user's eye movements and the mouse cursor.

5. Once calibrated, the script will continuously track the user's eye movements and move the mouse cursor accordingly.

6. To stop the script, press `q` on the keyboard.

## How It Works

- The script uses the `mediapipe` library to detect and track the user's eyes in real-time.

- OpenCV is used for image processing tasks, such as detecting the eyes and calculating the mouse cursor's position based on the detected eye movements.

- PyAutoGUI is utilized to control the mouse cursor position based on the calculated eye movements.

## Configuration

- You can adjust parameters such as the mouse sensitivity, eye detection thresholds, and calibration points in the `eye_controlled_mouse.py` script to fine-tune the behavior of the eye-controlled mouse.

## Notes

- Ensure that your environment has a webcam accessible to capture the user's face and eyes.

- The accuracy and performance of the eye-controlled mouse may vary depending on factors such as lighting conditions, camera quality, and user-specific characteristics.

- This project provides a basic implementation of an eye-controlled mouse. For production-grade applications, consider additional optimizations and user experience enhancements.

## Credits

- This project was inspired by various tutorials, articles, and open-source projects related to eye tracking and computer vision.

## License

This project is licensed under the [MIT License](LICENSE).
