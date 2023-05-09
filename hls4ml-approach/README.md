## Setting up the Environment and Installing Dependencies

Create a new Conda environment named 'hls4ml' with Python 3.8
```
conda create -n hls4ml python=3.8
```
Activate the 'hls4ml' Conda environment
```
conda activate hls4ml
```
Install the development version of HLS4ML and its dependencies using pip
```
pip install git+https://github.com/fastmachinelearning/hls4ml@main
```
Install additional packages using pip
```
pip install jupyter onnx tensorflow==2.4.0 tensorflow_datasets qkeras==0.9.0 scikit-learn conifer==0.2b0
```
Install PyTorch based on the installed CUDA version
Follow the [instructions](https://pytorch.org/get-started/locally/) based on your CUDA version
