```markdown
# Simple Python Screen Recorder

This is a simple screen recorder tool created using Python by NeuralNine.

## Installation

To use this screen recorder, follow these steps:

1. Clone the repository:

```
git clone https://github.com/https-alisha/screen-recorder.git
```

2. Navigate to the directory containing the script.

3. Ensure you have the required dependencies installed:

```
pip install opencv-python pyautogui
```

## Usage

To start recording your screen, run the following command:

```
python main.py
```

The recording will start immediately. To stop the recording, press `q`.

## Features

- Records the screen at a specified frame rate.
- Saves the recording as an AVI video file.

## Parameters

- `SCREEN_SIZE`: Tuple representing the screen resolution (default is 1920x1080).
- `fps`: Frames per second for the recording (default is 120).
- `output.avi`: Output filename for the recording.

## How it works

This screen recorder captures screenshots using the `pyautogui` library and converts them into a video using `OpenCV` (`cv2`). It continuously captures screenshots at a specified frame rate and writes them into a video file.

## Issues

- This script captures the entire screen. There's currently no option to record a specific region of the screen.

## Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests to enhance the functionality of this screen recorder.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
```
