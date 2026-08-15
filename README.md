# Muqsit Muhammad Hanif

Industrial Automation and Robotics Engineering graduate. I work at the intersection of three things that rarely sit in one person: **embedded and control systems**, **applied machine learning**, and **documentation that lets other people verify the work**.

Most of what I build follows the same shape — data comes off a sensor or a dataset, a model turns it into a decision, and the decision has to run somewhere real and be checkable afterwards.

---

### What I work with

**Languages** · Python · C/C++ · C# · JavaScript
**ML & CV** · PyTorch · scikit-learn · XGBoost · Optuna · OpenCV · Ultralytics YOLO
**Deployment** · ONNX Runtime · OpenVINO · model export and numerical-agreement validation
**Embedded & IoT** · ESP32 · Arduino · Raspberry Pi · MQTT · Firebase · sensor acquisition
**Industrial** · PLC (Siemens S7-1500 / TIA Portal, Omron, Mitsubishi, Keyence) · HMI · process control
**Engineering** · Git · pytest · YAML-driven config · Linux/WSL2 · reproducible pipelines

---

### Selected work

**[multi-uav-perception](https://github.com/muqsithanif/multi-uav-perception)** — Aerial object detection and tracking, from dataset conversion through fine-tuning to optimised CPU inference. Fine-tuned a YOLO nano detector on VisDrone and exported it to ONNX and OpenVINO, verifying that both runtimes still agreed with the original model before measuring latency. Every reported number traces back to a versioned experiment artefact.

**[aqi-jakarta-render](https://github.com/muqsithanif/aqi-jakarta-render)** — Daily air-quality forecasting for Jakarta. Six regression models compared under walk-forward cross-validation that respects time order, tuned with Optuna, with statistical significance testing so the conclusions stay proportional to the evidence. This was my undergraduate thesis.

---

### A note on how I work

I try to make failures visible rather than tidy them away. In the UAV project, two export-agreement tests failed before they passed — both are still in the commit history, along with what caused them. In the forecasting study, some of the winning model's advantages turned out not to be statistically significant, and the write-up says so.

Reproducibility is the part I care most about: pinned library versions, dataset hashes, fixed seeds, and enough documentation that a stranger can run the whole thing from a clean checkout.

---

📍 Bandung, Indonesia · 📧 muqsithanif29@gmail.com
