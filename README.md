# 👆 Hand Index Fingertip Detection using OpenCV & MediaPipe

## 📖 Overview

This project is a real-time computer vision application developed using **Python**, **OpenCV**, and **MediaPipe**. It detects a user's hand through a webcam and continuously tracks the **index fingertip** with high accuracy. The application visualizes all 21 hand landmarks, highlights the index fingertip with a red circle, and displays its coordinates on the screen in real time.

This project serves as an excellent introduction to hand tracking and gesture recognition. It demonstrates how computer vision can be used to interact with the digital world without requiring any physical controller or touch input. It also acts as the foundation for more advanced applications such as virtual drawing, gesture-controlled interfaces, and touchless human-computer interaction.

---

## ✨ Features

- 📹 Real-time webcam input
- ✋ Detects a single hand using MediaPipe Hands
- 👆 Tracks the index fingertip (Landmark 8)
- 🔴 Highlights the fingertip with a red circle
- 📍 Displays fingertip coordinates in real time
- 🟢 Draws all 21 hand landmarks and their connections
- ⚡ Smooth and accurate hand tracking
- 💻 Lightweight and easy to run

---

## 🛠️ Technologies Used

- Python 3
- OpenCV
- MediaPipe
- NumPy

---

## 📂 Project Structure

```
detection_of_hand_indexFingerTip/
│
├── main.py
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/RAGINICHAKRAVARTY-23/First_OpenCV_projects.git
```

### 2. Move into the Project Folder

```bash
cd First_OpenCV_projects/detection_of_hand_indexFingerTip
```

### 3. Install Dependencies

```bash
pip install opencv-python mediapipe numpy
```

### 4. Run the Program

```bash
python main.py
```

---

## 🚀 How It Works

1. The webcam is opened using OpenCV.
2. Each video frame is captured continuously.
3. The frame is converted from BGR to RGB because MediaPipe processes RGB images.
4. MediaPipe detects the user's hand and estimates all 21 landmarks.
5. The application extracts Landmark 8, which represents the tip of the index finger.
6. The normalized landmark coordinates are converted into pixel coordinates.
7. A red circle is drawn on the fingertip.
8. The fingertip coordinates are displayed on the screen while the hand landmarks are visualized.

---

## 📸 Output

When the application is running, it displays:

- Live webcam feed
- Hand landmark visualization
- Highlighted index fingertip
- Real-time X and Y coordinates

---

## 🎯 Applications

- Gesture Recognition
- Human-Computer Interaction
- Touchless Interfaces
- Virtual Mouse
- Air Drawing Applications
- Finger Tracking
- AI Vision Projects

---

## 🔮 Future Improvements

- Multi-hand tracking
- Finger counting
- Gesture recognition
- Click detection
- Virtual mouse control
- Volume and brightness control using gestures

---
# 🎨 Virtual Air Canvas using OpenCV & MediaPipe

## 📖 Overview

Virtual Air Canvas is a real-time computer vision application that enables users to draw in the air using only their index finger. Instead of using a physical mouse, stylus, or touchscreen, the application tracks the movement of the user's hand through a webcam and converts finger movements into digital drawings.

The project is built using **Python**, **OpenCV**, **MediaPipe**, and **NumPy**. It detects the user's hand, recognizes simple finger gestures, and provides an interactive drawing experience with multiple brush colors, an eraser, and a clear canvas option. The application demonstrates the practical use of hand tracking and gesture recognition in creating touchless digital interfaces.

---

## ✨ Features

- 🎥 Real-time webcam-based drawing
- ✋ Accurate hand tracking using MediaPipe
- 👆 Draw using only the index finger
- 🎨 Four brush colors
  - 🔴 Red
  - 🩷 Pink
  - 🔵 Blue
  - 🟢 Green
- 🧽 Eraser tool
- 🗑️ Clear canvas option
- ✨ Smooth drawing using point averaging
- 📍 Live fingertip tracking
- 🖥️ Hand landmark visualization

---

## 🛠️ Technologies Used

- Python 3
- OpenCV
- MediaPipe
- NumPy

---

## 📂 Project Structure

```
Air_Canvas/
│
├── main.py
├── red.png
├── pink.png
├── blue.png
├── green.png
├── eraser.png
├── dustbin.png
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/RAGINICHAKRAVARTY-23/First_OpenCV_projects.git
```

