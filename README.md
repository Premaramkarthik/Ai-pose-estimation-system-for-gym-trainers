
# Real-time Bicep Curl Counter

## Overview
This Python project utilizes computer vision techniques to create a real-time system for counting bicep curls using a webcam feed. By detecting the pose of a person performing bicep curls, the program automatically tracks repetitions and provides real-time feedback on the exercise performance.

## Features
- **Pose Detection:** Utilizes the MediaPipe library to detect key landmarks on the human body, including shoulders, elbows, and wrists.
  
- **Angle Calculation:** Computes the angle between the shoulder, elbow, and wrist joints to analyze the bicep curl motion.
  
- **Repetition Counting:** Tracks the number of completed bicep curl repetitions based on angle changes and updates a counter in real-time.
  
- **Graphical User Interface (GUI):** Renders a user-friendly interface overlaid on the webcam feed, displaying the current repetition count and curling stage.
  
- **Fitness Monitoring:** Enables users to monitor their bicep curl performance and progress without manual counting.
  
- **Training Assistance:** Provides feedback on proper form and technique during bicep curl exercises, aiding in training and muscle development.

## Installation
1. Clone the repository:
   ```
   git clone [https://github.com/your_username/bicep_curl_counter.git](https://github.com/Premaramkarthik/Ai-pose-estimation-system-for-gym-trainers)
   ```
2. Install dependencies:
   ```
   pip install mediapipe opencv-python
   ```

## Usage
1. Run the script:
   ```
   python bicep_curl_counter.py
   ```
2. Ensure that your webcam is enabled and properly positioned to capture your movements.
3. Perform bicep curls within the camera frame, and observe the real-time feedback on the GUI.
4. Press 'q' to exit the program when finished.

## Dependencies
- [MediaPipe](https://mediapipe.dev/): A framework for building multimodal applied machine learning pipelines.
  
- [OpenCV](https://opencv.org/): An open-source computer vision and machine learning software library.

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or feature requests, please open an issue or create a pull request.


## Acknowledgments
Special thanks to the developers of MediaPipe and OpenCV for providing powerful tools for computer vision applications.

---

Feel free to customize the README file with additional information, such as project setup instructions, troubleshooting tips, or acknowledgments to contributors and collaborators.
