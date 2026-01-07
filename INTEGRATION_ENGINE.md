# 🔌 Integration Engine (HL7 Middleware)

The integration engine functions as the system’s core nervous system.

## HL7 Listener (MLLP)

- TCP-based server listening on configurable ports
- Receives HL7 messages from analyzers
- Designed for devices such as clinical chemistry analyzers

## HL7 Parsing Logic

- Translates raw HL7 segments into structured data
- Extracts:
  - Test identifiers
  - Sample execution events
  - Result metadata

## Shadow Mode

The system supports **Shadow Mode**, allowing:
- Passive monitoring of analyzer output
- Zero interference with existing LIS workflows
- Safe validation before full activation
