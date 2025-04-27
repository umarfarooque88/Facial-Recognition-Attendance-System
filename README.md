# Facial Recognition Attendance System

This is a facial recognition-based attendance system built using Python and the `face_recognition` library. The system captures video input from a webcam, detects faces, matches them against known images, and logs attendance for recognized individuals.

## Features:
- Real-time facial recognition using a webcam.
- Matches detected faces against known images.
- Logs attendance in a CSV file, including time and date.
- Detects multiple faces in a frame.
- Supports custom images for recognition (e.g., Elon Musk, Jeff Bezos, Mark Zuckerberg, Ratan Tata, Umar).

## Technologies Used:
- **Python**: The programming language used for building the system.
- **OpenCV**: Used for handling video input and frame processing.
- **face_recognition**: Used for facial recognition tasks such as face encoding and comparison.
- **CSV**: For storing the attendance logs in a CSV format.

## Installation:
### Prerequisites:
- Python 3.6+ installed.
- Webcam for capturing video.
- The following Python libraries:
    - `face_recognition`
    - `opencv-python`
    - `numpy`
    - `datetime`

### Steps to run:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/umarfarooque88/facial-recognition-attendance.git
