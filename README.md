# 🧍‍♂️ Real-Time Human Pose Estimation

**Pose estimation** refers to a computer vision technique that identifies and tracks key human joints (like elbows, knees, etc.) in real time from images or video. This project demonstrates human body pose estimation using [PoseNet](https://github.com/tensorflow/tfjs-models/tree/master/posenet) — a model capable of detecting either **single-person** or **multi-person** poses via webcam.

> ⚠️ _Note: Pose Estimation does not identify the individual. It only tracks human posture and movements using keypoints._

---

## 🎯 Project Objective

This project showcases real-time human pose estimation using the webcam feed. It demonstrates:

- ✅ Single-Person Pose Estimation  
- ✅ Multi-Person Pose Estimation  
- ✅ Hand Pose Detection

It aims to provide a practical understanding of how PoseNet works and how it can be integrated into real-time applications.

---

## 📸 Features

### 🔹 Single-Person Pose Estimation
- Fast and efficient.
- Best for scenarios where only one person is present.
- May give incorrect keypoints when multiple people appear in the frame.

### 🔹 Multi-Person Pose Estimation
- Capable of detecting multiple individuals.
- More computationally intensive.
- Suitable for crowded environments or group activities.

---

## 💡 Interactive Showcase

🚀 Experience the interactive Human Pose Estimation demo live:

🔗 **Live Website**:  
[https://humanbody-pose-estimation.netlify.app/](https://humanbody-pose-estimation.netlify.app/)

📁 **Source Code**:  
[https://github.com/sahemant12/HumanBody-Pose-Estimation](https://github.com/sahemant12/HumanBody-Pose-Estimation)

🎨 **Figma Prototype**:  
[https://www.figma.com/design/Fc2UKWRAtuhF1c7ipBuj14/Human-Pose-Design-Website?node-id=0-1&p=f&t=MrsaSWbO8eGEksHx-0](https://www.figma.com/design/Fc2UKWRAtuhF1c7ipBuj14/Human-Pose-Design-Website?node-id=0-1&p=f&t=MrsaSWbO8eGEksHx-0)

![Human Pose Estimation Homepage](/images/readmeImg.png)

---

## 🛠️ How to Run Locally

### 🔧 Prerequisites
- A modern web browser (Chrome, Edge, Firefox)
- Code editor like **VS Code** (optional but recommended)

---

### 🧩 Installation & Setup

 1. Clone the repository:
`git clone https://github.com/sahemant12/HumanBody-Pose-Estimation.git`

2. Navigate to the project folder
`cd HumanBody-Pose-Estimation`

3. Open the project in Visual Studio Code or any code editor of your choice.

4. Navigate to `index.html`

5. Launch with Live Server:
    - Right-click on the `index.html` file and select `"Open with Live Server"` (make sure the Live Server extension is installed in VS Code).
    - This will open the project in your browser with full webcam support.

6. Use Pose Detection Features:
    - Navigate to the `M-Pose Detection` tab for real-time multi-person pose detection.
    - Navigate to the `H-Pose Detection` tab for hand pose detection using your webcam.
