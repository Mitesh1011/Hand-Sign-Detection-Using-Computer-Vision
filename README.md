# Hand Sign Detection System

## Overview
This project is a real-time Hand Sign Detection System developed using Python, OpenCV, and CVZone. The system detects and classifies hand gestures representing the letters **A, B, and C** using a webcam feed and a trained deep learning model.

## Features
- Real-time hand detection
- Detects hand signs: A, B, and C
- Dataset collection using a webcam
- Deep learning classification with Keras
- Live prediction display

## Technologies Used
- Python
- OpenCV
- CVZone
- NumPy
- TensorFlow / Keras

## Project Structure

```bash
├── Data/
│   ├── A/
│   ├── B/
│   └── C/
│
├── Model/
│   ├── keras_model.h5
│   └── labels.txt
│
├── dataCollection.py
├── test.py
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/hand-sign-detection.git
cd hand-sign-detection
```

Install dependencies:

```bash
pip install opencv-python cvzone numpy tensorflow
```

## Dataset Collection

Run the following command to collect hand gesture images:

```bash
python dataCollection.py
```

### Controls
- Press **S** to save images into the dataset folder.

## Run the Project

Execute the test script:

```bash
python test.py
```

The system will:
- Open webcam feed
- Detect hand gestures
- Predict A, B, or C in real time

## Model Files

- `keras_model.h5` → Trained classification model
- `labels.txt` → Labels for prediction classes

## Future Improvements
- Add more hand signs
- Improve prediction accuracy
- Convert sign language to text
- Deploy on embedded systems

## Author
Developed by Mitesh Salvi

## License
This project is for educational purposes.
