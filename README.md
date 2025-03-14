# License Plate Detection from Video

This project detects Russian license plates in a video using OpenCV and a pre-trained Haar cascade classifier.

## Features
- Processes a video frame by frame
- Converts frames to grayscale for better detection
- Uses a Haar cascade classifier to detect license plates
- Draws bounding boxes around detected plates
- Displays real-time detection results
- Allows exiting by pressing 'q'

## Requirements
- Python 3.x
- OpenCV
- NumPy

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/license-plate-detection.git
   cd license-plate-detection
   ```
2. Install dependencies:
   ```sh
   pip install opencv-python numpy
   ```

## Usage
1. Place your video file inside the `DATA/` folder and name it `car_plate_video.mp4` (or update the filename in the script).
2. Run the script:
   ```sh
   python detect_plate_video.py
   ```
3. Press 'q' to exit the detection window.

## Files
- `detect_plate_video.py`: Main script for detecting license plates in a video.
- `DATA/haarcascades/haarcascade_licence_plate_rus_16stages.xml`: Haar cascade classifier for Russian plates.
- `DATA/car_plate_video.mp4`: Sample video file.


## License
This project is open-source and available under the MIT License.

## Author
Abdullah Ali Salem Ali

