# Predicting handwritten digits
Copyright (c) 2020 Michio Inoue
Copyright (c) 2021 Paul Peeling

We take a deep learning ONNX model pre-trained on MNIST data from  https://github.com/onnx/models/tree/master/vision/classification/, import this into MATLAB and implement as a form of WebAssembly, through "Generate JavaScript Using MATLAB Coder" version 3.0.1 by Geoff McVittie. The tool allows you to create JavaScript/WebAssembly libraries from MATLAB projects using MATLAB Coder.

You can find the tool here:
https://mathworks.com/matlabcentral/fileexchange/69973-generate-javascript-using-matlab-coder

- Step 1: Draw a digit 
- Step 2: Click [Prediction]

The HTML is based on https://github.com/yukagil/tfjs-mnist-cnn and https://github.com/minoue-xx/handwritten-digit-prediction-on-browser (Thank you!)
