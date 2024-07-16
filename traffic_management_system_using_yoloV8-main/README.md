# Traffic Object Detection and PDF Generation

This project combines real-time traffic object detection using YOLOv8 and PDF generation from text input using Flask.

## Features

### Real-time Object Detection

- Utilizes YOLOv8 for detecting vehicles (cars, trucks, buses, motorbikes) in a video feed or video file.
- Tracks detected objects using SORT (Simple Online and Realtime Tracking) algorithm.
- Counts and records the number of vehicles crossing a specified line in the video frame.
- Displays real-time count of vehicles detected on the video stream.

## Setup and Usage

### Prerequisites

- Python 3.x
- OpenCV (cv2)
- cvzone
- Sort (Simple Online and Realtime Tracking)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_name>
2. Install dependencies:
3. Running the application
   ```bash
    python tf.py

##Usage
Real-time Object Detection:

- Open the video feed or upload a video file (video3.mp4).
- Detects and tracks vehicles specified in classNames.
- Counts vehicles crossing the specified line (limits) and logs into traffic_jam.txt.

Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.
