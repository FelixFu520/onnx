# ONNX学习
## 一、环境
### Docker环境
https://hub.docker.com/r/onnx/onnx-ecosystem    
### 主机环境
略
## 目录介绍
* models—模型保存路径
* images—图片路径
* jupyter—代码路径
    * PytorchOnnxExport.ipynb——onnx[官方案例2](https://github.com/onnx/tutorials/blob/master/tutorials/PytorchOnnxExport.ipynb)
    * super_resolution_with_onnxruntime.ipynb——pytorch[官方案例](https://pytorch.org/tutorials/advanced/super_resolution_with_onnxruntime.html)|onnx案例1
    * VersionConversion.ipynb——[ONNX版本更改](https://github.com/onnx/tutorials/blob/master/tutorials/VersionConversion.md)  
    * float32_float16_onnx.ipynb——精度转换[官方案例](https://github.com/onnx/onnx-docker/blob/master/onnx-ecosystem/converter_scripts/float32_float16_onnx.ipynb)
        
    * ONNX-ML.ipynb——ONNXRuntime[官方案例](https://microsoft.github.io/onnxruntime/python/tutorial.html)




## 二、学习项目
### 1、tutorial01
这个案例是使用onnx.ml的，参考[Link](https://zhuanlan.zhihu.com/p/86867138)   
### 2、tutorial02
这个案例是Pytorch官网API中的内容，参考[Link](https://pytorch.org/docs/master/onnx.html#example-end-to-end-alexnet-from-pytorch-to-onnx)   
### 3、tutorial03
这个案例是Pytorch官网的Tutorial中的内容，参考[Link](https://pytorch.org/tutorials/advanced/super_resolution_with_onnxruntime.html)
### 4、tutorial04
这个案例是ONNX官方的python API，参考[Link](https://github.com/onnx/onnx/blob/master/docs/PythonAPIOverview.md)   
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
