# CoreML to ONNX converter
Just a simple snippet which input the coreML model and output onnx models

## Requirement
 - coremltools
 - winmltools

## Usage
> $ python coreml_to_onnx.py `coreML_model` `onnx_model`

* `coreML_model` : The name of the model you want to convert, ended with ".mlmodel"
* `onnx_model` : The output name of the onnx model.

**Note:** CoreMLTools is a Python package provided by Apple, but is not available on Windows. If you need to install the package on Windows, install the package directly from the repo:

```
$ pip install git+https://github.com/apple/coremltools
```