### 2. Move into the Project Folder

```bash
cd First_OpenCV_projects/Air_Canvas
```

### 3. Install Required Libraries

```bash
pip install opencv-python mediapipe numpy
```

### 4. Make sure the following icons are present

- red.png
- pink.png
- blue.png
- green.png
- eraser.png
- dustbin.png

### 5. Run the application

```bash
python main.py
```

---

## 🚀 How It Works

1. The webcam captures live video frames.
2. MediaPipe detects the user's hand and estimates all 21 hand landmarks.
3. The application continuously tracks the index fingertip.
4. If only the index finger is raised, the application enters **Drawing Mode**.
5. Moving the finger creates lines on a virtual canvas.
6. Touching the toolbar at the top selects different brush colors.
7. Selecting the eraser changes the brush into an eraser.
8. Selecting the dustbin icon instantly clears the entire canvas.
9. The virtual canvas is combined with the webcam feed to create a seamless drawing experience.

---

## 🎨 Available Tools

| Tool | Function |
|------|----------|
| 🔴 Red | Draw with a red brush |
| 🩷 Pink | Draw with a pink brush |
| 🔵 Blue | Draw with a blue brush |
| 🟢 Green | Draw with a green brush |
| 🧽 Eraser | Remove existing drawings |
| 🗑️ Dustbin | Clear the entire canvas |

---

## 🎯 Applications

- Virtual Whiteboard
- Digital Sketching
- Gesture-Based Interfaces
- Educational Demonstrations
- Interactive Learning
- Human-Computer Interaction
- Computer Vision Research

---

## 🔮 Future Improvements

- Adjustable brush sizes
- Undo and Redo functionality
- Save drawings as images
- Shape drawing mode
- Text writing mode
- Multiple hand support
- Gesture shortcuts
- Color palette expansion

---

# 🎨 Virtual Air Canvas using OpenCV & MediaPipe

## 📖 Overview

Virtual Air Canvas is a real-time computer vision application that enables users to draw in the air using only their index finger. Instead of using a physical mouse, stylus, or touchscreen, the application tracks the movement of the user's hand through a webcam and converts finger movements into digital drawings.

The project is built using **Python**, **OpenCV**, **MediaPipe**, and **NumPy**. It detects the user's hand, recognizes simple finger gestures, and provides an interactive drawing experience with multiple brush colors, an eraser, and a clear canvas option. The application demonstrates the practical use of hand tracking and gesture recognition in creating touchless digital interfaces.

---

## ✨ Features

- 🎥 Real-time webcam-based drawing
- ✋ Accurate hand tracking using MediaPipe
- 👆 Draw using only the index finger
- 🎨 Four brush colors
  - 🔴 Red
  - 🩷 Pink
  - 🔵 Blue
  - 🟢 Green
- 🧽 Eraser tool
- 🗑️ Clear canvas option
- ✨ Smooth drawing using point averaging
- 📍 Live fingertip tracking
- 🖥️ Hand landmark visualization

---

## 🛠️ Technologies Used

- Python 3
- OpenCV
- MediaPipe
- NumPy

---

## 📂 Project Structure

```
Air_Canvas/
│
├── main.py
├── red.png
├── pink.png
├── blue.png
├── green.png
├── eraser.png
├── dustbin.png
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/RAGINICHAKRAVARTY-23/First_OpenCV_projects.git
```

### 2. Move into the Project Folder

```bash
cd First_OpenCV_projects/Air_Canvas
```

### 3. Install Required Libraries

```bash
pip install opencv-python mediapipe numpy
```

### 4. Make sure the following icons are present

- red.png
- pink.png
- blue.png
- green.png
- eraser.png
- dustbin.png

### 5. Run the application

```bash
python main.py
```

---

## 🚀 How It Works

1. The webcam captures live video frames.
2. MediaPipe detects the user's hand and estimates all 21 hand landmarks.
3. The application continuously tracks the index fingertip.
4. If only the index finger is raised, the application enters **Drawing Mode**.
5. Moving the finger creates lines on a virtual canvas.
6. Touching the toolbar at the top selects different brush colors.
7. Selecting the eraser changes the brush into an eraser.
8. Selecting the dustbin icon instantly clears the entire canvas.
9. The virtual canvas is combined with the webcam feed to create a seamless drawing experience.

