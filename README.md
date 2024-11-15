## Hand Gesture Recognition with Deep Learning

This repository implements a hand gesture recognition model using deep learning techniques. The model leverages Long Short-Term Memory (LSTM) networks to classify hand gestures based on sequences of keypoint data captured from a webcam using MediaPipe.

**Features:**

- Real-time hand gesture recognition using webcam.
- Multi-class classification with various gesture types.
- LSTM architecture for capturing temporal information in gestures.
- Support for data collection and preprocessing (commented out).
- Evaluation metrics and visualizations for model performance analysis.
- Hyperparameter tuning for optimizing model accuracy.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- MediaPipe (`pip install mediapipe`)
- TensorFlow (`pip install tensorflow`)
- Matplotlib (`pip install matplotlib`)
- (Optional) Scikit-learn (`pip install scikit-learn`)

### Running the model

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/hand-gesture-recognition.git
```

2. Navigate to the project directory:

```bash
cd hand-gesture-recognition
```

3. (Optional) Uncomment the data collection sections in the code (`main.py`) to collect data for training.
4. Run the script:

```bash
python main.py
```

This will start the webcam stream and display the detected hand landmarks. You can perform different gestures in front of the camera to see the model's prediction.

**(Note:** The provided code includes data collection functionality, but it's commented out. To use it, you'll need to define the gesture set and uncomment the relevant sections.)


## Contributing

We welcome contributions to this project! Please feel free to fork the repository, make changes, and submit pull requests. 

## License

This project is licensed under the MIT License. See the LICENSE file for details.
