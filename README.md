# Muqsit Muhammad Hanif

**[reactor-plc-trainer](https://github.com/muqsithanif/reactor-plc-trainer)** · A chemical reactor that exists only in software, so students can practise industrial control without a plant to practise on. It speaks the CODESYS gateway protocol directly, which lets a program written in Schneider Machine Expert drive it, and carries a twelve-chapter course for readers who have never seen a PLC.

**[multi-uav-perception](https://github.com/muqsithanif/multi-uav-perception)** · Aerial object detection and tracking, carried from a raw dataset through fine-tuning to measured CPU inference. I exported the fine-tuned detector to ONNX and OpenVINO and confirmed that both still produced the same detections as the original before timing them, because a faster model that quietly detects different things is not an optimisation.

**Daily air-quality forecasting for Jakarta** *(undergraduate thesis, repository private)* · Six regression models compared under walk-forward cross-validation that respects time order, tuned with Optuna, with significance testing so the conclusions stay proportional to the evidence. Available on request.

**[machine-health-monitor](https://github.com/muqsithanif/machine-health-monitor)** · Predictive maintenance scored on how early the warning arrives rather than on accuracy, because a detector that flags a bearing three hours before it seizes is correct and unusable. A control chart designed in the 1950s gives about nine days of notice where Isolation Forest gives none, and the repository explains the mechanism.

**[modbus-monitor](https://github.com/muqsithanif/modbus-monitor)** · Polls industrial equipment over Modbus TCP and turns raw registers into real measurements. A 4-20 mA sensor with a cut wire reads zero, which looks like a valid low reading unless you check for it, so this reports it as a fault instead.

**[visual-inspection-api](https://github.com/muqsithanif/visual-inspection-api)** · Serves any YOLO-style model over HTTP. Box decoding and duplicate-box suppression are written out rather than imported, which keeps the deployed service down to three dependencies and keeps an AGPL-licensed training library out of it entirely.

**[iot-telemetry-api](https://github.com/muqsithanif/iot-telemetry-api)** · Telemetry ingestion designed around the ways field devices fail: networks that drop mid-delivery, clocks that drift, and batches with one bad row in fifty. The ESP32 firmware that feeds it is in the same repository, so both ends of the link can be checked against each other.

📍 Bandung, Indonesia · 📧 muqsithanif29@gmail.com
