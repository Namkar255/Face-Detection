# Face Detection using OpenCV

A real-time face detection system built using **Python** and **OpenCV**. The project uses the **Haar Cascade Classifier** to detect human faces from a webcam feed and highlights detected faces with bounding boxes.

## Features

- Real-time webcam-based face detection
- Haar Cascade Classifier for face detection
- Bounding box visualization around detected faces
- Lightweight and easy to run
- Works with live video streams

## Technologies Used

- Python
- OpenCV
- NumPy
- Haar Cascade Classifier

## Project Structure

```text
Face-Detection/
│
├── Face Detection.ipynb
├── haarcascade_frontalface_default.xml
├── README.md
└── requirements.txt
```

## Usage

1. Ensure `haarcascade_frontalface_default.xml` is present in the project directory.
2. Open the Jupyter Notebook:

```bash
jupyter notebook
```

3. Run all cells in `Face Detection.ipynb`.

4. A webcam window will open and detect faces in real time.

5. Press **q** to exit the application.

## How It Works

1. Captures live video from the webcam.
2. Converts each frame to grayscale.
3. Uses the Haar Cascade Classifier to detect faces.
4. Draws a bounding rectangle around detected faces.
5. Displays the processed video stream in real time.

## Applications

- Attendance Systems
- Surveillance Systems
- Human-Computer Interaction
- Face Recognition Preprocessing
- Smart Security Systems

## Output

The system detects faces and displays a bounding box around each detected face in the webcam feed.

## Future Improvements

- Face Recognition
- Multiple Face Tracking
- Emotion Detection
- Mask Detection
- Attendance Management Integration

## Author

**Namkar Jindal**

## License

This project is licensed under the MIT License.
