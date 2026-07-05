# 🏋️ AI Gym Trainer

> **A production-ready Computer Vision application that leverages MediaPipe Pose Estimation to analyze exercise form, count repetitions, and provide real-time posture feedback through live webcam inference.**

![Python](https://img.shields.io/badge/Python-3.12-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Pose%20Estimation-orange)
![Computer Vision](https://img.shields.io/badge/AI-Computer%20Vision-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📖 Overview

**AI Gym Trainer** is a real-time AI-powered fitness assistant that analyzes body posture using **MediaPipe Pose Estimation** and **OpenCV**. The system detects **33 human body landmarks**, computes joint angles, tracks exercise phases, counts repetitions, and provides instant visual feedback to help users maintain proper exercise form.

The project demonstrates the practical application of **Computer Vision**, **Human Pose Estimation**, **Joint Angle Analysis**, and **Real-Time AI Inference** for intelligent fitness coaching.

---

# ✨ Features

- 🎥 Real-time webcam pose estimation
- 🦴 Detection of 33 human body landmarks
- 📐 Joint angle calculation
- 🔄 Automatic repetition counting
- 🏋️ Exercise phase detection
- ✅ Real-time posture correction
- 📊 Live workout statistics
- ⚡ Low-latency inference
- 🖥️ Skeleton visualization overlay
- 📈 Modular and scalable architecture

---

# 📸 Demo

> **Demo GIF**

```
assets/demo/demo.gif
```

---

# 🏗 System Architecture

```text
                    Webcam
                       │
                       ▼
               Video Capture
                       │
                       ▼
         MediaPipe Pose Estimation
                       │
                       ▼
        33 Body Landmark Detection
                       │
                       ▼
          Joint Angle Calculation
                       │
                       ▼
      Exercise State Classification
          (Up / Down / Neutral)
                       │
                       ▼
          Repetition Counter Logic
                       │
                       ▼
         Live Visual Feedback Overlay
                       │
                       ▼
          Workout Statistics Dashboard
```

---

# 📂 Repository Structure

```text
ai-gym-trainer/
│
├── src/
│   ├── app/
│   ├── pose_estimation/
│   ├── exercise_detection/
│   ├── angle_calculation/
│   ├── repetition_counter/
│   ├── visualization/
│   ├── utils/
│   └── main.py
│
├── assets/
│   ├── demo/
│   ├── screenshots/
│   └── architecture/
│
├── configs/
│
├── datasets/
│
├── docs/
│   ├── Architecture.md
│   ├── Learnings.md
│   ├── Challenges.md
│   ├── Deployment.md
│   └── Future_Work.md
│
├── notebooks/
│
├── scripts/
│
├── tests/
│
├── .github/
│   └── workflows/
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# ⚙️ Technology Stack

| Category | Technologies |
|-----------|--------------|
| Programming Language | Python |
| Computer Vision | OpenCV |
| Pose Estimation | MediaPipe |
| Mathematics | Joint Angle Analysis |
| Visualization | OpenCV Drawing API |
| Development | VS Code |
| Version Control | Git & GitHub |

---

# 🧠 AI Pipeline

```text
Live Webcam Feed
        │
        ▼
Pose Detection
        │
        ▼
33 Landmark Extraction
        │
        ▼
Joint Angle Computation
        │
        ▼
Exercise Phase Detection
        │
        ▼
Repetition Counting
        │
        ▼
Posture Evaluation
        │
        ▼
Real-Time Feedback
```

---

# 🏋️ Supported Exercises

- Squats
- Push-ups
- Bicep Curls

> The modular design allows new exercises to be added with minimal code changes.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/ai-gym-trainer.git
```

Navigate into the project

```bash
cd ai-gym-trainer
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

Start the application

```bash
python src/main.py
```

The application will

- Open your webcam
- Detect your body pose
- Track body landmarks
- Analyze exercise form
- Count repetitions
- Display live feedback

---

# 📊 Performance Highlights

- Real-time pose estimation
- Lightweight inference
- Smooth webcam processing
- Modular exercise detection
- Easy extension for additional workouts

---

# 📚 Learning Outcomes

This project provided hands-on experience with:

- Human Pose Estimation
- Computer Vision pipelines
- MediaPipe Pose API
- Geometric joint-angle calculations
- State-machine based repetition counting
- Real-time AI inference
- Performance optimization
- Modular software architecture
- Production-ready AI application development

---

# ⚠️ Challenges Solved

- Handling pose variations
- Reducing noisy landmark detections
- Designing robust angle thresholds
- Improving repetition counting accuracy
- Optimizing webcam frame processing
- Supporting multiple exercise types
- Providing responsive real-time feedback

---

# 🛣 Roadmap

- [x] Pose Estimation
- [x] Joint Angle Analysis
- [x] Repetition Counter
- [x] Real-Time Feedback
- [x] Multiple Exercise Support
- [ ] Workout History
- [ ] Performance Analytics Dashboard
- [ ] AI Personal Trainer Recommendations
- [ ] Voice Feedback
- [ ] Exercise Customization
- [ ] Mobile Deployment
- [ ] Docker Support

---

# 🤝 Contributing

Contributions are welcome.

Feel free to fork the repository, create a feature branch, and submit a pull request to improve the project.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Abhishek Ojha**

AI • Machine Learning • Computer Vision • Human Pose Estimation

⭐ If you found this project helpful, consider giving it a star on GitHub.
