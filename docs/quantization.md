# INT8 Quantization Accuracy Comparison

| Device Name          | Top-1 Accuracy |
|----------------------|----------------|
| Float32  (ONNX-GPU)  | 0.100          |
| INT8 (ONNX-CPU-INT8) | 0.109          |

**Notes**:
- Quantization to INT8 performed using `quantize_dynamic` with `QUInt8`.
- Warning observed during quantization: 'Please consider to run pre-processing before quantization.'

