# Eye Mouse Controller

This project tracks eye movement using a webcam and controls the mouse pointer based on pupil direction and gaze.

## 📁 Project Structure

- `Eye_tracker.py`: Main script that runs the eye-tracking interface.
- `import cv2.py`: Dependency or auxiliary script (may need refactoring).
- `README.md`: Documentation file.

## 👁️ Description

The project uses OpenCV to capture real-time webcam feed and detect eye positions. Based on gaze direction, the script moves the mouse pointer.

## ⚙️ Requirements

- Python 3.x
- OpenCV (`cv2`)
- pyautogui
- dlib
- imutils

Install via:
```bash
pip install opencv-python dlib imutils pyautogui
```

## 🚀 How to Run

1. Connect a webcam.
2. Run the script:
```bash
python Eye_tracker.py
```
3. The cursor should move based on your eye direction.

## ⚠️ Note

- Make sure `dlib` is installed correctly with shape predictor models.
- Works best in well-lit environments.

## 📄 License

MIT License.
