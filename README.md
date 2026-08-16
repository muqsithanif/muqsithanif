



**[reactor-plc-trainer](https://github.com/muqsithanif/reactor-plc-trainer)** · A batch chemical reactor in software that students drive with real ladder logic written in Schneider Machine Expert. It implements the CODESYS gateway protocol directly over TCP, exposes 23 industrial I/O tags on the 4-20 mA convention, and carries a 12-chapter beginner course built into the application.

**[multi-uav-perception](https://github.com/muqsithanif/multi-uav-perception)** · Aerial object detection and tracking, from dataset conversion through fine-tuning to optimised CPU inference. I fine-tuned a YOLO nano detector on VisDrone and exported it to ONNX and OpenVINO, verifying that both runtimes still agreed with the original model before measuring latency. Every reported number traces back to a versioned experiment artefact.

**Daily air-quality forecasting for Jakarta** *(undergraduate thesis, repository private)* · Six regression models compared under walk-forward cross-validation that respects time order, tuned with Optuna, with significance testing so the conclusions stay proportional to the evidence. Available on request.

**[machine-health-monitor](https://github.com/muqsithanif/machine-health-monitor)** · Predictive maintenance evaluated on lead time rather than accuracy. An EWMA control chart gives roughly nine days of warning on developing bearing faults, and the repository explains why it outperforms Isolation Forest on this problem.

**[modbus-monitor](https://github.com/muqsithanif/modbus-monitor)** · Polls industrial equipment over Modbus TCP, scales raw registers into engineering units, and evaluates alarms with hysteresis. Reports a cut 4-20 mA loop as a fault rather than as a low reading.

**[visual-inspection-api](https://github.com/muqsithanif/visual-inspection-api)** · Serves any YOLO-style ONNX export over HTTP, with box decoding and non-maximum suppression implemented directly so the runtime carries no training framework.

**[iot-telemetry-api](https://github.com/muqsithanif/iot-telemetry-api)** · Telemetry ingestion built around the ways field devices misbehave: replayed batches, drifting clocks, and partially malformed payloads. Ships with the ESP32 firmware that feeds it.
