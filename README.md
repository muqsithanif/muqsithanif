# Muqsit Hanif

**AI & Robotics Systems Engineer** | *Bridging Machine Intelligence to Physical & Industrial Systems*

[![GitHub](https://img.shields.io/badge/GitHub-muqsithanif-181717?style=flat-square&logo=github)](https://github.com/muqsithanif)
[![Kaggle](https://img.shields.io/badge/Kaggle-muqsithanif-20BEFF?style=flat-square&logo=kaggle)](https://www.kaggle.com/muqsithanif)
[![Email](https://img.shields.io/badge/Email-muqsithanif29%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:muqsithanif29@gmail.com)

---

### Focus & Specialization
I design and deploy end-to-end intelligent systems that operate at the intersection of **Computer Vision, Real-Time Edge Inference, Robotics Perception, and Industrial Automation**. My work focuses on low-latency inference, deterministic hardware protocols, and robust edge architectures.

- **Robotics & Physical AI:** Autonomous manipulator perception, SE(3) hand-eye coordinate transformations, and smooth trajectory planning.
- **Edge Vision:** Deploying optimized perception models (ONNX, OpenVINO, TensorRT) with zero-dependency runtime environments.
- **Industrial Automation & IIoT:** Deterministic telemetry pipelines, Modbus TCP/IP, CODESYS/PLC integration, and industrial loop monitoring.
- **Applied Machine Learning:** Predictive maintenance, statistical anomaly detection on high-frequency time-series, and aerial multi-object tracking.

---

### Technical Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Robotics & Control** | 6-DoF Kinematics (FK/IK), Trajectory Planning (Quintic Polynomials), ROS 2, URDF |
| **AI / ML & Vision** | PyTorch, OpenCV, ONNX Runtime, OpenVINO, YOLO, Albumentations, scikit-learn |
| **Industrial & Protocols** | Modbus TCP, CODESYS Gateway Protocol, 4–20 mA Current Loops, MQTT, REST APIs |
| **Edge & Embedded** | Edge Deployments, UAV Perception & Tracking, ESP32 Firmware, Linux/Embedded |
| **Backend & Data Eng** | FastAPI, SQLite/MySQL, NumPy, Pandas, Docker, Git CI/CD |

---

### Featured Systems & Repositories

#### 1. Robotics Perception & Real-Time Vision
- **[visiongrasp](https://github.com/muqsithanif/visiongrasp)**  
  *Autonomous 6-DoF Robotic Pick-and-Place with RGB-D Perception*  
  End-to-end manipulator pipeline integrating pinhole camera ray de-projection, oriented grasp pose estimation, numerical inverse kinematics, and minimum-jerk quintic trajectory planning. Includes 11 automated invariant tests and 3D simulation rendering.

- **[visual-inspection-api](https://github.com/muqsithanif/visual-inspection-api)**  
  *Zero-Framework ONNX Model Serving for Industrial QA*  
  High-throughput HTTP serving engine for YOLO-family ONNX detectors. Features layout auto-detection, pure NumPy NMS from scratch, and eliminates heavy training framework dependencies in production runtime.

- **[multi-uav-perception](https://github.com/muqsithanif/multi-uav-perception)**  
  *Aerial Object Detection & Tracking Pipeline*  
  Fine-tuned vision detectors on aerial imagery (VisDrone), optimized via ONNX and OpenVINO with cross-format agreement validation, integrated into multi-target tracking benchmarks.

#### 2. Industrial Automation & Plant Emulation
- **[modbus-monitor](https://github.com/muqsithanif/modbus-monitor)**  
  *Industrial Equipment & Loop Health Monitor over Modbus TCP*  
  Engineering-unit scaling engine, 4–20 mA loop-fault detection (under-range/over-range), alarm hysteresis, and a zero-hardware plant simulator for deterministic testing.

- **[reactor-plc-trainer](https://github.com/muqsithanif/reactor-plc-trainer)**  
  *Batch Reactor Simulator with CODESYS Gateway Protocol*  
  Hardware-free industrial simulation bridge allowing real ladder logic in Machine Expert / CODESYS to control virtual batch processing plants.

#### 3. Data Science & Predictive Maintenance
- **[machine-health-monitor](https://github.com/muqsithanif/machine-health-monitor)**  
  *Early Mechanical Fault Detection on Industrial Bearings*  
  Benchmarking statistical time-series control charts against modern unsupervised ML; demonstrates EWMA providing a 9-day earlier warning horizon over Isolation Forest for developing mechanical failures.

- **[iot-telemetry-api](https://github.com/muqsithanif/iot-telemetry-api)**  
  *Idempotent Industrial Sensor Ingestion Pipeline*  
  FastAPI telemetry service with JWT authentication, relational storage, and accompanying ESP32 firmware for edge sensor telemetry streaming.

---

### Contact & Collaboration
- **Email:** [muqsithanif29@gmail.com](mailto:muqsithanif29@gmail.com)
- **Kaggle Profile:** [@muqsithanif](https://www.kaggle.com/muqsithanif)
