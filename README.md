# Driver Drowsiness Monitor

Driver Drowsiness Monitor is a Python-based real-time system that detects when a driver is drowsy using computer vision. The program uses a webcam to monitor eye closure and yawning patterns and alerts the driver with an audio warning before accidents can happen. This lightweight system is easy to run on any computer without requiring a GPU.

## Features
- Real-time detection of eye closure and yawning
- Audio alerts to warn the driver
- Works on CPU; no special hardware required
- Simple setup and usage, ideal for learning computer vision

## Installation
1. Clone the repository:  
   `git clone https://github.com/yourusername/driver-drowsiness-monitor.git`
2. Navigate to the project folder:  
   `cd driver-drowsiness-monitor`
3. Install dependencies:  
   `pip install -r requirements.txt`

## Usage
1. Connect a webcam to your computer.  
2. Run the program:  
   `python drowsiness_monitor.py`  
3. The system will continuously monitor the driver’s eyes and alert if drowsiness is detected.  

## Dependencies
- OpenCV
- dlib
- imutils
- numpy
- playsound  
*(All can be installed via `pip install -r requirements.txt`)*

## Contributing
Contributions and improvements are welcome! You can fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.
