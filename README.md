# Face Recognition System

## 📌 Overview

The **Face Recognition System** is a computer vision project that detects and recognizes human faces using machine learning and image processing techniques. The system captures images from a camera, extracts facial features, and compares them with stored data to identify individuals.

This project demonstrates the application of **Artificial Intelligence, Computer Vision, and Python programming** for real-time face detection and recognition.

---

## 🚀 Features

* Real-time face detection using webcam
* Face recognition using trained dataset
* Automatic labeling of recognized faces
* Unknown face detection
* Dataset creation for new users
* Simple and efficient implementation

---

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* Machine Learning algorithms
* Haar Cascade / Deep Learning based detection

---

## 📂 Project Structure

```
Face-Recognition-System/
│
├── dataset/               # Stored images of known faces
├── trainer/               # Trained model files
├── face_dataset.py        # Script to capture face dataset
├── face_trainer.py        # Script to train recognition model
├── face_recognition.py    # Main script for face recognition
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository

```
git clone https://github.com/yourusername/Face-Recognition-System.git
```

2. Navigate to the project directory

```
cd Face-Recognition-System
```

3. Install required libraries

```
pip install opencv-python
pip install numpy
```

---

## ▶️ Usage

### Step 1: Capture Face Dataset

Run the following script to collect face images.

```
python face_dataset.py
```

### Step 2: Train the Model

Train the recognition model using the collected dataset.

```
python face_trainer.py
```

### Step 3: Run Face Recognition

Start the real-time face recognition system.

```
python face_recognition.py
```

---

## 🧠 How It Works

1. The camera captures real-time video frames.
2. Face detection algorithm identifies faces in each frame.
3. Extracted facial features are compared with the trained dataset.
4. If a match is found, the person's name is displayed; otherwise it shows **Unknown**.

---

## 📸 Example Output

* Detects faces in live video
* Displays bounding box around face
* Shows person's name if recognized

---

## 🔮 Future Improvements

* Add deep learning models like FaceNet or Dlib
* Improve recognition accuracy
* Integrate with attendance systems
* Add database storage

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

⭐ If you found this project useful, please give it a star on GitHub!