---

## 🎨 Available Tools

| Tool | Function |
|------|----------|
| 🔴 Red | Draw with a red brush |
| 🩷 Pink | Draw with a pink brush |
| 🔵 Blue | Draw with a blue brush |
| 🟢 Green | Draw with a green brush |
| 🧽 Eraser | Remove existing drawings |
| 🗑️ Dustbin | Clear the entire canvas |

---

## 🎯 Applications

- Virtual Whiteboard
- Digital Sketching
- Gesture-Based Interfaces
- Educational Demonstrations
- Interactive Learning
- Human-Computer Interaction
- Computer Vision Research

---

## 🔮 Future Improvements

- Adjustable brush sizes
- Undo and Redo functionality
- Save drawings as images
- Shape drawing mode
- Text writing mode
- Multiple hand support
- Gesture shortcuts
- Color palette expansion

---

# 🎨 Virtual Air Canvas using OpenCV & MediaPipe

## 📖 Overview

Virtual Air Canvas is a real-time computer vision application that enables users to draw in the air using only their index finger. Instead of using a physical mouse, stylus, or touchscreen, the application tracks the movement of the user's hand through a webcam and converts finger movements into digital drawings.

The project is built using **Python**, **OpenCV**, **MediaPipe**, and **NumPy**. It detects the user's hand, recognizes simple finger gestures, and provides an interactive drawing experience with multiple brush colors, an eraser, and a clear canvas option. The application demonstrates the practical use of hand tracking and gesture recognition in creating touchless digital interfaces.

---

## ✨ Features

- 🎥 Real-time webcam-based drawing
- ✋ Accurate hand tracking using MediaPipe
- 👆 Draw using only the index finger
- 🎨 Four brush colors
  - 🔴 Red
  - 🩷 Pink
  - 🔵 Blue
  - 🟢 Green
- 🧽 Eraser tool
- 🗑️ Clear canvas option
- ✨ Smooth drawing using point averaging
- 📍 Live fingertip tracking
- 🖥️ Hand landmark visualization

---

## 🛠️ Technologies Used

- Python 3
- OpenCV
- MediaPipe
- NumPy

---

## 📂 Project Structure

```
Air_Canvas/
│
├── main.py
├── red.png
├── pink.png
├── blue.png
├── green.png
├── eraser.png
├── dustbin.png
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/RAGINICHAKRAVARTY-23/First_OpenCV_projects.git
```

### 2. Move into the Project Folder

```bash
cd First_OpenCV_projects/Air_Canvas
```

### 3. Install Required Libraries

```bash
pip install opencv-python mediapipe numpy
```

### 4. Make sure the following icons are present

- red.png
- pink.png
- blue.png
- green.png
- eraser.png
- dustbin.png

### 5. Run the application

```bash
python main.py
```

---

## 🚀 How It Works

1. The webcam captures live video frames.
2. MediaPipe detects the user's hand and estimates all 21 hand landmarks.
3. The application continuously tracks the index fingertip.
4. If only the index finger is raised, the application enters **Drawing Mode**.
5. Moving the finger creates lines on a virtual canvas.
6. Touching the toolbar at the top selects different brush colors.
7. Selecting the eraser changes the brush into an eraser.
8. Selecting the dustbin icon instantly clears the entire canvas.
9. The virtual canvas is combined with the webcam feed to create a seamless drawing experience.

---

## 🎨 Available Tools

| Tool | Function |
|------|----------|
| 🔴 Red | Draw with a red brush |
| 🩷 Pink | Draw with a pink brush |
| 🔵 Blue | Draw with a blue brush |
| 🟢 Green | Draw with a green brush |
| 🧽 Eraser | Remove existing drawings |
| 🗑️ Dustbin | Clear the entire canvas |

---

## 🎯 Applications

- Virtual Whiteboard
- Digital Sketching
- Gesture-Based Interfaces
- Educational Demonstrations
- Interactive Learning
- Human-Computer Interaction
- Computer Vision Research

---

## 🔮 Future Improvements

- Adjustable brush sizes
- Undo and Redo functionality
- Save drawings as images
- Shape drawing mode
- Text writing mode
- Multiple hand support
- Gesture shortcuts
- Color palette expansion

---
