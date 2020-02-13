# Tensorrt

## For record 
### Python
- Prepare model (pytorch->onnx) [code]()
  -  ceil_mode = True and pow method make bugs on pytorch->onnx

### C++
- Control Engine [link](https://github.com/NVIDIA/TensorRT/blob/572d54f91791448c015e74a4f1d6923b77b79795/samples/common/sampleEngines.cpp#L488-L516)
  - Method of loading Engine ( ONNX -> TRT) [link](https://github.com/NVIDIA/TensorRT/blob/572d54f91791448c015e74a4f1d6923b77b79795/samples/common/sampleEngines.cpp#L488-L516)
- Method of Using Mat img for TRT[link](https://devtalk.nvidia.com/default/topic/987599/tensorrt/tensorrt-how-cv-mat-convert-to-nhcw-format-/)

