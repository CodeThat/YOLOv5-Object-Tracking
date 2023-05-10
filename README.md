# YOLOv5 Object Tracking

This program uses the YOLOv5 deep learning model to perform real-time object detection and tracking. It allows you to select a YOLOv5 model and track objects either from a webcam or a video file.

## Requirements

- Python 3.6+
- OpenCV
- PyTorch
- torchvision

## Installation

1. Clone the repository:

git clone https://github.com/CodeThat/yolov5-object-tracking.git

2. Install the required Python packages:

  {pip install -r requirements.txt}

## Usage

1. Run the program:

  python main.py

2. Select a YOLOv5 model from the dropdown menu.

3. Choose the video source. You can either use the webcam or provide a path to a video file.

4. Click the "Track Objects" button to start the object tracking.

5. The program will display the video stream with bounding boxes around the tracked objects. Press 'q' to stop the tracking.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
