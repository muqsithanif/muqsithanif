# Muqsit Hanif

**AI & Robotics Systems Engineer** | *Bridging Machine Intelligence to Physical & Industrial Systems*

[![GitHub](https://img.shields.io/badge/GitHub-muqsithanif-181717?style=flat-square&logo=github)](https://github.com/muqsithanif)
[![Kaggle](https://img.shields.io/badge/Kaggle-meguminksdj-20BEFF?style=flat-square&logo=kaggle)](https://www.kaggle.com/meguminksdj)
[![Email](https://img.shields.io/badge/Email-muqsithanif29%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:muqsithanif29@gmail.com)

---

### Focus & Specialization
I design and deploy end-to-end intelligent systems that operate at the intersection of **Computer Vision, Real-Time Edge Inference, Robotics Perception, Industrial Automation, and Competitive Data Science**. My work focuses on low-latency inference, deterministic hardware protocols, distribution shift robustness, and physical edge architectures.

- **Robotics & Physical AI:** Autonomous 6-DoF manipulator perception, SE(3) hand-eye coordinate transforms, mobile robot (AMR/AGV) SLAM, global A* graph search, and reactive Dynamic Window Approach (DWA).
- **Industrial Vision & Unsupervised QA:** Memory-bank anomaly detection (PatchCore/Coreset), zero-framework ONNX serving, and pixel-level defect localization.
- **Competitive Data Science & Robust ML:** Covariate shift quantification, adversarial validation, leakage guard scanning, and importance-weighted cross-validation (IWCV) for tabular pipelines.
- **Industrial Automation & IIoT:** Deterministic encoder-tracked sorting, Modbus TCP/IP communication, CODESYS gateway integration, and 4–20 mA current loop fault diagnostics.
- **Predictive Maintenance:** Statistical anomaly detection (EWMA control charts) benchmarked on mechanical lead times for industrial rotating machinery.

---

### Technical Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Robotics & Motion Control** | 6-DoF Kinematics (FK/IK), Trajectory Planning (Quintic Polynomials), DWA Local Planner, Global A*, ROS 2, URDF |
| **Vision & Anomaly Detection** | PatchCore, Coreset Subsampling, Gabor Filter Banks, PyTorch, OpenCV, ONNX Runtime, OpenVINO, YOLO |
| **Data Science & ML Robustness** | Adversarial Validation, Two-Sample KS-Test, Wasserstein-1, Sample-Size Calibrated PSI, LightGBM, Scikit-Learn |
| **Industrial & Protocols** | Modbus TCP/IP, CODESYS Gateway Protocol, Rotary Optical Encoders, 4–20 mA Loops, MQTT, REST APIs |
| **Mobile Robotics & Sensing** | 2D Planar LiDAR Raycasting, C-Space Obstacle Inflation, UAV Aerial Perception, ESP32 Firmware |
| **Backend & Infrastructure** | FastAPI, SQLite/MySQL, NumPy, SciPy, Pandas, Docker, Git CI/CD |

---

### Featured Systems & Repositories

#### 1. Competitive Data Science & Production ML Robustness
- **[driftdetect](https://github.com/muqsithanif/driftdetect)**  
  *Covariate Shift Quantification, Adversarial Validation & Adaptive Alignment*  
  Industrial and Kaggle-grade distribution shift engine. Features two-sample Kolmogorov-Smirnov, normalized Wasserstein-1, sample-size calibrated PSI (chi-square null), LightGBM out-of-fold adversarial validation, leakage guard detection, consensus culprit scoring, RAFE feature elimination, and importance-weighted cross-validation (IWCV).

- **[machine-health-monitor](https://github.com/muqsithanif/machine-health-monitor)**  
  *Early Mechanical Fault Detection on Industrial Bearings*  
  Benchmarking statistical time-series control charts against modern unsupervised ML; demonstrates EWMA providing a 9-day earlier warning horizon over Isolation Forest for developing mechanical failures.

- **[iot-telemetry-api](https://github.com/muqsithanif/iot-telemetry-api)**  
  *Idempotent Industrial Sensor Ingestion Pipeline*  
  FastAPI telemetry service with JWT authentication, relational storage, and accompanying ESP32 firmware for edge sensor telemetry streaming.

#### 2. Robotics Perception & Autonomous Navigation
- **[visiongrasp](https://github.com/muqsithanif/visiongrasp)**  
  *Autonomous 6-DoF Robotic Manipulator with RGB-D Perception*  
  End-to-end pick-and-place pipeline integrating pinhole camera ray de-projection, oriented grasp pose estimation, numerical inverse kinematics, and minimum-jerk quintic trajectory planning. Includes 11 automated invariant tests and 3D simulation rendering.

- **[agvnav](https://github.com/muqsithanif/agvnav)**  
  *Autonomous Factory AMR / AGV Navigation & Obstacle Avoidance*  
  Full mobile robot navigation stack for factory shop floors featuring 2D planar LiDAR raycasting, configuration-space obstacle dilation, global A* path planning with string-pulling smoothing, and reactive Dynamic Window Approach (DWA) for dynamic worker avoidance.

- **[multi-uav-perception](https://github.com/muqsithanif/multi-uav-perception)**  
  *Aerial Object Detection & Tracking Pipeline*  
  Fine-tuned vision detectors on aerial imagery (VisDrone), optimized via ONNX and OpenVINO with cross-format agreement validation, integrated into multi-target tracking benchmarks.

#### 3. Industrial Machine Vision & Quality Assurance
- **[defectscan](https://github.com/muqsithanif/defectscan)**  
  *Industrial Unsupervised Visual Anomaly Detection & Defect Localization*  
  PatchCore-style inspection pipeline trained exclusively on nominal workpieces. Employs multi-scale steerable Gabor embeddings, greedy minimax k-center coreset subsampling (85% memory reduction), and k-NN distance scoring to achieve 100% image-level AUROC and 99.1% pixel-level localization on manufacturing flaws.

- **[visual-inspection-api](https://github.com/muqsithanif/visual-inspection-api)**  
  *Zero-Framework ONNX Model Serving for Industrial QA*  
  High-throughput HTTP serving engine for YOLO-family ONNX detectors. Features layout auto-detection, pure NumPy NMS from scratch, and eliminates heavy training framework dependencies in production runtime.

#### 4. Industrial Automation, IIoT & Hardware-in-the-Loop
- **[conveyorsort](https://github.com/muqsithanif/conveyorsort)**  
  *Closed-Loop Vision-to-PLC Industrial Reject Sorter*  
  Deterministic package sorting system immune to conveyor speed variations. Synchronizes high-speed vision decisions with an optical rotary incremental encoder shift register, actuating pneumatic reject solenoids over Modbus TCP at sub-millimeter precision.

- **[modbus-monitor](https://github.com/muqsithanif/modbus-monitor)**  
  *Industrial Equipment & Loop Health Monitor over Modbus TCP*  
  Engineering-unit scaling engine, 4–20 mA loop-fault detection (under-range/over-range), alarm hysteresis, and a zero-hardware plant simulator for deterministic testing.

- **[reactor-plc-trainer](https://github.com/muqsithanif/reactor-plc-trainer)**  
  *Batch Reactor Simulator with CODESYS Gateway Protocol*  
  Hardware-free industrial simulation bridge allowing real ladder logic in Machine Expert / CODESYS to control virtual batch processing plants.

---

### Contact & Collaboration
- **Email:** [muqsithanif29@gmail.com](mailto:muqsithanif29@gmail.com)
- **Kaggle Profile:** [@meguminksdj](https://www.kaggle.com/meguminksdj)
