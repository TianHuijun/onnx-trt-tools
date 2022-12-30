# onnx-trt-tools

- Source:
  - <https://github.com/NVIDIA/TensorRT/blob/main/samples/python/efficientdet>

## onnx tools

- [modify_onnx.py](onnx_tools/modify_onnx.py): modify input and output of onnx model

## trt tools

- [build_engine.py](trt_tools/build_engine.py): build engine with fp32, fp16, int8 (must provide calib images)
- [image_batcher.py](trt_tools/image_batcher.py): for calibrate with int8, must **provide preprocess** for in model in that script
- [test_running_time](trt_tools/test_running_time.py): test .trt running time
