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


## XRT Installation (For Alveo U250)

To install XRT and the associated deployment and development platforms for Alveo U250, follow these steps:

1. Download XRT, Deployment, and Development platforms version 2019.1 from [here](https://www.xilinx.com/products/boards-and-kits/alveo/package-files-archive/u250-2019-1.html).

2. Install XRT and the platforms according to the instructions provided in the Xilinx user guide UG1301 version 1.3
   **Warning:** If you have already installed a different version of XRT and have an Alveo card flashed with it, you need to remove the current XRT installation, revert the Alveo card to the golden image, and then install XRT version 2019.1
   
   For managing the version of XRT, refer to the instructions provided [here](https://xilinx.github.io/Alveo-Cards/master/debugging/build/html/docs/modifying-xrt-platform.html).

