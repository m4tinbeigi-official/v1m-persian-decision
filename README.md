# v1m: System One Calibrated Decision Model for Persian

**v1m** is an open-source, ultra-low latency System One decision model trained specifically for Persian and multilingual intent classification, risk assessment, and discrete business decisions.

- **Architecture:** `jhu-clsp/mmBERT-base` encoder + 2-layer decision head
- **Parameters:** ~322M
- **Inference Runtime:** ONNX Runtime / Ollaya (`family: laya`, layout `laya-markers-v1`)
- **Primary Language:** Persian (`fa`), Multilingual (`en`, `ar`)
- **Calibrated Temperature:** `[1.0, 1.0, 1.0]`
- **Official Host:** [v1m.ir](https://v1m.ir)

## Supported Primitives
1. `choice`: Multi-option categorical selection
2. `score`: Calibrated ordinal risk/priority scale
3. `noul`: Binary boolean decision (`false` / `true`)

## License
Apache-2.0
