# Hello, I'm Alvaro 👋

Computer Science student focused on **Software Engineering and Artificial Intelligence**.

I like projects where software meets real constraints: hardware, latency, noisy data. I choose technologies based on the problem, not the other way around.

[LinkedIn](https://www.linkedin.com/in/alvaro-danko) • [alvarodanko032@gmail.com](mailto:alvarodanko032@gmail.com)

## Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | Python • C++ • Java • JavaScript • SQL |
| **AI & Data** | OpenCV • PyTorch • TensorFlow • scikit-learn • Pandas • NumPy • spaCy • LLMs • Matplotlib |
| **Embedded & Mobile** | ESP32 (Arduino framework) • Android (Kotlin, CameraX, Chaquopy) • WebSocket • Serial |
| **Backend & Engineering** | FastAPI • Git • Modular Architecture • OOP • pytest |
| **Frontend** | React • HTML • CSS |
| **Currently learning** | Docker • AI Agents |

## Featured Projects

### 🚗 [ESP32 Self-Driving Car](https://github.com/allvaret/esp32-self-driving-car)

Small autonomous car for obstacle avoidance, integrating computer vision, embedded firmware and a mobile app. An Android phone runs a classical vision pipeline (HSV floor segmentation via histogram back-projection, optical flow, edges) at ~18 ms/frame on a Galaxy S9 and decides between free / uncertain / obstacle with hysteresis. An ESP32 drives the motors and runs a safety reflex, using an ultrasonic sensor on a servo to cover what vision cannot, such as a wall the same color as the floor. Phone and ESP32 talk over WebSocket. Vision was validated offline on recorded videos before the car existed, and the project design was partly inspired by a study of Tesla's and Waymo's perception approaches.

**Python • OpenCV • C++ (ESP32) • Kotlin • Android (Chaquopy) • WebSocket**

### 📄 [Financial Report Processing Pipeline](https://github.com/allvaret/Document_Parsing_Pipeline)

Modular pipeline for reconstructing financial reports, extracting relevant information and preparing structured data for LLMs.

**Python • PyMuPDF • spaCy • LLMs • FastAPI**

### 🧠 Transfer Learning & ML Adaptations

Neural network projects involving transfer learning, custom architectures, dataset preparation and model evaluation.  
#### My favorite:  
[Image-based recommendation system using visual embeddings](https://github.com/allvaret/embeddings_similarity_recommendation)

**Python • TensorFlow • PyTorch • NumPy • Matplotlib • Pandas • Pillow • OpenCV**

### 🎮 [2D Educational Game](https://github.com/allvaret/CleanCity)

Complete Java game exploring object-oriented programming, modular architecture, game loops, physics and asset management.

**Java • LibGDX • LWJGL**
