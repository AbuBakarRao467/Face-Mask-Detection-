# Live Face Detection Using OpenCV and Haar Cascade

##  Project Description
This project implements **real-time face detection using a webcam** with Python and OpenCV. It uses the Haar Cascade Classifier to detect human faces from live video frames captured by the webcam and highlights detected faces with rectangular bounding boxes.

The system processes the webcam feed continuously, demonstrating a basic computer vision application for live face detection.

## Objectives
- Detect human faces from a live webcam feed.
- Apply the Haar Cascade Classifier for face detection.
- Process video frames in real time using OpenCV.
- Display detected faces with bounding boxes.
- Explore the practical application of computer vision.

##  Technologies Used
- Python
- OpenCV
- Haar Cascade Classifier
- Webcam / Live Video Input

##  How It Works
1. Initialize the webcam to capture live video.
2. Load the pre-trained Haar Cascade face detection model.
3. Read video frames continuously from the webcam.
4. Convert each frame to grayscale for face detection.
5. Detect faces using the Haar Cascade Classifier.
6. Draw rectangular bounding boxes around detected faces.
7. Display the processed video feed in real time.

##  How to Run
1. Install Python on your computer.
2. Install OpenCV:

   ```bash
   pip install opencv-python
   ```

3. Make sure your webcam is connected and accessible.
4. Run the Python script:

   ```bash
   python face_detection.py
   ```

   Replace `face_detection.py` with the actual name of your Python file.

5. A window should display the live webcam feed with rectangles around detected faces.
6. Press the **`q` key** to exit, if supported by the script.

##  Key Features
- Real-time face detection using a webcam.
- Haar Cascade-based face detection.
- Live video frame processing.
- Visual highlighting of detected faces.

##  Limitations
- Detection accuracy may vary with lighting, face angle, distance, and image quality.
- Haar Cascade detects faces but does not identify the person.
- Performance depends on the computer's processing capability and webcam quality.

##  Future Improvements
- Improve detection under different lighting conditions.
- Compare Haar Cascade with modern face detection models.
- Add face counting or detection statistics.
- Explore integration with other computer vision applications.

##  Privacy Note
This project is designed for face detection, not identity recognition. Webcam access should be used with the user's knowledge and permission.

## 📚 Disclaimer
This project was developed for educational purposes to explore real-time computer vision and face detection using OpenCV.
