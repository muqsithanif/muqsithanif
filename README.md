# Muqsit Hanif

**AI & Robotics Systems Engineer**

[![Kaggle](https://img.shields.io/badge/Kaggle-profile-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/meguminksdj)
[![Email](https://img.shields.io/badge/Email-muqsithanif29%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:muqsithanif29@gmail.com)

I build software where machine learning meets physical equipment: computer vision, robot motion, and industrial automation. Most of the projects below run against simulators or public datasets rather than hardware. Each README says what was measured, on what data, and what the numbers do not cover.

---

### Selected work

| Project | What it is | Measured |
|---|---|---|
| [multi-uav-perception](https://github.com/muqsithanif/multi-uav-perception) | Aerial detection and tracking: YOLO fine-tuned on VisDrone, ONNX and OpenVINO exports checked for agreement, ByteTrack vs BoT-SORT, and target assignment for three virtual UAVs over a ROS 2 Jazzy graph with a C++ monitor node | mAP50 0.154 → 0.402 on a locked validation subset |
| [machine-health-monitor](https://github.com/muqsithanif/machine-health-monitor) | Predictive maintenance scored on how early the warning comes, not on accuracy, across five simulated machines | EWMA warns ~9 days before fault onset; Isolation Forest only after it |
| [reactor-plc-trainer](https://github.com/muqsithanif/reactor-plc-trainer) | Batch-reactor simulator that speaks the CODESYS gateway protocol, so students control it with real ladder logic in Machine Expert; includes a 12-chapter beginner course in Indonesian | Its headless mode generated the 400-batch fouling study used against the machine-health detectors |
| [modbus-monitor](https://github.com/muqsithanif/modbus-monitor) | Modbus TCP monitoring: engineering-unit scaling, 4–20 mA loop-fault detection, alarm hysteresis, and a plant simulator to run against | End-to-end test over a real TCP socket |
| [agvnav](https://github.com/muqsithanif/agvnav) | Factory AGV simulation: A* global path, DWA local control on LiDAR only, and safety fields that stop for a worker the robot is never told about | No collisions; closest approach 0.16 m to the worker |
| [conveyorsort](https://github.com/muqsithanif/conveyorsort) | Reject sorter tracking packages by encoder instead of timer, firing a PLC coil over Modbus TCP, with the belt slowing and stopping mid-run | Reject within 10 mm vs 330 mm for a fixed timer |

### More projects

- [visiongrasp](https://github.com/muqsithanif/visiongrasp): UR5 pick-and-place in simulation. It covers RGB-D detection, pixel-to-base deprojection, orientation-constrained IK and quintic trajectories.
- [defectscan](https://github.com/muqsithanif/defectscan): PatchCore-style anomaly detection with a memory bank of patch features and a greedy coreset.
- [wateraudit](https://github.com/muqsithanif/wateraudit): effluent BOD/COD soft sensors with conformal prediction intervals, tested in time order on the UCI Water Treatment Plant data.
- [driftdetect](https://github.com/muqsithanif/driftdetect): a dataset-shift audit with FDR-controlled per-column tests, adversarial validation and attribution, tested on injected drift and real plant data.
- [visual-inspection-api](https://github.com/muqsithanif/visual-inspection-api): serves YOLO-style ONNX detectors over HTTP, with the output layout detected automatically and NMS written in NumPy.
- [iot-telemetry-api](https://github.com/muqsithanif/iot-telemetry-api): FastAPI telemetry service with JWT auth, idempotent batch ingestion, and the ESP32 firmware that feeds it.

### Tools I use

- **Languages:** Python, C++, VB.NET, Arduino (ESP32)
- **Vision and ML:** PyTorch, Ultralytics YOLO, OpenCV, ONNX Runtime, OpenVINO, scikit-learn, LightGBM
- **Robotics:** ROS 2 Jazzy, URDF with ikpy, A* and DWA planning
- **Industrial:** Modbus TCP (pymodbus), the CODESYS gateway, 4–20 mA signals, ladder logic
- **Backend:** FastAPI, SQLAlchemy, MySQL/SQLite, Docker Compose
