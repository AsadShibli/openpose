# Video and Webcam Landmark Detection with MediaPipe

This repository contains two Python scripts for detecting facial, hand, and body landmarks using the MediaPipe library. The scripts can be used to process videos or webcam feeds, providing annotated visualizations of detected landmarks.

## Files

### openpose.py

This script processes videos stored in the `vid` folder and generates annotated videos in the `output` folder. Each processed video will have facial, hand, and body landmarks overlaid on the frames.

### openpose(webcam).py

This script captures webcam feed and displays real-time annotations of facial, hand, and body landmarks. Users can interactively view the landmarks detected by the script.

## Usage

1. **Video Processing (openpose.py):**
    - Place the videos you want to process in the `vid` folder.
    - Run the `openpose.py` script.
    - Annotated videos will be saved in the `output` folder.

2. **Webcam Feed (openpose(webcam).py):**
    - Run the `openpose(webcam).py` script.
    - The webcam feed will display real-time annotations of facial, hand, and body landmarks.
    - Press 'q' to quit the application.

## Requirements

- Python 3.10
- MediaPipe library
- OpenCV

## Folder Structure

- `vid`: Contains input videos for processing (for `openpose.py`).
- `output`: Annotated videos will be saved in this folder (for `openpose.py`).
- No additional folders are required for `openpose(webcam).py`.

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
