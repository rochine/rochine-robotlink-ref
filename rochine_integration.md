# Rochine RobotLink — Integration Notes

Purpose:
- Prototype device enrollment (pubkey/DID)
- Telemetry signing (GPS/IMU/timestamp)
- Minimal verbs: `MoveTo`, `CaptureImage`, `MeasureSensor`

Next:
- Map ROS2 topics → RobotLink adapter
- MQTT/WebSocket bridge for DApp Console
- Proof payload → canonical JSON → SHA-256 → submit to Devnet
