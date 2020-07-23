# ONNX学习
## 目录介绍
* models—模型保存路径
* images—图片路径
* jupyter—代码路径
    * [PytorchOnnxExport.ipynb](jupyter/PytorchOnnxExport.ipynb)——onnx[官方案例2](https://github.com/onnx/tutorials/blob/master/tutorials/PytorchOnnxExport.ipynb)
    * [super_resolution_with_onnxruntime.ipynb](jupyter/super_resolution_with_onnxruntime.ipynb)——pytorch[官方案例](https://pytorch.org/tutorials/advanced/super_resolution_with_onnxruntime.html)|onnx案例1
    * [VersionConversion.ipynb](jupyter/VersionConversion.ipynb)——[ONNX版本更改](https://github.com/onnx/tutorials/blob/master/tutorials/VersionConversion.md)  
    * [float32_float16_onnx.ipynb](jupyter/float32_float16_onnx.ipynb)——精度转换[官方案例](https://github.com/onnx/onnx-docker/blob/master/onnx-ecosystem/converter_scripts/float32_float16_onnx.ipynb)
        
    * [ONNX-ML.ipynb](jupyter/ONNX-ML.ipynb)——ONNXRuntime[官方案例](https://microsoft.github.io/onnxruntime/python/tutorial.html)
    * [PythonAPI.ipynb](jupyter/PythonAPI.ipynb)——ONNX python API[官方案例](https://github.com/onnx/onnx/blob/master/docs/PythonAPIOverview.md)
        * Loading an ONNX Model
        * Loading an ONNX Model with External Data
        * Saving an ONNX Model
        * Manipulating TensorProto and Numpy Array
        * Creating an ONNX Model Using Helper Functions
        * Checking an ONNX Model
        * Checking a Large ONNX Model >2GB
        * Optimizing an ONNX Model
        * Running Shape Inference on an ONNX Model
        * Converting Version of an ONNX Model within Default Domain (""/"ai.onnx")
        * Utility Functions
                * Polishing the Model
        * Tools
                * Updating Model's Inputs Outputs Dimension Sizes with Variable Length


* ai-serving
    * [AIServingMnistOnnxModel.ipynb](ai-serving/AIServingMnistOnnxModel.ipynb)——[使用AI-serving容器部署案例](https://github.com/autodeployai/ai-serving/blob/master/examples/AIServingMnistOnnxModel.ipynb)
* onnxruntime-serving   
    * [OnnxRuntimeServerSSDModel.ipynb](onnxruntime-serving/OnnxRuntimeServerSSDModel.ipynb)——SSD ONNXRuntime[官方案例](https://github.com/onnx/tutorials/blob/master/tutorials/OnnxRuntimeServerSSDModel.ipynb)