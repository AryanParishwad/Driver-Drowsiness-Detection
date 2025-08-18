# Real-Time Driver Drowsiness Detection

![Project Demo GIF](assets/drowsiness-detection.gif)

This project is a real-time computer vision system designed to enhance road safety by detecting driver drowsiness and issuing an alert. It utilizes a hybrid deep learning model to analyze a live video feed from a webcam.

**This project is the basis for my published research paper in the *Indian Journal of Technical Education*.**

## 🚀 Key Features
- **Real-Time Detection:** Processes video streams at **18-22 FPS** to provide immediate feedback.
- **High Accuracy:** Achieved **95.4% accuracy** on the NTHU Driver Drowsiness Detection dataset.
- **Advanced Model:** Employs a hybrid architecture combining a **MobileNetV2 CNN** for efficient spatial feature extraction and a **GRU** to analyze temporal patterns in the video sequence.
- **False Positive Reduction:** Implements temporal smoothing to ensure alerts are only triggered for sustained periods of drowsiness, not quick glances.

## 🛠️ Tech Stack
- Python
- TensorFlow & Keras
- OpenCV
- Pandas & NumPy

## 🔧 Setup and Usage
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AryanParishwad/Driver-Drowsiness-Detection.git](https://github.com/AryanParishwad/Driver-Drowsiness-Detection.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Driver-Drowsiness-Detection
    ```
3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the application:**
    ```bash
    python main.py
    ```
